**Challenge Title:** Corporate Veil
**Category:** OSINT 
**Difficulty:** Medium
Author: Abdul Ghani

**Description:**
The email appears to be from someone at Blackstone, discussing legal reviews and regulatory compliance for an important transaction. It mentions external counsel coordination and emphasizes accuracy. Based on this, what is this challenge asking us to identify?

**Hint:**
Look for the key player handling compliance and legal reviews at Blackstone. Their role ensures accuracy in transactions—find the name behind the responsibility, a small separator can make all the difference.

**Write-Up:**
Challenge Analysis:
The challenge provided an email that seemed to originate from a professional at Blackstone, focusing on legal reviews and compliance aspects of a transaction. The key was to identify the individual responsible for these tasks, with a specific emphasis on the use of a "separator."

**Approach:**

1. Email Analysis:
The email content pointed towards a compliance and legal expert at Blackstone. The information seemed legitimate, but the real clue lay in interpreting the "separator" hint.

2. Research:
A quick search on Blackstone’s official website and LinkedIn profiles helped identify John G. Finley, who is Blackstone’s Chief Legal Officer. His role directly aligns with handling compliance and legal reviews for major transactions.

3. Understanding the Separator:
The hint mentioned that "a small separator can make all the difference." The name John G. Finley usually appears with a space between John and G, but the flag format required using an underscore (_) instead of a space.

4.Flag Submission:
AxP25{John_G.Finley}

