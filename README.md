This code consists of a QRCode generator, let me break it down to you and tell you how to use it.
-Create any folder in your desktop (any name)
-Then open your teminal or window powershell , navigate to the folder, inside the folder (pip install qrcode) it'll pip install the python qrcode library.
-Then we open the folder we created with a code editor either vscode or Pycharm, Create a file inside the folder (any name) inside that folder the first thing we need to do 
is import qrcode.
import qrcode.
Define a variable (any name ) not that the variable we're defining is the data we're encoding behind the QRcode 
Sample = "https://facebook.com"

After that we create a qrcode instance like the one in my code we declare the version, error correction box size and border , but we would first create an object that'll hold the the following parameters 
i listed earlier .
- version is the size of the qrcode which was set to 1.
- error correction : it's like having a built-in process that helps the qrcode reader to still interpret the code correctly even if it's deformed .
_ There are four levels of error correction low , medium, high and quartile. when you indicate the error correction level during the creation of a qrcode , you're basically telling your library
how much redundancy to include in the code , more redundancy allows for better error correction but also increases the size of the qrcode . 
- box size : sets the size of each box in the qrcode image , larger values outcomes larger to larger qrcode.
- border : sets the width of the white border around the qrcode .

