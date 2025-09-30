# Detecting-steganography-with-tools-like-StegExpose-analyzing-file-signatures
## AIM:
To detect hidden data using steganography detection tools like StegExpose and analyze file signatures for authenticity and manipulation.

## DESIGN STEPS:
### Step 1:
Install StegExpose or use the JAR version to detect steganography in image files.

### Step 2:
Run StegExpose on a directory of suspected image files using the command:

### Step 3:
Analyze file signatures using tools like file, binwalk, or xxd to check for inconsistencies or embedded content.

## PROCEDURE:
StegExpose and File Signature Analysis Commands

# Step 1: Download Image and Create Secret Message File
• Download a .jpeg image  from a trusted website or use own image.

<img width="1485" height="800" alt="image" src="https://github.com/user-attachments/assets/b9fa2795-dccc-4755-8519-786155ea7d02" />


• Create a text file named secret with a confidential message:

<img width="855" height="780" alt="step 2" src="https://github.com/user-attachments/assets/b6b7abf0-3880-4928-9f50-af1cc47ca283" />


# Step 2: Install and Verify Steghide Tool
• To install Steghide on Kali linux,run:

• Confirm the installation by checking its version:

<img width="982" height="257" alt="step 3" src="https://github.com/user-attachments/assets/06d83386-b516-4e72-8a85-f8e10575aeb7" />


# Step 3: Embed the Secret Message into the Image
• Use the following command to embed secret into praveen.jpeg:

<img width="1920" height="910" alt="step5" src="https://github.com/user-attachments/assets/ff3de168-c60a-40ca-8900-0e2003ff7a1b" />


# Step 4: Delete the Original Secret File
• After embedding, delete the plaintext file:
<img width="950" height="651" alt="step 7" src="https://github.com/user-attachments/assets/49b46ef8-ab3a-46c9-84d7-406244257f57" />





## OUTPUT:
List of Images with Steganography Detection Scores and File Signature Details

# Step 1: Extract the Embedded Secret from the Image

<img width="1472" height="716" alt="image" src="https://github.com/user-attachments/assets/1bbc30a1-7805-45dc-91bc-77e4368df446" />


• To retrieve the hidden file: • Enter the same passphrase used during embedding.
<img width="1920" height="923" alt="step9" src="https://github.com/user-attachments/assets/3af13579-4db6-486a-b78d-8368118ee90d" />



# Step 2: Verify the Extracted Message
• Display the extracted file content to verify:

• Ensure the message matches the original secret content.

• Another command to see the same secret message is

# Step 3: Retrieve Information About the Embedded Data
• To gather details about embedded content in the image:

![image](https://github.com/user-attachments/assets/9a499ab3-50fd-4a9d-a08f-5a01eca456b8)

• This will display file type, size, and whether data is embedded.
## RESULT:
Hidden data was successfully detected and file signatures were analyzed for irregularities.
