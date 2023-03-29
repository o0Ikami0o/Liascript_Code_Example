<!--
author:   o0Ikami0o

comment:  Test für C-Code

language: de

narrator: Deutsch Female

mode:     Textbook

import: https://raw.githubusercontent.com/liascript/CodeRunner/master/README.md

-->

### `@LIA.java`: Java

``` java
import java.io.*;
class Demo {
public static void main(String args[])
throws IOException
{
  // create a BufferedReader using System.in
  BufferedReader obj = new BufferedReader(new InputStreamReader(System.in));
   String str;

 System.out.println("Enter lines of text.");
 System.out.println("Enter 'stop' to quit.");
   do {

    str = obj.readLine();
    System.err.println(str);
  }   while(!str.equals("stop"));
}
}
```
@LIA.eval(`["Demo.java"]`, `javac Demo.java`, `java Demo`)
