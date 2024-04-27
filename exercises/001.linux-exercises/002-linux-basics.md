# Assignment on  Chapter 1 exercises on Linux Basics

### 1. Use the ls command from the root (/) directory to explore the directory structure of Linux. Move to each of the directories with the cd commandand run pwd to verify where you are in the directory structure.

### Solution

```bash
cd / && ls
```

The Screenshot below shows the directory structure of Linux using the ls command from root/ drectory

  1. ![The directory structure of linux](/assets/Directory_Structure_Linux.JPG)
  
  2. The Different Directories
  
  
   - Bin Dierectory 

   ```bash
   cd bin && pwd
   
   ```
   
   ![Navigating the bin directory](/assets/Navigating_to_the_bin_directory.JPG)

   - Dev Directory

   ```bash 

   cd dev && pwd

   ```

   ![Navigating the Dev Directory](/assets/Navigating_to_the_dev_directory.JPG)
 
    -  Home Directory

    ```bash

    cd home && pwd

    ```

![Navigating the Home Directory](/assets/navigating_to_the_home_directory.JPG)


![Navigating the mnt Directory](/assets/Navigating_to_the_mnt_directory.JPG)

 
 ### 2. Use the whoami command to verify which user you are logged in as.

### Solution:

``whoami``

The Screenshot Below shows  which user i am logged in as

![Verifying what use i am logged in as with the whoami command](/assets/whoami_command.JPG)

### 3. Use the locate command to find wordlists that can be used for password cracking 

### Solution


``locate wordlist``

The screenshot below shows the locate command used to search for wordlists

![ Locate command use to find wordlists](/assets/locate_command_for_wordlists.JPG)


### 4. Use the cat command to create a new file and then append to that file. Keep in mind that > redirects input to a file and >> appends to a file.

### Solution

The implementation of this solution is shown in the screenshot below

![Using the cat command with the redirect symbol](/assets/using_the%20_cat_command_using_redirect_symbol.JPG)


### 5. Create a new directory called hackerdirectory and create a new file in that directory named hackedfile. Now copy that file to your /root directory and rename it secretfile.

the implementatioon code for this solution is shown below

```bash
mkdir hackerdirectory

cd hackerdirectory && touch hackedfile

sudo cp hackedfile /root/secretfile

```

the screenshot for the implementation is shown below:




