# CyberTech Ninja OSINT CTF Challenge 🕵️‍♂️  

Welcome to the **CyberTech Ninja CTF Challenge!** Your mission is to uncover a **hidden flag** using **Google Dorking and OSINT techniques**.  

## 📌 Challenge:  
1️⃣ Use **Google Dorking** to locate a file in this repository.  
2️⃣ Search for a **debugging log** that may contain useful clues.  
3️⃣ Decode any hidden messages inside the log file.  

## 💡 Hints:  
- Try searching with:  
  ```  
  site:github.com/CyberTech-ninja "debug_log.txt"  
  ```  
- Look for **suspicious comments** in the log file.  
- Some data might be **encoded** in base64.  
- Example of decoding in Linux/macOS:  
  ```sh  
  echo "RkxBR3tIaWRkZW5faW5fTG9nc30=" | base64 --decode  
  ```  
Good luck, and happy hunting! 🚀
