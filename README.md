<h2 align="center"><u>Bong Compiler</u></h2>

<h4 align="center">Welcome to Bong Compiler! This project is a simple compiler implemented in Rust that supports variable assignment, printing values, conditional statements (`if`), and loop statements (`while`). The commands are customized with Bengali terms for fun and educational purposes. </h4>

<p align="center">
<br>
</p>

## Features

- Variable assignment with the `chol` command.
- Print values with the `bol` command.
- Conditional statements with the `jodi` command.
- Loop statements with the `jotokhun` command.
- Exit the interpreter with the `gand mara` command.

  ## Installation

  To get started with the Bong Compiler, you need to have Rust installed. If you don't have Rust installed, you can install it from [rust-lang.org](https://www.rust-lang.org/).
  Clone the repository:

```sh
git clone https://github.com/Shounak2003/Bong-Campiler.git
cd Bong-Compiler
```


  ## Build the project

```sh

cargo build
```



  ## Run the project

```sh



cargo run

```

## Usage
Here are some example commands you can use in the interpreter:

## Variable Assignment
Assign a number to a variable:
```sh
> chol count = 1


```
Assign a string to a variable:
```sh
> chol name = "Shounak"

```

## Print Variable
Print the value of a variable:
```sh
> bol count

```

## Conditional Statement
Print a value if a condition is met:
```sh
> jodi count == 1 bol "Count is one"

```

## Loop Statement
Execute a block of commands while a condition is true:
```sh
> chol count = 1
> jotokhun count <= 5 obdhi
| bol count
| chol count = count + 1
|

```

## Exit Command
Exit the interpreter:
```sh
> gand mara

```

## Example Session
```sh
Welcome to the Rust Interpreter. Type your commands:
> chol count = 1
> jotokhun count <= 5 obdhi
| bol count
| chol count = count + 1
|
1
2
3
4
5
> gand mara

```

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request or open an issue to discuss what you would like to change.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
Special thanks to the Rust community and the creators of the dependencies used in this project.


