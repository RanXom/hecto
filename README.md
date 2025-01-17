# Hecto - A Rust CLI Text Editor

Hecto is a simple yet powerful CLI text editor inspired by VIM, built entirely in Rust. This project is a guided learning experience based on Philipp Flenker's tutorial series, with plans to expand its features and functionality that I may find missing. Through this project, my goal is to deepen my understanding of Rust and learn to write idiomatic Rust code by following a project-based learning approach.

## Features

Currently, Hecto supports:

- Displaying a clean editor interface with tildes (`~`) on empty lines.
- A welcome message at startup.
- Opening and displaying the content of `.txt` files.
- Character insertion and deletion (line changes via `Enter` and `Tab` are not supported yet).

Planned features include:

- Support for line changes (Enter and Tab).
- File saving.
- Syntax highlighting.
- Advanced navigation (jumping to specific lines, etc.).
- Search functionality.

## Getting Started

Follow these steps to clone and run Hecto on your local machine:

### Prerequisites

- [Rust](https://www.rust-lang.org/tools/install) (latest stable version recommended)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/RanXom/hecto.git
   cd hecto
   ```

2. Build the project:
   ```bash
   cargo build --release
   ```

3. Run the editor:
   ```bash
   cargo run
   ```

## Usage

- Open the editor by running the above command.
- Use arrow keys for navigation.
- Open `.txt` files to view their content, using the following command:
```bash
   cargo run [path/to/your/txt/file]
   ```
- Edit files with character insertion and deletion.
- Stay tuned for upcoming updates with more interactive features!

## Resources

This project has been developed using the following resources:

1. [Hecto: Build Your Own Text Editor in Rust](https://www.flenker.blog/hecto/)
2. [Rust Cheatsheet](https://cheats.rs/)
3. [Rust Design Patterns](https://rust-unofficial.github.io/patterns/intro.html)
4. [VT100 User Guide](https://vt100.net/docs/vt100-ug/chapter3.html)

## Contributing

Contributions are welcome! Feel free to fork the repository, create a branch, and submit a pull request for improvements or new features.

## Acknowledgments

This project is based on Philipp Flenker's guide to building a text editor in Rust. Special thanks to him for creating an excellent learning resource.

## License

This project is licensed under the [MIT License](LICENSE). Please note that this project is based on a public guide, and similar implementations may exist.