---
title: 'C++ Journey Chapter 1'
date: 2019-11-16
permalink: /CppJourney/Chapter-1/
type: "portfolio"
collection: portfolio  
author_profile: true
---

Coding is an art.
It must be cultivated over time.
It requires dedication, passion, discipline.
However, it is highly rewarding.
The joy of seeing your piece od code actually running... Is overwhelming.

The standard procedure is to start with the infamous **HELLO WORLD** program.

```javascript
#include <iostream>
using namespace std;

//_____________________________
void HelloWorld(){
  cout << "Hello World" << endl;
}
//_____________________________
int main(){
  HelloWorld();
}
```

Simply write this piece of code into a file in the `Desktop` by the name `HelloWorld.cpp` and you are good to go!
Now comes a bit of magic.
Open a `terminal` and go to the `Desktop` by typing:

```
cd Desktop
```
Press `enter` and you should arrive at the `Desktop`.
At this point you should type:
```
g++ HelloWorld.cpp
./a.out
```
Magic will happen and you should see the comforting printout:
```
Hello World
```
Congratulations! This is your (as it was mine) first code...

We still do not know what each word in the code means.
This will appear in the latter pages of this documentation.

The next post should be about making our life easier with coding, before delving further...
Enjoy this moment of glory, as coding is actually often painful instead... Sigh.
