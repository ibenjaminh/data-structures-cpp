# Whale Talk Translator

This project takes a string input and translates it into "whale talk," a playful rendition of the input where only the vowels are echoed, and certain vowels are elongated for effect.

## Features

- **Vowel Isolation**: Filters out all consonants to leave only the vowels in the output.
- **Elongation of Specific Vowels**: Doubles up on 'e' and 'u' to mimic the elongated sounds often associated with whale vocalizations.

## Technical Overview

The program demonstrates a variety of fundamental programming concepts and C++ specific skills:

### Utilization of Standard Libraries

- `#include <iostream>` for input/output stream operations.
- `#include <vector>` for using dynamic array structures.
- `#include <string>` for string manipulation.

### Core Concepts Showcased

- **Basic Data Structures**: Uses `std::vector<char>` for dynamically storing and manipulating sequences of characters.
- **String Manipulation**: Iterates through a `std::string` object, showcasing how to access and compare individual string characters.
- **Nested Loops**: Employs nested for-loops to compare each character in the input string against a list of vowels.
- **Conditional Logic**: Implements `if` statements to filter vowels and apply special rules for 'e' and 'u'.
- **Dynamic Collection Building**: Demonstrates adding elements to a vector using `push_back()`, illustrating how to build up collections based on runtime decisions.
- **Result Presentation**: Iterates over the constructed `whale_talk` vector to print the translation, showing how to output results to the console.

## Getting Started

To run this application, you need a C++ compiler like GCC, Clang, or MSVC. Follow these steps to compile and execute the program

Thank you,
Izaac
