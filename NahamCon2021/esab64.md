# esab64
## Points: 50
#### Description:
##### Was it a car or a cat I saw? 
<br>
After running cat on the file I was presented with a random string of characters<br>

###### root@kali$:cat esab64
mxWYntnZiVjMxEjY0kDOhZWZ4cjYxIGZwQmY2ATMxEzNlFjNl13X <br>
<br>
I took the string and reversed them using python
<br>
<img width="545" alt="python" src="https://user-images.githubusercontent.com/75152185/111223363-0bdf0880-85ab-11eb-9ce8-19946cb9c14a.png">
<br>
I then took the new string and did a base64 decode on it<br>
<br>
<img width="692" alt="decode" src="https://user-images.githubusercontent.com/75152185/111223558-4d6fb380-85ab-11eb-9bd0-de6666f42a6e.png">
<br>
Almost there...One last reverse in python and we get our flag<br>
<br>
<img width="448" alt="flag" src="https://user-images.githubusercontent.com/75152185/111223736-8f98f500-85ab-11eb-804f-548f828d53a9.png">
<br>
Flag: flag{fb5211b498afe87b1bd0db601117e16e}
