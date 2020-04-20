# 1. Python
```
x = "Hello World"                                 // Text Type : str

x = 10                                            // Numeric Type : int
x = 10.2                                          // Numeric Type : float
x = 1j                                            // Numeric Type : complex

x = ["first", "second", "Third"]                  // Sequence Type : list
x = ("first", "second", "third"]                  // Sequence Type : tuple
x = range(5)                                      // Sequence Type : range

x = {"first" : 1, "second" : 2}                   // Mapping Type : dictionary

x = {"first_value","seoncd_value"}                // Set Type : set
x = frozenset({"first", "second", "third"})       // Set Type : frozenset

x = True                                          // Boolean Type : bool

x = b"Hello"                                      // Binary Type : bytes
x = bytearray(5)                                  // Binary Type : bytearray
x = memoryview(bytes(5))                          // Binary Type : memoryview
```

# 2. C
- [Data Types range](https://docs.microsoft.com/ko-kr/cpp/cpp/data-type-ranges?view=vs-2019)
```
char myChar = 'c'                                 // Primitive Type : 1 byte
short myShort = 123;                              // Primitive Type : 2 bytes
int myInt  = 32;                                  // Primitive Type : 4 bytes
long myLong = 456123;                             // primitive Type : 4 bytes
float myFloat = 5.54345;                          // Primitive Type : 4 bytes
double myDouble = 5.812352352;                    // Primitive Type : 8 bytes
long double myLongDouble = 5.81232345;            // Primitive Type : 8 bytes

unsigned 'data_type'      : just '+'

void : 타입 없음. 리턴값이 없는 함수에 쓰이거나 함수가 매개변수를 사용하지 않음을 나타냄
```

# 3. C++
- [C++ Data Types](https://docs.microsoft.com/en-us/cpp/cpp/cpp-type-system-modern-cpp?view=vs-2019)
```
char myChar = 'A';                                // Primitive Type : 1 byte
int myNum = 5;                                    // Primitive Type : 4 bytes
float myFloatNum = 5.23;                          // Primitive Type : 4 bytes
double myDoubleNum = 9.98562;                     // Primitive Type : 8 bytes
bool myBool = true;                               // Primitive Type : 1 byte

string myString = "This is my String"             // String Type
auto myAddress = "This is my Address"             // let compiler deduce the type

unsigned 'data type'      : just '+'

void : 타입 없음. 리턴값이 없는 함수에 쓰이거나 함수가 매개변수를 사용하지 않음을 나타냄
```

# 4. C#
- [.NET Data Types](https://www.tutorialspoint.com/vb.net/vb.net_data_types.htm)
- [.NET Data Types](https://docs.microsoft.com/en-us/windows/win32/wmp/about--net-framework-data-types)
```
byte myByte = 64;                                   // Integral Number : 1 byte
short myShort = 156;                                // Integral Number : 2 bytes
int myInt = 4566;                                   // Integral Number : 4 bytes
long myLong = 456897;                               // Integral Number : 8 bytes

float myFloat = 45.312;                             // Real Number : 4 bytes
double myDouble = 45.123456;                        // Real Number : 8 bytes
decimal myDecimal = 45.123456123;                   // Real Number : 16 bytes

bool myBool = True;                                 // Boolean Type : 1 byte

char myChar = 'm';                                  // Unicode Character : 2 bytes
string myStr = "This is my string!";                // String Type

var i = 0;                                          // Implicitly Typed
```

# 5. Java
```
byte myByte = 12;                                   // Primitive Type : 1 byte
short myShort = 1234;                               // Primitive Type : 2 bytes
int myInt = 1231456;                                // Primitive Type : 4 bytes
long myLong = 123156456;                            // Primitive Type : 8 bytes
float myFloat = 12.32;                              // Primitive Type : 4 bytes
double myDouble = 12.235645;                        // Primitive Type : 8 bytes
char myChar = 'b';                                  // Primitive Type : 1 byte
boolean = true;                                     // Primitive Type : 1 byte

String myStr = "This is my string";                 // String Class
```

# 6. JavaScript ES6
```
var myNumber = 123;                                 // Primitive Type : number
var myString = "This is my string!";                // Primitive Type : string
var myBoolean = true;                               // Primitive Type : boolean
var x;                                              // Primitive Type : undefined

var myInfo = {name: 'myName', age: 34);             // Complex Data : object
var arr = [1, 2, 3];                                // Complex Data : array = object
var x = null;                                       // Complex Data : null = object
var x = myFunc(){}                                  // Complex Data : function
```

# 7. Rust
