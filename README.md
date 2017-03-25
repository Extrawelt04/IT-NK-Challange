# IT-NK-Challange

This is the challange project for our IT-NK's.  
The task will be to write an en-/decrypt cli (Command Line Interface).

## The journey:

### Step 1:
Use this [Java AES cipher](http://blog.axxg.de/java-aes-verschluesselung-mit-beispiel/)  to implement a simple encrypt / decrypt cli.  
The usage should be this (on the prompt): java -jar "app-name" "method" "String-to-process"  

- "app-name" is the name of the developed application
- "method" can be:
  - "encrypt" for encrypting the given string
  - "decrypt" for decrypting the given string
- "String-to-process" is the string which will be either encrypted or decrypted

### Step 2:
If not done already: Make it bulletproof.
Means, extend it with validation and exception handling. Also you can add a help parameter to the cli which shows how to use it.

### Step 3:
Now implement the [Caesar cipher](https://en.wikipedia.org/wiki/Caesar_cipher) 
But do me a favor: Try to implement it from scratch without cheating. Your experience will be much better...

### Step 4:
Change the crypt method to "caesar" but don't remove the old code! We will need it in stap 5...

### Step 5:
Now: Extend the cli by an additional parameter where you can choose between "caesar" and "AES".

### Step 6:
You will have lot of redundant code. Use this to avoid it:

- Inheritance
- Pattern:
  - Interface
  - Factory

### Step 7:
not yet defined... :)

Perhaps:  
- Read a file -> encrypt the content -> write ecrypted content to file
- Refactor to Spring-Boot-App and provide an UI for encrypting and decrypting text and / or files
- ...

## Additional Information

Ensure that you have tested your code. Means: write JUnit tests.
Al least at the end of:

- Step 2
- Step 4
- Step 6