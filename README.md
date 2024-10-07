<h1>Python: Updating Files</h1>

<h2>Description</h2>
For this project, I was tasked to create an algorithm to automate updating a file called "allow_list.txt" and remove IP addresses that should not have access to the contents of the file. The repository provides examples for various file operations, such as reading and writing to files and updating file permissions.


<br />

<h2>Languages and Utilities Used</h2>

- <b>Python</b> 

<h2>Environments Used </h2>

- <b>Linux</b>

<h2>Algorithm walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>Summary</h2>
The algorithm I built filtered out IP addresses found in the remove_list variable from the "allow_list.txt" file. I started by opening the file, reading its contents as a string, and converting it to a list of IP addresses stored in the ip_addresses variable. As I looped through each entry in remove_list, I checked for its presence in the ip_addresses list. If the entry was found, it was removed using the .remove() function. Once all removals were completed, I transformed ip_addresses back into a string using .join() and updated the "allow_list.txt" file with the newly revised data.
