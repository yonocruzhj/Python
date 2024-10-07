<h1>Python: Updating Files</h1>

<h2>Description</h2>
For this project, I was tasked to create an algorithm to automate updating a file called "allow_list.txt" and remove IP addresses that should not have access to the contents of the file. The repository provides examples for various file operations, such as reading and writing to files and updating file permissions.


<br />

<h2>Languages and Utilities Used</h2>

- <b>Python</b> 

<h2>Environments Used </h2>

- <b>Linux</b>

<h2>Script:</h2>

Open file that has the allow list: <br/>
<img src="https://imgur.com/0cjeDlW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/LCVtino.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Reading the file: <br/>
<img src="https://imgur.com/cFFU2XH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Convert string into a list: <br/>
<img src="https://imgur.com/GP0ElrI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Removal of IP addresses that are on the remove list: <br/>
<img src="https://imgur.com/aePWHMj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Update file using revised list of IP addresses:  <br/>
<img src="https://imgur.com/3DPxl7Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/cXn1upH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<h2>Summary</h2>
The algorithm I built filtered out IP addresses found in the remove_list variable from the "allow_list.txt" file. I started by opening the file, reading its contents as a string, and converting it to a list of IP addresses stored in the ip_addresses variable. As I looped through each entry in remove_list, I checked for its presence in the ip_addresses list. If the entry was found, it was removed using the .remove() function. Once all removals were completed, I transformed ip_addresses back into a string using .join() and updated the "allow_list.txt" file with the newly revised data.
