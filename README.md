# SwiftStydy
Swift学习记录
var str = "Hello, playground"
print("hello world")
//常量
let girlFriends = 0
//变量
var weight = 100
weight = 120
//值得类型和类型推断
var run:Int = 5
var running = 6
//浮点型(默认类型是Double)
var water : Double = 3.5
//类型安全：变量一旦定义之后，其类型不可以更改
var electric = 3.5
electric = 5
print(electric)
//布尔型：Bool，表示逻辑上的真和假
var isYoung : Bool = true
var isVip = false
//元组（Tuple）:定义变量的组合
var x = 1
var y = 2
var z = 3
var vector = (1,2,3)
vector.0
var (a,b,c) = (1,2,3)
a
b
c
var FFInfo = (name:"FF",age:26,like:"swift")
FFInfo.name
FFInfo.age
FFInfo.like
//可选类型（Optional）:代表变量可能有值得情况
var address : String?
address = "沈阳市恒大绿洲"
//基础操作符
var d = 6
var e = -d      //一元操作符
d + e       //二元操作符
d = 8       //赋值操作符
13 % 3      //数学操作符
var f = 1
f += 2      //组合赋值
//比较操作符：> >= < <= 结果是true或false
1 > 2
3 == 3
//逻辑操作符
true && true && false   //与
true || false || true   //或
let g = false
!g  //非
//字符串与字符
//字符串字面量
"回到洪荒，去支配，去操作"
//空字符串
var h = ""
var i = " "
h.isEmpty
i.isEmpty
var j:Character = "我"
let worlds = "我明天放假啦"
for world in worlds {
    print(world)
}
//连接字符串和字符 +
let k = "洪荒"
let m = "少女"
let n = "傅园慧"
var famous = k + m + n
//向字符串添加字符，用append方法
let number : Character = "1"
famous.append(number)
//字符串z插值
let name = "FF"
let type = "G"
let carNumber = "11"
let price = 158.5
let 订票提示 = "\(name)先生，您订购\(type)\(carNumber)了的往返票，需支付\(price * 2)元。"
//集合类型 数组（有序可重复）：Array 无序不重复 ：Set  无序课重复（每一个值对应一个key）字典：Dictionary
let array = [Int](repeatElement(3, count: 10))
let array2 = Array(1...10)
var places = ["beijing","shanghai","guangzhou","shenzhen"]
places.count
places.isEmpty
places.append("shenyang")
let haiwaiPlace = ["NewYrok","London","Sao paolu"]
places += haiwaiPlace
places[7]
places.insert("Paris", at: 4)
places.remove(at: 8)
