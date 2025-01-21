Introduction Steganography is the art of hiding secret data within a non-secret medium, such as images, audio files, or videos, to ensure secure communication. This project demonstrates the use of steganography to embed a secret message within an image using Stegosuite, a graphical user interface (GUI) tool available on Kali Linux.
Objective The primary objective of this project is to hide a text message inside an image file using Stegosuite and retrieve the hidden message to demonstrate the principles of steganography.
Tools and Technologies Used
•	Operating System: Kali Linux
•	Tool: Stegosuite
•	Programming/Skills: Basic Linux command-line usage
•	Input Files: Image file (e.g., image.jpg), Text file with a secret message (e.g., message.txt)
skip these lines it become hard to co
y and paste
Methodology
1. Setting Up the Environment
1.	Open the terminal in Kali Linux.
2.	Install Stegosuite by executing the following command:
Sudo apt update
Sudo apt install stegosuite
3.	Verify the installation by typing stegosuite in the terminal. This command opens the Stegosuite GUI.
2. Preparing the Input Files
1.	Select an image file to act as the cover medium (e.g., image.jpg).
2.	Create a simple text file (e.g., message.txt) with the secret message:

3. Hiding the Secret Message
1.	Launch Stegosuite by entering stegosuite in the terminal.
2.	In the GUI:
o	Click on the Open File button and load the cover image (image.jpg).
o	Select the Embedded Message option and click Add File to load the message.txt file.
o	Set a password for additional security.
3.	Save the new steganographic image file (e.g., hidden_image.jpg) by clicking the Save button.
4. Extracting the Hidden Message
1.	Open Stegosuite and load the steganographic image (hidden_image.jpg) by clicking on the Open File button.
2.	Enter the password set during the embedding process.
3.	Extract the hidden message by selecting the Extract Message option.
Results
•	The text file containing the secret message (message.txt) was successfully embedded into the image file (image.jpg), creating the steganographic image (hidden_image.jpg).
•	The hidden message was extracted from the steganographic image using Stegosuite without any data loss or corruption.

•	Conclusion This project demonstrates the successful use of Stegosuite on Kali Linux for steganography. The process of embedding and extracting data through a graphical interface ensures ease of use and practical implementation. This method highlights the importance of steganography in secure communication and data protection.

Limitations and Future Work
1.	Limitations:
o	The size of the embedded data is limited by the capacity of the cover file.
o	Detection by advanced forensic tools remains a challenge.
2.	Future Work:
o	Explore the use of encryption for added security.
o	Test the approach with different file formats (e.g., audio, video).
o	Automate the process using scripts.
