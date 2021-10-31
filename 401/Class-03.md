# Readings: FileIO & Exceptions
## ***Read & Write Files in Python***
  a file is a contiguous set of bytes used to store data. This data is organized in a specific format and can be anything as simple as a text file or as complicated as a program executable. In the end, these byte files are then translated into binary 1 and 0 for easier processing by the computer.
  Files on most modern file systems are composed of three main parts:
  1. Header: metadata about the contents of the file (file name, size, type, and so on)
  2. Data: contents of the file as written by the creator or editor
  3. End of file (EOF): special character that indicates the end of the file

  File Paths:When you access a file on an operating system, a file path is required. The file path is a string that represents the location of a file. It’s broken up into three major parts:
  1. Folder Path: the file folder location on the file system where subsequent folders are separated by a forward slash / (Unix) or backslash \ (Windows)
  2. File Name: the actual name of the file
  3. Extension: the end of the file path pre-pended with a period (.) used to indicate the file type

  An encoding is a translation from byte data to human readable characters. This is typically done by assigning a numerical value to represent a character. The two most common encodings are the ASCII and UNICODE Formats.

  When you want to work with a file, the first thing to do is to open it.open() has a single required argument that is the path to the file. 
  There are two ways that you can use to ensure that a file is closed properly, even when encountering an error. The first way to close a file is to use the try-finally block and the second way to close a file is to use the with statement.

  A file object is:
  “an object exposing a file-oriented API (with methods such as read() or write()) to an underlying resource.”

  A raw file type is:
  “generally used as a low-level building-block for binary and text streams.”



## ***Exceptions in Python*** 
 Syntax errors occur when the parser detects an incorrect statement. 
 We can use raise to throw an exception if a condition occurs. The statement can be complemented with a custom exception.
 If you want to throw an error when a certain condition occurs using raise
 We assert that a certain condition is met. If this condition turns out to be True, then that is excellent! The program can continue. If the condition turns out to be False, you can have the program throw an AssertionError exception.
 ![try_except_else_finally](https://files.realpython.com/media/try_except_else_finally.a7fac6c36c55.png)

 * raise allows you to throw an exception at any time.
 * assert enables you to verify if a certain condition is met and throw an exception if it isn’t.
 * In the try clause, all statements are executed until an exception is encountered.
 * except is used to catch and handle the exception(s) that are encountered in the try clause.
 * else lets you code sections that should run only when no exceptions are encountered in the try clause.
 * finally enables you to execute sections of code that should always run, with or without any previously encountered exceptions.

## ***Read & Write Files in Python - Companion Video*** 

## ***Reading and Writing Files in Python Quiz***
