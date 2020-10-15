
**Ryan McGuiness**
# Date: August 26, 2019

**Office Hours:**
- 30 mins before class every class
- TA - athicha - TBD
- Graders

**Reminders**
- Text book - required
	- PL Progmatics - 4ed - any ed is fine tho 
	- "The Rust programming languages"
## Course Languages
**Midterm:**
1. Rust - systems language, new gen lang.
1. Clojure - uses S expretions, list
1. Haskell - lambda calculus, function language

**Final:**

4. prolog - logic language
1. mech - 

why do we not have one be all end all language?
- used as means of communication. Teams, students, teacher, users, others. Provides certain langues to attend to a persons needs. 

## Course Take-Aways 
**Important topics we will constantly revist**
- Design space of PL
- Design and implementation of PL
- Programming Competency 

# Date: August 28, 2019
## Objectives/Reminders:
- Install Rust 
- Review syllabus

# Rust
* Fimilair wit C/C++
* Lil diff from java
* Systems language
## Web page Analysis
- Performance - Very fast and memory efficient. No run time or garbage collector. 
- Reliable - rich tyoe system and ownership model gaurentee memory-saftey and thread-safety -- and enable you to eliminate many classes of bugs.
- Productive - Great documentation, friendly compiler w/ useful error messages

**Used For:**
- Webassembly
- networking 
- Embedding 

## Who, When, Why :
- Created by Graydon Hoare (Mozilla)
- Invented in 2006
- Built to make a language that is safe and efficient. So that we can make webpages more interactive and keep the same speed as static webpages. 
-  Used rust to create a webBrowser called **Servo**. 
- However it has evolved since then is more inclusive now. 
- **Redox** -  operating system that runs on Rust. 

**Main function in rust:**
```
fn main(){
	println!("Hello World!");
}
```
- macro- code that generates code
	- ! - is a macro, anything that ends in '!' generates more code.

```
fn add_two(x:u32, y:u32)-> u32{
	x+y
}
```
- Only use a return statement if you want to return or exit code early. The function returns the first statement that omitts a ';'. 

**Unsigned Bits**
- u8, u16, u32, u64

**Signed Bits**
- i8, i16, i32, i64

**Float bits**
- f8,f16,f32
# Date: August 30,2019
## Objectives and Reminders
- Readn Rust chapters 1-4. Especially 4
- Assignment due next Firday. Must be done through git hub.

Youtube
-
-Basics of Berkeley LOGO video. 
