
以下是所有 Visual Basic .NET 关键字的分类说明，以便更好地理解：

## **保留关键字（不能用作标识符）**

### **声明关键字**
```vb
Class     类        Structure 结构体   Module    模块
Interface 接口      Enum      枚举     Namespace 命名空间
Imports   导入      Using     使用     Assembly  程序集
Get       获取      Set       设置     Property  属性
Sub       过程      Function  函数     Delegate  委托
Event     事件      AddHandler 添加处理器 RemoveHandler 移除处理器
RaiseEvent 引发事件
```

### **访问修饰符**
```vb
Public    公共      Private   私有     Protected 受保护的
Friend    友元      Protected Friend 受保护友元
Shadows   隐藏      Overloads 重载     Overrides 重写
Overridable 可重写   MustInherit 必须继承
NotInheritable 不可继承 MustOverride 必须重写
Shared    共享      Static    静态
```

### **数据类型**
```vb
Boolean   布尔      Byte      字节     Char      字符
Date      日期      Decimal   小数     Double    双精度
Integer   整数      Long      长整型   Object    对象
Short     短整型    Single    单精度   String    字符串
UInteger  无符号整数 ULong     无符号长整型 UShort    无符号短整型
```

### **类型转换**
```vb
CType     类型转换  DirectCast 直接转换 TryCast    尝试转换
CBool     转布尔    CByte      转字节   CChar      转字符
CDate     转日期    CDec       转小数   CDbl       转双精度
CInt      转整数    CLng       转长整型 CObj       转对象
CSByte    转有符号字节 CShort    转短整型 CSng       转单精度
CStr      转字符串  CUInt      转无符号整数 CULng     转无符号长整型
CUShort   转无符号短整型
```

### **控制流程**
```vb
If        如果      Then      那么     Else      否则
ElseIf    否则如果  Select    选择     Case      情况
For       对于      To        到       Step      步长
For Each  对于每个  In        在...中  Next      下一个
While     当...时  Do        执行     Loop      循环
Until     直到      Continue  继续
Exit      退出      Return    返回     GoTo      转到
```

### **异常处理**
```vb
Try       尝试      Catch     捕获     Finally   最终
Throw     抛出      When      当...时
```

### **运算符**
```vb
And       与        Or        或       Not       非
Xor       异或      AndAlso   短路与   OrElse    短路或
Is        是        IsNot     不是     Like      类似
Mod       取模      New       新建     AddressOf 取地址
GetType   获取类型  TypeOf    类型判断
```

### **杂项**
```vb
Me        当前实例  MyBase    基类     MyClass   当前类
Nothing   空值      Global    全局     Inherits  继承
Implements 实现     With      随着     End       结束
WithEvents 带事件   Handles   处理
```

## **上下文关键字（在大多数情况下可用作标识符）**

### **LINQ 关键字**
```vb
From      从        Where     哪里     Select    选择
Order By  排序      Group By  分组     Join      连接
On        在...上   Into      进入     Let       让
Skip      跳过      Take      获取     Aggregate 聚合
Distinct  去重      By        通过     In        在...中
Ascending 升序      Descending 降序
```

### **异步编程**
```vb
Async     异步      Await     等待
```

### **迭代器**
```vb
Iterator  迭代器    Yield     产出
```

### **分部类**
```vb
Partial   分部
```

### **泛型约束**
```vb
As        作为      New       新建     Of        的
```

### **其他上下文关键字**
```vb
Alias     别名      Mid       中间     Off       关闭
Strict    严格      Explicit  显式     On        开启
Custom    自定义    IsExternalInit 是外部初始化
```

## **按字母顺序排列的完整列表**

```vb
AddHandler   添加处理器   AddressOf    取地址      Alias        别名
And          与          AndAlso      短路与      As           作为
Async        异步        Auto         自动        Await        等待
Boolean      布尔        ByRef        传引用      Byte         字节
ByVal        传值        Call         调用        Case         情况
Catch        捕获        CBool        转布尔      CByte        转字节
CChar        转字符      CDate        转日期      CDec         转小数
CDbl         转双精度    Char         字符        CInt         转整数
Class        类          CLng         转长整型    CObj         转对象
Const        常量        Continue     继续        CSByte       转有符号字节
CShort       转短整型    CSng         转单精度    CStr         转字符串
CType        类型转换    CUInt        转无符号整数 CULng        转无符号长整型
CUShort      转无符号短整型 Custom       自定义      Date         日期
Decimal      小数        Declare      声明        Default      默认
Delegate     委托        Dim          声明        DirectCast   直接转换
Do           执行        Double       双精度      Each         每个
Else         否则        ElseIf       否则如果    End          结束
Enum         枚举        Erase        擦除        Error        错误
Event        事件        Exit         退出        False        假
Finally      最终        For          对于        Friend       友元
Function     函数        Get          获取        GetType      获取类型
GetXMLNamespace 获取XML命名空间 Global       全局        GoTo         转到
Handles      处理        If           如果        Implements   实现
Imports      导入        In           在...中    Inherits     继承
Integer      整数        Interface    接口        Into         进入
Is           是          IsNot        不是        Iterator     迭代器
Join         连接        Key          键          Let          让
Lib          库          Like         类似        Long         长整型
Loop         循环        Me           当前实例    Mod          取模
Module       模块        MustInherit  必须继承    MustOverride 必须重写
MyBase       基类        MyClass      当前类      Namespace    命名空间
Narrowing    窄化        New          新建        Next         下一个
Not          非          Nothing      空值        NotInheritable 不可继承
NotOverridable 不可重写  Object       对象        Of           的
On           在...上     Operator     运算符      Option       选项
Optional     可选        Or           或          OrElse       短路或
Overloads    重载        Overridable  可重写      Overrides    重写
ParamArray   参数数组    Partial      分部        Private      私有
Property     属性        Protected    受保护的    Public       公共
RaiseEvent   引发事件    ReadOnly     只读        ReDim        重定义
RemoveHandler 移除处理器 Resume       恢复        Return       返回
SByte        有符号字节  Select       选择        Set          设置
Shadows      隐藏        Shared       共享        Short        短整型
Single       单精度      Static       静态        Step         步长
Stop         停止        String       字符串      Structure    结构体
Sub          过程        SyncLock     同步锁      Then         那么
Throw        抛出        To           到          True         真
Try          尝试        TryCast      尝试转换    TypeOf       类型判断
UInteger     无符号整数  ULong        无符号长整型 UShort       无符号短整型
Using        使用        When         当...时    While        当...时
Widening     扩宽        With         随着        WithEvents   带事件
WriteOnly    只写        Xor          异或        Yield        产出
```

## **注意：**
- **保留关键字**不能用作变量名、方法名或其他标识符
- **上下文关键字**仅在特定上下文中具有特殊含义
- 一些关键字如 `Let`、`Rem`、`Gosub` 为保持向后兼容而保留，但很少使用
- 具体列表可能因 VB.NET 版本略有不同

这个全面的列表涵盖了直到最新版本的 VB.NET 关键字，包括现代功能如异步/等待和 LINQ 支持。
