# Assembly Language Playground 

**Explore the world of Assembly language within a Docker-powered environment!**

This repository provides a quick and easy setup for experimenting and developing with Assembly language, primarily for educational purposes. It's not intended for production environments.

## Prerequisites

- Docker installed and running on your machine (Windows, macOS, or Linux)

## Setup

1. Clone the repository:

   ```bash
   git clone [invalid URL removed]
   ```
2. Navigate to the project directory:
   ```bash
   cd assembly-language-setup
   ```
3. Build the Docker image:
   ```bash
   docker-compose build
   ```
4. Run the container:
   ```bash
   docker-compose run assembly-language-setup
    ```
## Checking The Environment
   ```bash
   gdb --version
   vim --version
   clang --version
   make --version
   nasm -v  # or nasm --version
   ```
## Usage
* Place your Assembly code files in the x86-playground/src directory on your host machine.
* They will be accessible within the container at /usr/src.
* Use the available tools (NASM, GCC, GDB, Vim) to create, compile, debug, and explore Assembly code.

## Acknowledgments
A huge shout-out to the incredible developers who paved the way for Assembly languages and shared their knowledge to make learning environments like this possible. Your contributions are invaluable!

## Feedback and Contributions
Feel free to use this repo for your Assembly language learning journey!

Share your feedback and suggestions for improvements.
Contribute to the project by suggesting changes or creating pull requests.

