
Here are all the Visual Basic .NET keywords categorized for better understanding:

## **Reserved Keywords (Cannot be used as identifiers)**

### **Declaration Keywords**
```vb
Class     Structure   Module     Interface   Enum
Namespace Imports     Using      Assembly    Get
Set       Property    Sub        Function    Sub
Delegate  Event       AddHandler RemoveHandler RaiseEvent
```

### **Access Modifiers**
```vb
Public    Private    Protected   Friend     Protected Friend
Shadows   Overloads  Overrides   Overridable MustInherit
NotInheritable MustOverride Shared      Static
```

### **Data Types**
```vb
Boolean   Byte       Char       Date       Decimal
Double    Integer    Long       Object     Short
Single    String     UInteger   ULong      UShort
```

### **Type Conversion**
```vb
CType     DirectCast TryCast    CBool      CByte
CChar     CDate      CDec       CDbl       CInt
CLng      CObj       CSByte     CShort     CSng
CStr      CUInt      CULng      CUShort
```

### **Control Flow**
```vb
If       Then     Else     ElseIf   Select   Case
For      To       Step     For Each In       Next
While    Do       Loop     Until    Continue
Exit     Return   GoTo
```

### **Exception Handling**
```vb
Try      Catch    Finally   Throw    When
```

### **Operators**
```vb
And      Or       Not       Xor      AndAlso  OrElse
Is       IsNot    Like      Mod      New      AddressOf
GetType  TypeOf
```

### **Miscellaneous**
```vb
Me       MyBase   MyClass   Nothing  Global   Inherits
Implements With     End      WithEvents Handles
```

## **Contextual Keywords (Can be used as identifiers in most contexts)**

### **LINQ Keywords**
```vb
From      Where     Select    Order By  Group By  Join
On        Into      Let       Skip      Take      Aggregate
Distinct  By        In        Ascending Descending
```

### **Async Programming**
```vb
Async     Await
```

### **Iterators**
```vb
Iterator  Yield
```

### **Partial Classes**
```vb
Partial
```

### **Generic Constraints**
```vb
As        New       Of
```

### **Other Contextual Keywords**
```vb
Alias     Mid       Off       Strict    Explicit On
Custom    IsExternalInit
```

## **Complete Alphabetical List**

```vb
AddHandler   AddressOf    Alias        And          AndAlso
As           Async        Auto         Await        Boolean
ByRef        Byte         ByVal        Call         Case
Catch        CBool        CByte        CChar        CDate
CDec         CDbl         Char         CInt         Class
CLng         CObj         Const        Continue     CSByte
CShort       CSng         CStr         CType        CUInt
CULng        CUShort      Custom       Date         Decimal
Declare      Default      Delegate     Dim          DirectCast
Do           Double       Each         Else         ElseIf
End          Enum         Erase        Error        Event
Exit         False        Finally      For          Friend
Function     Get          GetType      GetXMLNamespace Global
GoTo         Handles      If           Implements   Imports
In           Inherits     Integer      Interface    Into
Is           IsNot        Iterator     Join         Key
Let          Lib          Like         Long         Loop
Me           Mod          Module       MustInherit  MustOverride
MyBase       MyClass      Namespace    Narrowing    New
Next         Not          Nothing      NotInheritable NotOverridable
Object       Of           On           Operator     Option
Optional     Or           OrElse       Overloads    Overridable
Overrides    ParamArray   Partial      Private      Property
Protected    Public       RaiseEvent   ReadOnly     ReDim
RemoveHandler Resume       Return       SByte        Select
Set          Shadows      Shared       Short        Single
Static       Step         Stop         String       Structure
Sub          SyncLock     Then         Throw        To
True         Try          TryCast      TypeOf       UInteger
ULong        UShort       Using        When         While
Widening     With         WithEvents   WriteOnly    Xor
Yield
```

## **Notes:**
- **Reserved keywords** cannot be used as variable names, method names, or other identifiers
- **Contextual keywords** have special meaning only in specific contexts
- Some keywords like `Let`, `Rem`, `Gosub` are retained for backward compatibility but rarely used
- The list may vary slightly depending on the VB.NET version

This comprehensive list covers VB.NET keywords up to the latest versions, including modern features like async/await and LINQ support.
