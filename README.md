# Hello-C
***************This program is Written in C Language***************

C is a general-purpose programming language used for wide range of applications from Operating systems like Windows and iOS to software that is used for creating 3D movies.
As mentioned, it’s a good language to start learning programming. If you know C programming, you will not just understand how your program works, but will also be able to create a mental picture on how a computer works.

---------------------DESCRIPTION-------------------------

Include stdio.h header file in your program.

C programming is small and cannot do much by itself. You need to use libraries that are necessary to run the program. The stdio.h is a header file and C compiler knows the location of that file. To use the file, you need to include it in your program using #include preprocessor.

Why do you need stdio.h file in this program?

In this program, we have used printf() function which displays the text inside the quotation mark. Since printf() is defined in stdio.h, you need to include stdio.h.

The main() function

In C programming, the code execution begins from the start of main() function (doesn’t matter if main() isn’t located at the beginning).

The code inside the curly braces { } is the body of main() function. The main() function is mandatory in every C program.

int main() {
}


This program doesn’t do anything but, it’s a valid C program.

The printf() function

The printf() is a library function that sends formatted output to the screen (displays the string inside the quotation mark). Notice the semicolon at the end of the statement.

In our program, it displays Hello, World! on the screen.

Remember, you need to include stdio.h file in your program for this to work.

The return statement

The return statement return 0; inside the main() function ends the program. This statement isn’t mandatory. However, it’s considered good programming practice to use it.
