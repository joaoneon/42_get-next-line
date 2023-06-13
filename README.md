<h1 align="center">
  42_get-next-line
</h1> 
<p align="center">
  <img src="https://github.com/joaoneon/42_get-next-line/assets/6489188/10fd5b3a-a952-404e-947c-f47491a25b5e">
</p>
<h3 align="left">
  About the project:
  </h3>
    <p>
    The primary objective of the Get Next Line project is to develop a solution that enables the sequential reading of a text file, processing one line at a time.
      </p>
 <h3 align="left">
    Technology used:
  </h3>
   <table>
       <td align="center">
            <img src="https://skillicons.dev/icons?i=c" width="65px" alt="C icon" /><br>
            <sub>
                <b>
                    <pre>C language</pre>
                </b>
            </sub>
        </td>
  </table>
    <h3 align=>
  Mandatory Part  
</h3>
  <p align="left">
Implement a function that reads and processes one line at a time from an opened file.
  </p>
<table align>
  <tr>
    <td>File</td>
    <td>Description</td>
  </tr>
  <tr>
    <td><a href="https://github.com/joaoneon/42_get-next-line/blob/main/get_next_line.c">get_next_line.c</td>
    <td>Function that reads the file, extracts and returns the current line</td>
  </tr>
   <tr>
    <td><a href="https://github.com/joaoneon/42_get-next-line/blob/main/get_next_line_utils.c">get_next_line_utils.c</td>
    <td>Auxiliary functions from the libft library</td>
  </tr>
   <tr>
    <td><a href="https://github.com/joaoneon/42_get-next-line/blob/main/get_next_line.h">get_next_line.h</td>
    <td>Header file</td>
  </tr>
  </table>
  
  
   <h3 align="left">
  Bonus part 
</h3>
  <p align="left">
Implement a function that reads one line at a time from multiple files simultaneously.
  </p>
<table align>
  <tr>
    <td>File</td>
    <td>Description</td>
  </tr>
  <tr>
    <td><a href="https://github.com/joaoneon/42_get-next-line/blob/main/get_next_line_bonus.c">get_next_line.c</td>
    <td>Function that reads the file, extracts and returns the current line</td>
  </tr>
   <tr>
    <td><a href="https://github.com/joaoneon/42_get-next-line/blob/main/get_next_line_utils_bonus.c">get_next_line_utils.c</td>
    <td>Auxiliary functions from the libft library</td>
  </tr>
   <tr>
    <td><a href="https://github.com/joaoneon/42_get-next-line/blob/main/get_next_line_bonus.h">get_next_line.h</td>
    <td>Header file</td>
  </tr>
  </table>
  <br>
  <h3 align="left">
   Final score  
</h3>
<p align="left">
  <img src="https://github.com/joaoneon/42_get-next-line/assets/6489188/45582b9c-e1e5-444d-be4b-7fe30c6d5c3b">
</p>
  
<br>
  
  <h3 align="left">
  Instructions to use  
</h3>
<p>
  In order to utilize this project, you must initially clone the repository onto your local machine by employing a terminal:
  </p>
  <ul>
  <li>
  - $> git clone git@github.com:joaoneon/42_get-next-line.git [folder]
  </ul>
  </li>
  
  <p>
  Once you have successfully cloned the project to your local repository, compile the mandatory portion using the following command:
  </p>
  <ul>
  <li>
  - $> -cc -Wall -Wextra -Werror -D BUFFER_SIZE=n <files.c>
  </ul>
  </li>
   <p>
 Additionally, to compile the bonus part of the project, utilize the following command:
  </p>
  <ul>
  <li>
  - $> -cc -Wall -Wextra -Werror -D BUFFER_SIZE=n <files_bonus.c>
  </ul>
  </li>
    
 <p>
   Replace <b>'n'</b> with the desired number of bytes to be read into the buffer for the <b>read</b> function. Additionally, you will need a <b>main.c</b> file to open a file and a test file that needs to be read.
    </p>
  
 

