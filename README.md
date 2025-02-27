# silver-journey
**Algorithm for File Updates in Python**

Project Description

This project implements an algorithm to update a file containing a list of IP addresses with access to restricted information. The algorithm removes IP addresses that match those on a specified removal list, ensuring that only authorized IPs remain.

Features
	•	Reads an allowlist of IP addresses from a file.
	•	Converts the file content into a list for easy manipulation.
	•	Iterates through a removal list to identify and remove unauthorized IPs.
	•	Updates the file with the revised list of IP addresses.

How It Works
	1.	Open the file containing the allowlist.
	2.	Read the file contents.
	3.	Convert the string of IPs into a list.
	4.	Iterate through the removal list and remove matching IPs.
	5.	Update the file with the revised list.

Implementation Details
	•	Uses Python’s with open() function to read and write files.
	•	Utilizes .split() to convert the string of IPs into a list.
	•	Iterates through the list using a for loop and if statements to remove matching entries.
	•	Writes the updated list back to the file using .join().

Dependencies
	•	Python 3.x

Usage
	1.	Ensure the allowlist file and removal list are available.
	2.	Run the script.
	3.	The updated allowlist will be saved with unauthorized IPs removed.
