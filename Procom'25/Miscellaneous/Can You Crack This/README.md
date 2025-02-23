**Challenge Title:** Can You Crack This?

**Category:** Steganography

**Difficulty:** Medium

**Author:** Abdul Ghani

**Description:**
Here’s a simple math problem for you. Solve it and find the answer! 🤔
![pic](https://github.com/user-attachments/assets/ff4603a9-d136-4043-b95c-6f984fba0dc1)

-------------------------------------------------------------------------
**Write-Up:**

Challenge Analysis:
The initial glance at "pic.jpg" misleads participants into believing this is a math problem. However, the real challenge is a Steganography puzzle where the flag is concealed within the image file.

**Approach:**

1. Download the Image:
Start by downloading "pic.jpg" to the local system.

2. File Analysis:
Verify the file type and check for any hidden information using: file pic.jpg

![image](https://github.com/user-attachments/assets/5d10f143-3413-4917-8445-6548f1e0f0c1)

3. Extract Strings:
The strings command can help extract readable text, which may include hidden flags or encoded data: strings pic.jpg

![image](https://github.com/user-attachments/assets/4c07fe5f-3c4a-4351-bd36-f06c4a1a39ba)

During the output inspection, a base64-encoded string was found, resembling something like this:

![image](https://github.com/user-attachments/assets/8bc7aeab-60fc-4031-9c81-4dfaa7e25028)


4. Decode the Base64 String:
Use the base64 decoding tool to reveal the actual flag: 
![image](https://github.com/user-attachments/assets/3576fc03-e1c0-4202-9172-87feffcccd87)

