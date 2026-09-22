# NETWORKWALKS-ZOE-B083-WK3-PM1-PASSWORD-CRACKING-WITH-JTR---NW-TOOLS

# Project Overview
Password cracking is a common way to get access to a system, whether it's a wireless network connection or an endpoint device. Password protection is one of the most essential lines of defense in protecting  systems. Therefore, it will be impossible to talk about gaining and maintaining access to systems (or hacking), without understanding common ways and basic tools with which password cracking is ethically and unethically performed.

# Project Objectives
1. Download and properly install John the Ripper and Johnny (It's GUI).
2. Make use of pdf hash extractor.
3. Crack the hash using johnny.
4. Enter the discovered password and capture the flag.
5. Use other industry tools like NetworkWalks Hash Calculator to get the hash of pdf file, then crack the password.

# Lab
## Step 1
I downloaded John the Ripper and Johnny from the google drive provided us. I installed both and put the correct directory to John the Ripper in Johnny and was ready to use.

<img width="872" height="654" alt="Johnny 9_22_2026 9_39_54 PM" src="https://github.com/user-attachments/assets/b92a2c75-3ebf-4f6e-b52d-2c71ef2b8387" />


## Step 2 
I made use of an online hash calculator to get the hash of the protected pdf file.

<img width="1920" height="1020" alt="PDF Hash Extractor _ Online Hash Crack - Google Chrome 9_22_2026 9_42_08 PM" src="https://github.com/user-attachments/assets/494669ab-60d0-471a-8411-c4c7e0d8d18f" />

## Step 3 
I cracked the hash using Johnny. 

<img width="872" height="654" alt="Johnny 9_22_2026 8_42_44 AM" src="https://github.com/user-attachments/assets/13a3777a-757f-4495-8add-9bc19421de3e" />

## Step 4
I entered the discovered password and captured the flag.

<img width="1920" height="1020" alt="My Locked PDF1 pdf (SECURED) - Adobe Acrobat Reader (64-bit) 9_22_2026 8_44_45 AM" src="https://github.com/user-attachments/assets/74711339-c7d9-4c2e-a466-c049717322f5" />

<img width="653" height="153" alt="Downloads 9_22_2026 8_43_53 AM" src="https://github.com/user-attachments/assets/7a7f0be7-85c7-4b6a-b7e1-2564d9b64434" />

## Step 5
I used other industry standard tools like Networkwalks hash calculator and password cracker to achieve the same result. I first used the hash calculator to get the hash of the protected pdf file.

<img width="1920" height="1020" alt="Password Cracker (Dictionary Attack) - Networkwalks Academy — Mozilla Firefox 9_22_2026 2_11_00 PM" src="https://github.com/user-attachments/assets/e129921e-7896-401e-a863-69fa23db83c9" />

I then began cracking, but it was unsuccessful as the default word list did not contain the particular hash. So i shuffled between different word lists till there was a successful crack.

<img width="1920" height="1020" alt="Password Cracker (Dictionary Attack) - Networkwalks Academy — Mozilla Firefox 9_22_2026 2_12_16 PM" src="https://github.com/user-attachments/assets/da873046-c0b1-49d0-8d7f-003dfb900e59" />

Fasttrack.txt unsuccessful.
<img width="1920" height="1020" alt="Password Cracker (Dictionary Attack) - Networkwalks Academy — Mozilla Firefox 9_22_2026 2_27_47 PM" src="https://github.com/user-attachments/assets/ade2e62a-820b-4148-80a0-4aee9b89a41c" />

JTR_default_password.txt successful. 
<img width="1920" height="1020" alt="Password Cracker (Dictionary Attack) - Networkwalks Academy — Mozilla Firefox 9_22_2026 2_28_25 PM" src="https://github.com/user-attachments/assets/8589a448-284a-4d8d-af11-00549c827e79" />
<img width="1920" height="1020" alt="Password Cracker (Dictionary Attack) - Networkwalks Academy — Mozilla Firefox 9_22_2026 2_35_53 PM" src="https://github.com/user-attachments/assets/8bd65a0c-03c4-4220-94b1-8a1567961f2b" />










