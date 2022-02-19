[comment]: # (This presentation was made with markdown-slides)
[comment]: # (This is a CommonMark compliant comment. It will not be included in the presentation.)
[comment]: # (Compile this presentation with the command below)
[comment]: # (mdslides presentation.md --include media)

[comment]: # (Set the theme:)
[comment]: # (THEME = white)
[comment]: # (CODE_THEME = base16/zenburn)
[comment]: # (The list of themes is at https://revealjs.com/themes/)
[comment]: # (The list of code themes is at https://highlightjs.org/)

[comment]: # "You can also use quotes instead of parenthesis"
[comment]: # "THEME = white"

[comment]: # (Pass optional settings to reveal.js:)
[comment]: # (controls: true)
[comment]: # (keyboard: true)
[comment]: # (markdown: { smartypants: true })
[comment]: # (hash: false)
[comment]: # (respondToHashChanges: false)
[comment]: # (Other settings are documented at https://revealjs.com/config/)

Rust | @acary | February 19, 2022

# Rust

Study topics

[comment]: # (!!!)

# Chapter 1

[comment]: # (!!!)

# Topic 1

[comment]: # (!!!)

# Primitives

## Scalar Types
- `signed integers`: `i8, i16, i32, i64, i128 and isize (pointer size)`
- `unsigned integers`: `u8, u16, u32, u64, u128 and usize (pointer size)`
- `floating point`: `f32, f64`

[comment]: # (!!!)

## Scalar Types
- `char` Unicode scalar values like `'a', 'α' and '∞' (4 bytes each)`
- `bool` either `true or false`
- and the unit type `()`, whose only possible value is an empty tuple: `()`

[comment]: # (!!!)

# Compound Types

- arrays like `[1, 2, 3]`
- tuples like `(1, true)`

[comment]: # (!!!)

# Traits

- Class:
  - `trait Show {`
    - `...`
    - `(like Java or Go interfaces)`
  - `}`

[comment]: # (!!!)

#

- Main method:
  - `fn main() {`
    - `println!("Hello, World!");`
  - `}`

[comment]: # (!!!)

# Topic 2

[comment]: # (!!!)

#

- Assignment:
  - (variable) `=` (value or expression)
- Operators:
  - Equality: `==, !=`
  - Conditional: `&&, ||`

[comment]: # (!!!)

# Topic 3

[comment]: # (!!!)

#

- Expression:
  - evaluates to a single value

[comment]: # (!!!)

#

- Operators:
  - `=, +=, -=, *=, %=`
- Arithmetic:
  - `+, -, *, %, ==`
- Auto-Increment:
  - `++/--`

[comment]: # (!!!)

#

- Control flow:
  - `for i in 0..5 {`
    - `println!("Hello {}", i);`
  - `}`


[comment]: # (!!!)

# Boolean

- `bool`: implements traits
  - `let my_variable = true;`

[comment]: # (!!!)

# Match

- Switch:
  - `match my_variable {`
    - `true => println!("It is true!"),`
    - `false => println!("Evaluated as false"),`
  - `}`

[comment]: # (!!!)

#

- Break:
  - `break` escapes loop
- Continue:
  - `continue` passes control to next iteration

[comment]: # (!!!)

# Appendices

[comment]: # (!!!)

# Shortcuts

[comment]: # (!!!)
