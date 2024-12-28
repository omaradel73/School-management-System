# School-management-System
# Data Structures in C

This project implements fundamental data structures and utilities in C, providing a modular approach for managing and processing data efficiently. It includes a doubly linked list and basic string manipulation functionalities. The project is suitable for educational purposes or as a foundation for more complex applications.

## Features

- **Doubly Linked List**
  - Insert nodes at the beginning, end, or a specific position.
  - Delete nodes efficiently.
  - Traverse the list in both forward and backward directions.
- **String Manipulation**
  - Capitalization of strings.
  - Additional utilities for text processing.
- Well-structured code with separate files for implementation and declarations, following best practices in modular programming.

## Project Structure

```
data-structure-C-main/
├── bin/                        # Compiled binaries
├── captlize.c                  # String manipulation functionality
├── config.h                    # Configuration settings
├── doubly_linked_list.cbp      # Code::Blocks project file
├── doubly_linked_list.depend   # Build dependencies
├── doubly_linked_list.layout   # Code::Blocks layout file
├── list.c                      # List implementation
├── list.h                      # List declarations
├── main.c                      # Main entry point
├── obj/                        # Compiled object files
```

## Prerequisites

- A C compiler (e.g., GCC)
- Code::Blocks (optional, for project management)

## How to Build

1. Clone the repository:
   ```sh
   git clone <[repository_url](https://github.com/omaradel73/School-management-System)>
   cd data-structure-C-main
   ```

2. Compile the code:
   ```sh
   gcc -o bin/main main.c list.c captlize.c
   ```

3. Run the program:
   ```sh
   ./bin/main
   ```

## Usage

- The program demonstrates the usage of a doubly linked list and other utilities.
- Modify `main.c` to test specific functionalities.

## Contributing

Contributions are welcome! Please fork the repository, make changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- Inspired by classic data structure implementations.
- Special thanks to the open-source C community.

