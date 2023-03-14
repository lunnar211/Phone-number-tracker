# Phone-number-tracker
The process of finding the location of a phone number involves using a database of phone numbers and their associated locations. There are various databases available online that you can use for this purpose, such as the one provided by OpenCNAM.

To implement this program, you can follow these steps:

Download the phone number location database and store it in a file on your computer.
Write a C program that prompts the user to input a phone number.
Open the database file and search for the phone number entered by the user.
If the phone number is found, retrieve the associated location information and display it to the user.
If the phone number is not found, display an error message.
This code opens the file "phone_numbers.txt" and reads each line until it finds a line that contains the user's phone number. If the phone number is found, it displays the location information. If the end of the file is reached without finding the phone number, it displays an error message. Note that this code assumes that the phone number database is stored in a text file with one phone number and location per line, separated by a comma. You may need to modify this code to fit your specific database format.
