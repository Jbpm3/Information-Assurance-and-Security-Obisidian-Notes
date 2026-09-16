**ls** - list files and directories in the current working directory

*ls* *[options]* *[directory]* 

![[ls.png]]

==-**lh** - human-readable size==

**pwd** - display the full path of the current directory

*pwd*

![[pwd.png]]

**mkdir** - create new directory or folder

*mkdir directory_name*
*mkdir GeeksforGeeks*

![[mkdir.png]]

**cd**  - change current directory

*cd directory_name*
*cd GeeksforGeeks*
![[cd.png]]

**rmdir** - delete empty directories

*rmdir directory_name*
*rmdir TestFolder*

![[rmdir.png]]

**cat** - display file contents and combine multiple files

*cat file_name*
*cat text.txt*
![[cat.png]]

**cp** - copy files or directories

*cp source destination*

*cp file1.txt file2.txt*

![[cp.png]]

**mv** - move or rename files and directories

*mv old_name new_name*

*mv old.txt new.txt*

![[mv.png]]

**rm** - delete files permanently

*rm file_name*
*rm demo.txt*

- **f**: Forces the removal of all files or directories.
- **i**: Prompts for confirmation before removing.
- **-I***:Prompts once before removing more than three files or when removing recursively.
- **`**-r**`**: Removes directories and their content recursively.
- **`**-d**`**: Removes empty directories.
- **`**-v**`**: Provides a verbose output.
- **`**--help**`**: Displays the help text.
- **`**--version**`**: Displays the command version.



![[rm.png]]

**uname** - display system information
	- shows operating system details
	- identifies the system

*uname [OPTIONS]*
*uname*
![[uname.png]]

**locate** - find files using a database

*locate file_name*
*locate demo.txt*
![[locate.png]]

**touch** - create empty files and updates file timestamps

*touch file_name*
*touch test.txt*
![[touch.png]]

**ln** - create links between files

*ln -s source link_name*

*ln -s file1.txt link1.txt*

![[ln.png]]

**clear** - clear terminal screen

*clear*

![[clear.png]]

**ps** - display running processes

*ps*

![[ps.png]]

**man** - display command manuals

*man command_name*

*man ls*

![[man 1.png]]

![[man 2.png]]

**grep** - search text patterns
	- finds specific strings
	- filters output

*grep "text" file_name* or *grep -n : "text" file_name*
*grep "Python" notes.txt*

![[grep.png]]

**echo** - display text in the terminal

*echo "text"*

*echo "Hello Linux"*

![[ech.png]]

*echo "Hello Word" > hello.txt* - writes the text 'Hello World' to the "hello.txt" file
 
**wget** - download files from the internet using URL

*wget url*
![[wget.png]]

**whoami** - display current user

*whoami*
![[whoami.png]]

**sort** - sort file contents

*sort file_name*
*sort test.txt*
![[sort.png]]

**cal** - display the calendar

*cal*
![[cal.png]]

**whereis** - locate command files

*whereis command_name*

*whereis ls*

![[whereis.png]]

**df** - display disk space usage

*df [options]*

*df -h*
![[df.png]]

**wc** - display number of lines, words, and bytes in the file

*wc [OPTION] file_name*

*wc -m test.txt*

-l = lines
-w = words
-c = bytes
-m = chars
-l = max-line-length

![[wc.png]]

**chmod** - change mode or change file access permissions

d = directory
r = read
w = write
x = execute

**date** - display current date and time

*date*

**which** - locate the exact executable file associated with a command

*which [options] command_name*

**head** - displays first 10 lines by default

*head -n 5* first 5 lines
*head -n 100* first 100 lines

**tail** - shows last 10 lines by default

*tail -n 20* last 20 lines
*tail -n +50* from line 50 to end
 
**env** - prints system environment variables

**find** - search file by name
	- filter by size or date
	- search by permissions or owner
	- batch processing on found files

  find /home -name -size

|Situation|Command to use|
|---|---|
|Don't know where files are|`find`|
|Want to find text inside files|`grep`|
|Want to process or aggregate data|`awk`|
