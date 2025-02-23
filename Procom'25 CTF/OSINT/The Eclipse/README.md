**Challenge Title:** The Eclipse
**Category:** OSINT / Forensics
**Difficulty:** Easy
**Author:** Abdul Ghani

**Description:**
The path has already been revealed. You just need to remember where to look.
Flag Format: AxP25{}

Were you paying attention, or did you let it slip away?
---------------------------------------------------------------------------

**Write-Up:**

Challenge Analysis:
The challenge description suggested that the critical information had already been revealed. The phrase "let it slip away" hinted that the participants might have overlooked a previously shared detail.

**Approach:**
1. Initial Clue Gathering:

The first step was to revisit all communications, including emails, messages, and shared resources.
One specific email stood out—the Credentials Email sent to participants with their CTF platform login details.

2. Examining the Email:

The email included instructions on how to join the competition platform, along with the flag format (AxP25{flag}).
At first glance, this seemed like a standard flag format instruction, but the real flag was subtly hidden in plain sight.

3. Identifying the Flag:
   ![image](https://github.com/user-attachments/assets/b916b32f-3829-4cd9-82e8-858701a75d72)


The provided screenshot of the email (attached below) showcased the Flag Format: AxP25{flag} line.
The key to solving this challenge was to recognize that the flag was not meant to be generated but rather directly visible in the email.
The flag was cleverly embedded as AxP25{flag}, with "flag" being the literal placeholder for the final submission.

4. Submission:
AxP25{flag}

