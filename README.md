# Command Line Interpreter (CLI)

## Description

This project is a custom Command Line Interpreter (CLI) built using C++. It is designed to interpret and execute user commands from the terminal.

## Features

The CLI supports the following commands:

* `quit`: Exit the CLI
* `remove <file_name>`: Removes the specified file
* `rename <old_name> <new_name>`: Renames the specified file or folder
* `rmdir <directory_name>`: Removes the specified directory (assumes the directory is empty)
* `echo "<data>" <optional_file_name>`: Writes the specified data to the specified file, or prints it on the screen if no file is specified
* `out -l <file_name_1> <file_name_2> <file_name_3>`: Prints the contents of the specified files one by one on the screen, asking the user to press a key to continue after each file (or each line if `-l` is specified)
* `zip <destination> <file_name>`: Zips the specified file or folder
* `unzip <file_name>`: Unzips the specified zipped file

## Installation

To install and run this CLI, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/yourrepository.git
    ```

2. Navigate to the `src` directory:
    ```bash
    cd yourrepository/src
    ```

3. Compile the C++ code:
    ```bash
    g++ -o cli.out cli.cpp
    ```

4. Run the CLI:
    ```bash
    ./cli.out
    ```

## Contributing

Contributions are welcome! Please read the [contributing guidelines](link-to-your-contributing-guidelines) first.

## License

This project is licensed under the terms of the [MIT License](link-to-your-license).

## Contact

If you have any questions, feel free to reach out to me at your-email@example.com.