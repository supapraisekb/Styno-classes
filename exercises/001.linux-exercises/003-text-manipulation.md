# Exercise 3 From Chapter 2:

### 1. Navigate to /usr/share/wordlists/metasploit. This is a directory of multiple wordlists that can  be used to brute force passwords in various passwordprotected devices using Metasploit, the most popular entesting and hacking framework.

### Solution

```bash
cd /usr/share/wordlists/metasploit

```

![Metasploit directory](/assets/metasploint-directory.JPG)

### 2. Use the cat command to view the contents of the file passwords.lst.

### Solution: 

```bash
cat password.lst

```

![viewing the contents of the password.lst file with cat](/assets/password.lst-file-output.JPG)


### 3. Use the more command to display the file passwords.lst.

### Solution

```bash
more password.lst

```

![Out put of the password.lst file using more command](/assets/output_with_more_command.JPG)


### 4. Use the less command to view the file passwords.lst.

```bash
less password.lst

```

![Output of the password.lst file using the less command](/assets/less_output.JPG)


### 5. Now use the nl command to place line numbers on the passwords in passwords.lst. There should be 88,396 passwords.

### Solution

The Command for this is:

```bash

nl password.lst
 
 ```
Below is the screeenshot of the solution

![Numbered Password.lst file](/assets/numbered_password.lst)


### 6. Use the tail command to see the last 20 passwords in passwords.lst.

### Solution 

```bash

tail -20 password.lst

```

Below is the screenshot:

![Last 20 commands of the password.lst file using tail command](/assets/last_20_commands_using_tail_command.JPG)


### 7. Use the cat command to display passwords.lst and pipe it to find all the passwords that contain 123.


### Solution 

```bash
cat password.lst | grep 123 | wc -l

```
It returns 30 passwords



The screenshot of the solutions is as follows:



![List of passwords containing 123](/assets/passwords_with_123.JPG)



