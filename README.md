# Enhancing Data Security Using Cryptography,Steganography and file encryption
<p>It is  a Python based application with use of flask a microservice based
framework to demonstrate the combination of cryptography that is based on symmetric key and
steganography that is based on modified LSB which helps to provide security to confidential data over
an unsecured network.</p>

# Project Team Members :
<ul>
<li><b>ganesh pendyala (U21CS226) </b></li>
<li><b>hari shankar(U21CS221)</b></li>
<li><b>datta raj varma(U21CS220) </b></li>
<li><b>gaddam ganesh(U21CS211) </b></li>
</ul>

<br>


 

# METHODOLOGY : 
<div>
<p>
  The encrypted data is then embedded within a cover image using a modified least significant bit (LSB) steganography technique. This method alternates between LSB-1, LSB-2, and LSB-3, storing bits at different positions to enhance security. The resulting stego-image is transmitted over the network.

At the receiver’s end, the encrypted content is extracted from the stego-image, followed by decryption using the proposed algorithm. While inspired by prior research, we designed a custom encryption and decryption architecture to ensure robust data security, ultimately developing an application for secure transmission over untrusted channels.
</p>
</div>



# How To Run The Project :

Make Dirctory Crypto_Project : <br/>
`mkdir Crypstego_Project`

 <br/>
 
Move Inside the Directory:   <br/>
`cd Crypstego_Project`

 <br/>
 
 
Clone The Repo: <br/>
`git clone https://github.com/ganesh68788/Enhancing_data_security_Using_cryptography_steganography_file_encryption`


 <br/>
 
Move Inside The Clone Repo: <br/>
`cd Enhancing_data_security_Using_cryptography_steganography_file_encryption`


 <br/>
 
Install all Requirements: <br/>
`pip install -r requirements.txt` 

 <br/>
 
Run the web application: <br/>
`python3 app.py`

 <br/>
After that Copy the link http://127.0.0.1:5000/ and paste it on your Broswe and you are good to go .

 <br/>

# REFERENCES

[1] Marwa E. Saleh Abdel Magied A. Aly Fatma A. Omara. CSE from Minia University, ​ Data Security Using Cryptography and
Steganography Techniques . ​ International Journal of Advanced Computer Science and applications, 2016.

[2] Ms. Hemlata Sharma, Ms. MithleshArya, and Mr. Dinesh Goyal. Department of CSE ​ Secure Image Hiding Algorithm using
Cryptography and Steganography. 2013

[3] S. Wendzel, S. Zander, B. Fechner, and C. Herdin. "Double Layer Security Using Crypto-Stegano Techniques: A Comprehensive Study." Health and Technology, 2021.

[4] S. Sarmah. "Evaluating the Merits and Constraints of Cryptography-Steganography Integration." International Journal of Information Security, 2024.

[5] M. R. K. Krishna, V. R. Kumar, and N. R. Reddy. "A Secure Data Communication System Using Cryptography and Steganography." International Journal of Computer Networks & Communications (IJCNC), 2013.
