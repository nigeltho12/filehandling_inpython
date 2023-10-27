<h1> Update a File Through a Python Algorithm </h1>



<h2>Description</h2>
<p> This project involves tasks related to text file management in Python. It covers importing, reading, writing, and manipulating text files, as well as creating and documenting a list of allowed IP addresses. The project showcases the use of Python functions and the importance of efficient file handling with the with statement. </p>


<br />


<h2>Objective</h2>

- <b> Demonstrate proficiency in importing, reading, and manipulating text files using Python, including splitting log files into manageable data. </b> 
- <b> Create and document a text file containing a list of allowed IP addresses, emphasizing the use of the with statement and proper file handling techniques.</b>
<br> </br>



<h2>Program walk-through:</h2>

<p align="center">
<p> Imported a Security Log Text File

Used the Python with statement to open a log file for reading.
The filename stored in the variable import_file was utilized.
Began by writing the first line of the with statement using the open() function with the "r" parameter to open the file.</p> <br/>
<img src="https://i.imgur.com/YIRUW6f.png" height="80%" width="80%" />
<br />
<br />


<p> Read and Displayed the Imported File

Employed the .read() method to read the content of the imported file.
Stored the result in a variable named text.
Displayed the contents of the text variable to explore what was in the file. </p>  <br/>
<img src="https://i.imgur.com/GYDfEeR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<p>Split the Log File into a List of Strings

Utilized the .split() method to split the entire log file (stored in text) into a list of strings, with one string per line.</p> <br/>
<img src="https://i.imgur.com/gCB0S0J.png" height="80%" width="80%"/>
<br />
<br />
<p>Appended a Missing Entry to the Log File

Provided the missing entry stored in a variable named missing_entry.
Used the .write() method with the "a" parameter to append the missing entry to the log file.
Read the updated file back into the text variable using a with statement and displayed its contents.</p>  <br/>
<img src="https://i.imgur.com/0022JUH.png" height="80%" width="80%"/>
<br />
<br />
<p>Created a Text File for Allowed IP Addresses

Created a variable named import_file with the value "allow_list.txt" to specify the name of the new file.
Also given a variable named ip_addresses containing the allowed IP addresses</p>  <br/>
<img src="https://i.imgur.com/rkzWZEP.png" height="80%" width="80%"/>
<br />
<br />
<p> Wrote Allowed IP Addresses to a Text File

Created a with statement to open the file with the "w" parameter.
Wrote the IP addresses to the file.</p>  <br/>
<img src="https://i.imgur.com/GYjdj63.png" height="80%" width="80%"/>
<br />
<br />
<p>Read and Displayed the Allowed IP Addresses

Created a with statement to read the contents of the text file containing IP addresses.
The content was stored in a new variable named text.
Displayed the contents of the text variable to explore the result.</p>  <br/>
<img src="https://i.imgur.com/njR2fU1.png" height="80%" width="80%"/>
</p>

<br />
<br />


<h2>Review</h2>
<b>Python:</b> In conclusion, these tasks demonstrate how to import, read, write, and manipulate text files in Python. The with statement is used for efficient file handling, and the open() function with various parameters is employed to control the file's purpose (e.g., reading, appending, writing). Additionally, methods like .read(), .write(), and .split() are used for specific file operations.
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
