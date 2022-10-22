# Inspect-File-Content-and-Find-Files-Linux
Operating System – Lab 06
Inspect File Content and Find Files

1.	Create a directory FileContent in /home/[username]
•	Command: Mkdir FileContent



2.	Create two file1 & file2 files using cat command as:
    -	Cat > file1
    <p>
    Start of file 1
    This is first line of test file 1
    This is second line of test file 1
    End of file 1</p>
    -	Cat > file2
    <p>
    Start of file 2
    This is first line of test file 2
    This is second line of test file 2
    End of file 2
  </p>

3.	Write a command to view content of file1 and file2 using  cat command
  -	Command: cat File1.txt  cat File2.txt

4.	Write a command to view content of both files using single cat command
  -	Command: cat File1.txt File2.txt

5.	 Display content of file1 and file2 with line numbers
  -	Command: cat –n File1.txt 
    -    cat –n File2.txt

6.	Redirect standard output of a file1 into a new file named as “file3” with ‘>‘ (greater than) symbol. Careful, if file3 already exists, redirection will overwrite its content.

7.	Append content of file3 using >> operator.cat 	as
  -	Echo “New Line added to file 3” >> file3

8.	Cd ~ [change directory to home]

9.	Find path of file3 using find command?

10.	Find location of following utilities using which command
  -	ls
  -	mv
  -	cp
  -	which
