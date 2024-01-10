# ✅ libft with a 125% mark :) 

## Hey There! 👋🏽
Welcome to `libft`! This is your first step as a student at 42. It's all about diving into C programming by redoing some of the classic C standard library functions, plus a few extra utility functions. Think of it as your DIY toolkit for coding at 42.

## What's the Goal?
The idea is simple yet challenging: rebuild those key C library functions from scratch. Why? To get you super comfortable with C and give you a bunch of tools you'll use throughout your coding journey at 42.

## Before You Start
You'll need to be buddies with C programming for this. If you've got loops, functions, and data types down, you're good to go!

## Setting Up
Ready to roll? Great! Grab the code from GitHub:
```bash
git clone https://github.com/daanmlab/libft.git
```
Jump into the libft folder and hit `make` to get your library ready:
```bash
make
```
Boom! You've got your `libft.a` ready to be used in your projects.

## What's Inside?
Inside `libft`, you'll find a bunch of recreated functions like:
- `ft_strlen` (to get the length of a string)
- `ft_strdup` (to duplicate a string)
- `ft_memcpy` (for copying memory)
- ...and loads more (check the repo!)

## Try It Out!
Here's how you can use these tools:
```c
#include "libft.h"

int main() {
    char *greeting = "Hello, world!";
    int length = ft_strlen(greeting);
    printf("Length: %d\n", length);
    return 0;
}
```
