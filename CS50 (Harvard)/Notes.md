````


````

## Week 0 Notes:

### Shorts

#### Algorithms
- Every algorithm involves a tradeoff

#### ASCII
- Common encoding scheme.
- The American Standard Code for Information Interchange
- 7 bits / 128 characters
- 95 characters, and 33 control characters
- Numbers are mapped to their corresponding binary code prefixed with 011
- For letters, the second to left character is 0 for uppercase and 1 for lowercase.
- Unicode was developed to cover more characters.


#### Binary
- Represented by 0 and 1


### Scratch
- Bottom left - sprites
- Middle - puzzle pieces
- Top left - Stage


### Problem Set 0
- How do you represent the (decimal) integer 50 in binary?
  - 110010
- How many bits must be "flipped" (i.e., changed from 0 to 1 or from 1 to 0) in order to capitalize a lowercase a that’s represented in ASCII?
  - 1, the second to left bit
- How do you represent the (decimal) integer 50 in, oh, "hexadecimal," otherwise known as "base-16"? Know that decimal is considered "base-10" (since it employs 10 digits, 0 through 9), and binary is considered "base-2" (since it employs 2 digits, 0 and 1). Infer from those base systems how to represent base-16! (We’ll see base-16 again in the context of graphics and web programming.)
  - 32

### My Scratch game:
- https://scratch.mit.edu/projects/113517844/
- You control a butterfly with the arrow keys. Try and collect as many tacos as possible while avoiding the bat!
- There are 3 sprites. The taco sprite is generated in a random location. When it touches the butterfly it moves to a random new location and adds 1 to the tacos variable. The bat sprite picks a random location on the screen and moves towards it for one second, than repeats. The butterfly has a number of scripts that are tied to key strokes, each arrow key either changes the x or the y position of the butterfly. When the butterfly touches the bat, it disappears.
- My game doesn't have an end game screen. I couldn't figure out how to change the background or display a message.


## Week 1 Notes:

### Lecture

#### Compiler:
- Source Code -> Compiler -> Object Code
- Compiler bash command:
  - clang -o hello hello.c
  - OR
  - make hello

#### Hello World

````c
int main(void)
{
  printf("hello, world\n" );
}

````

#### CS50 methods
- CS50 provides some useful c methods.
- #include <cs50.h>
- GetString()
- GetInt()
