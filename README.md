See caesar_cipher.md for assignment instructions.
Qingxi Zhao   Feb 19th 2020
This code is using commmand line input  (CLI) instead of instead of interactive user input for Caesar ciper. Caesar ciper is used for encrypt and decrypt the text. Firstly, users can choose different mode and shift value in the system. And they also can choose the if they wanna write a file or read a file or not. I made some changes. 1. Previously, the code only can read uppercase, but now it can read uppercase and lowercase. 2. Since  commmand line input do not need interaction, I delete for loop in get_cipher_mode and get_shift_value functions. 3. If the parameter of CLI is less than 3, there will be a error message.
How to use the code and examples of output:
Open the Terminal, find the file, and type "python" +"caesar_cipher.py"+ "e/d"+"shift number"+ "text"
Example 1: d 3 with me        output :"tfqe jb"
Example 2: d 8 Hello World       output :"Zwddg Ogjdv“
