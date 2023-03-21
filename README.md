<!--
author:   o0Ikami0o

comment:  Test für C-Code

language: de

narrator: Deutsch Female

mode:     Textbook

import: https://raw.githubusercontent.com/liascript/CodeRunner/master/README.md

@run: @LIA.eval(`["main.c"]`, `gcc -Wall main.c -o a.out`, `./a.out`)

-->

# C

``` c
#include <stdio.h>
#include <stdlib.h>

int main()
{
  printf("Es funktioniert\n");
}
```
@run
