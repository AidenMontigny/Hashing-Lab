<h1> Hashing Lab </h1>

<h2>Description</h2>
The Hashing Lab explores the use of cryptographic hashing algorithms and their applications in data integrity and security. In this lab, hash functions such as MD5, SHA256, and SHA512 were performed on both Kali Linux and Windows virtual machines to demonstrate how these algorithms produce unique message digests. A key part of the lab involved analyzing the SHA-1 collision using the "Shattered" PDF files to emphasize the vulnerabilities of outdated hash algorithms.
<br />

<h2>Languages and Utilities Used</h2>

- <b> Bash </b>
- <b> PowerShell </b>

<h2>Environments Used </h2>

- <b> Kali Linux Virtual Machine </b>
- <b> Windows 10 Virtual Machine </b>

<h2>Project walk-through:</h2>
</p><p align="left">
The Kali Linux virtual machine successfully executed the `md5sum`, `sha256sum`, and  <br/> `sha512sum`commands, generating cryptographic hash values to verify file integrity across <br/> multiple hashing algorithms. <br/><br/>
  <img src="Screenshot 2025-04-30 173554.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
</p><p align="left">
The Windows virtual machine successfully generated cryptographic hash values using the  <br/>  MD5, SHA-256, and SHA-512 algorithms, validating data integrity through multiple hashing methods. <br/><br/>
  <img src="Screenshot 2025-04-30 173602.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
</p><p align="left">
The Shattered 1 and Shattered 2 PDF files were successfully downloaded, allowing for analysis of <br/> SHA-1 hash collisions. <br/><br/>
  <img src="Screenshot 2025-04-30 173608.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
</p><p align="left">
A SHA-1 hash collision was successfully demonstrated using the Shattered 1 and Shattered 2 PDF  <br/>  files,  highlighting the cryptographic vulnerability of the SHA-1 algorithm. <br/><br/>
  <img src="Screenshot 2025-04-30 173619.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>


 <h2>Write Up</h2>

<p><u> Symmetric and Asymmetric Encryption  </u></p>
<p> Symmetric encryption is the process of changing the form of any message to secure it from any unauthorized parties (GeeksforGeeks, 2024). That is done by using a singular key that encrypts the message, and the same key has to be utilized to access the message. Although symmetric encryption is ‘secure’, it is challenging to maintain the security as the key has to be shared with the recipient, creating a gray area. On the other hand, asymmetric encryption is based on a public and private key. The public key encrypts the message, and the private key decrypts it so that the user can access the message. Overall, asymmetric encryption is more secure than symmetric encryption, however, it is more complicated, therefore making it more time-consuming.
 </p>

<p><u> The Importance of Hashing/Message Digestion </u></p>
<p> Hashing or message digesting is a string of numbers that is generated utilizing a cryptographic hash (GeeksforGeeks, 2024). The message string is passed through a hash function, creating a unique value, acts as the digital fingerprint for the message. It is important because any message sent online could potentially be intercepted or altered; however, by using message digesting, we can ensure that the message has not been tampered with, adding security to online communication.
</p>

<p><u> How Collisions Affect Hashing </u></p>
<p> A collision is when a hashing algorithm produces the same hash value for two different sets of data. When a collision occurs it creates an imbalance in the security of the hashing algorithm and ultimately makes it easy for malicious attackers to input fraudulent data utilizing the collision hash (Freeman Law, 2024). This can lead to a wide variety of issues such as data corruption and unauthorized access. </p>

<p><u> The Differences between MD5, SHA256 and SHA512</u></p>
<p> MD5: This hashing algorithm produces a 128-bit hash value. MD5 is one of the fastest hashing algorithms, however, it is not very secure as it has a high probability of producing collisions (Tutorial Points, 2019).
 </p>
<p> SHA256: This hashing algorithm produces a 256-bit hash value. SHA256 is a lot more secure and has a lower collision probability, however, it is much slower than MD5.
 </p>
<p> SHA512: This hashing algorithm produces a 512-bit hash value. SHA512 is one of the most secure hashing algorithms; however, with the security it provides, it has to takes longer. It is uncommon for SHA512 to provide collisions. </p>

<p><u>The Purpose of Cryptography in PKI   </u></p>
<p> PKI is a system that aids in identifying people, and devices while also encrypting messages for secure communication (Logsign, 2019). Cryptography plays a vital role in PKI vt ensuring that data confidentiality, integrity, and authentication are all present. Some common uses for this are secure communication, digital signatures, and certificates.
 </p>

<p><u> Comparing Authentication, Authorization, and Nonrepudiation  </u></p>
<p> Authentication is the process of verifying the identity of users trying to access data. The simplest forms of authentication are passwords and two-factor authentication. Authorization is the process of confirming what data or resources a user is allowed to access and ensuring that they cannot access any other information. Lastly, nonrepudiation is the process of proving who accessed the data or who sent the data over. The simplest forms of this would be signatures, however, it could also be tracking their access to various data. Overall, all three of these components are crucial as they all aid with security and protect companies' data. </p>

<p><u> References </u></p>
<p>GeeksforGeeks. (2024a, May 15). What is message and message digest in cryptography?. GeeksforGeeks. https://www.geeksforgeeks.org/what-is-message-and-message-digest-in-cryptography/ </p>
<p>GeeksforGeeks. (2024b, May 31). Difference between symmetric and asymmetric key encryption. GeeksforGeeks. https://www.geeksforgeeks.org/difference-between-symmetric-and-asymmetric-key-encryption/</p>
<p>Hash collisions explained. Freeman Law. (2022, October 4). https://freemanlaw.com/hash-collisions-explained/</p>
<p>The role of cryptography and PKI. Logsign. (2019, November 4). https://www.logsign.com/blog/the-role-of-cryptography-and-pki/</p>
<pTutorial Points. (2019, August 21). Ethical Hacking #23: SHA256, SHA512, MD5. YouTube. https://www.youtube.com/watch?v=rdd74INW2dg&t=1s</p>
