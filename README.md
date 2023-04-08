### 第一周计划

上一次做到stripe调度，后面的就没做了，这次提升了debug能力之后，回来重做。

总结上一次的教训，暴发式的学习不可取，应该日积月累，每天投入固定的时间学习。

先把rust的基础打得再扎实一点。每天2小时。

#### Day7 2023-04-08 周六

6 Expressions
    Assignment
    Type Casts
    Closures
    Onward
7 Error Handling
Panic
    Unwinding
    Aborting
Result
    Catching Errors
    Result Type Aliases
    Printing Errors
    Propagating Errors
    Working with Multiple Error Types
    Dealing with Errors That âCanât Happenâ
    Ignoring Errors
    Handling Errors in main()
    Declaring a Custom Error Type
    Why Results?
8 Crates and Modules
Crates
    Editions
    Build Profiles
Modules
    Nested Modules
    Modules in Separate Files
    Paths and Imports
    The Standard Prelude
    Making use Declarations pub
    Making Struct Fields pub
    Statics and Constants
Turning a Program into a Library
The src/bin Directory
Attributes
Tests and Documentation
    Integration Tests
    Documentation
    Doc-Tests
Specifying Dependencies
    Versions
    Cargo.lock
Publishing Crates to crates.io
Workspaces
More Nice Things

#### Day6 2023-04-07 周五

《Programming Rust》ch06

6 Expressions
    An Expression Language
    Precedence and Associativity
    Blocks and Semicolons
    Declarations
    if and match
    if let
    Loops
    Control Flow in Loops
    return Expressions
    Why Rust Has loop
    Function and Method Calls
    Fields and Elements
    Reference Operators
    Arithmetic, Bitwise, Comparison, and Logical Operators

#### Day5 2023-04-06 周四

未学

#### Day4 2023-04-05 周三 清明节

复习Rust，完成《Programming Rust》[ch03](https://github.com/MeouSker77/ProgrammingRust/blob/main/md/ch03.md)、[ch04](https://github.com/MeouSker77/ProgrammingRust/blob/main/md/ch04.md)、[ch05](https://github.com/MeouSker77/ProgrammingRust/blob/main/md/ch05.md)

结合[生命周期确保引用有效 - Rust 程序设计语言](https://kaisery.github.io/trpl-zh-cn/ch10-03-lifetime-syntax.html)，这次真的理解了生命周期参数还有reference到底是怎么一回事。

3 Fundamental Types
Arrays, Vectors, and Slices
    Arrays
    Vectors
    Slices
String Types
    String Literals
    Byte Strings
    Strings in Memory
    String
    Using Strings
    Other String-Like Types
Type Aliases
Beyond the Basics

4 Ownership and Moves
Ownership
Moves
    More Operations That Move
    Moves and Control Flow
    Moves and Indexed Content
Copy Types: The Exception to Moves
Rc and Arc: Shared Ownership

5 References
References to Values
Working with References
    Rust References Versus C++ References
    Assigning References
    References to References
    Comparing References
    References Are Never Null
    Borrowing References to Arbitrary Expressions
    References to Slices and Trait Objects
Reference Safety
    Borrowing a Local Variable
    Receiving References as Function Arguments
    Passing References to Functions
    Returning References
    Structs Containing References
    Distinct Lifetime Parameters
    Omitting Lifetime Parameters
Sharing Versus Mutation
Taking Arms Against a Sea of Objects

#### Day3 2023-04-04 周二

复习Rust，完成《Programming Rust》ch3，看到指针

3 Fundamental Types
Fixed-Width Numeric Types
    Integer Types
    Checked, Wrapping, Saturating, and Overflowing Arithmetic
Floating-Point Types
The bool Type
Characters
Tuples
Pointer Types
    References
    Boxes
    Raw Pointers

#### Day2 2023-04-03 周一

复习Rust，完成《Programming Rust》ch2，开始看ch3

Concurrency
    What the Mandelbrot Set Actually Is
    Parsing Pair Command-Line Arguments
    Mapping from Pixels to Complex Numbers
    Plotting the Set
    Writing Image Files
    A Concurrent Mandelbrot Program
    Running the Mandelbrot Plotter
    Safety Is Invisible
Filesystems and Command-Line Tools
    The Command-Line Interface
    Reading and Writing Files
    Find and Replace

#### Day1 2023-04-02 周日

[MeouSker77/ProgrammingRust: 本书为《Programming Rust - Fast, Safe Systems Development》第2版的个人中文翻译，仅供学习和交流使用，如有侵权请联系作者删除 (github.com)](https://github.com/MeouSker77/ProgrammingRust)

敲里面的代码，复习rust，到ch2，actix-web的例子
Preface
Who Should Read This Book
Why We Wrote This Book
Navigating This Book
Conventions Used in This Book
Using Code Examples
OâReilly Online Learning
How to Contact Us
Acknowledgments

1 Systems Programmers Can Have Nice Things
Rust Shoulders the Load for You
Parallel Programming Is Tamed
And Yet Rust Is Still Fast
Rust Makes Collaboration Easier

2 A Tour of Rust
rustup and Cargo
Rust Functions
Writing and Running Unit Tests
Handling Command-Line Arguments
Serving Pages to the Web
