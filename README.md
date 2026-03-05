# DMZ2026
Data Modeling Zone 2026 workshop

## 1. License validation
Hackolade Studio trial license key **BJRK0-N0300-GH144-182BM-2P8QF-1AH4R-4S28D-IBCJ8E53** is valid through March 15, 2026.  Follow the steps below:

1) go to <a href="https://studio-demo1.hackolade.com" target="_blank" rel="noopener noreferrer">https://studio-demo1.hackolade.com</a> (Use Ctrl/Cmd+click to open in a new tab)
2) click the Accept button for the License Agreement, then click the Close button to bypass the Overview slides
3) go to the menu option Help > License Status (or click the key icon in the bottom left of the browser tab
4) paste the license key **BJRK0-N0300-GH144-182BM-2P8QF-1AH4R-4S28D-IBCJ8E53**
5) enter some identifier that you can recognize -- **note** that, for privacy reasons, it is not required for this identifier to be your name or email address
6) click the Validate button

Getting Started videos are available on our <a href="https://community.hackolade.com/slides/hackolade-studio-tutorial-0-vision-getting-started-6" target="_blank" rel="noopener noreferrer">eLearning platform</a>  (Use Ctrl/Cmd+click to open in a new tab)

This browser-based data modeling solution is highly secure.  See more information about the security-first architecture in our <a href="https://hackolade.com/help/Security-firstbrowserdeployment.html" target="_blank" rel="noopener noreferrer">online documentation</a>  (Use Ctrl/Cmd+click to open in a new tab)

## 2. Repository connection
In order to access files prepared in our repository, you must create a connection to your repo:

1) go to the menu option Repository > Repository Connections (last option in the menu)
2) paste the access token published in <a href="https://hackoladestudio-my.sharepoint.com/:w:/g/personal/pascal_desmarets_hackolade_com/IQCLU6CwcmGGTbt-0oAJz1lSAU7sUqw4fbTNJCGBK6iHjWI?e=B7jLLn" target="_blank" rel="noopener noreferrer">this document</a> (Use Ctrl/Cmd+click to open in a new tab)
3) click the Connect button, then close the dialog.

## 3. Adjust parameter to facilitate operations with repo
1) go to Tools > Options
2) in the General tab, first line, choose GitHub from the dropdown list
<img width="864" height="221" alt="image" src="https://github.com/user-attachments/assets/d81d4ad9-c38e-4719-83ab-d9002df0c5e8" />

3) click the OK button

## 4. Prompt your prefered GenAI tool
1) go to https://github.com/hackolade-public/DMZ2026/blob/main/GenAI/prompt.md
2) copy the proposed prompt
3) paste in your prefered GenAI tool

## 5. Generate ERD in Hackolade Studio
1) copy the output from your GenAI tool, or copy from https://github.com/hackolade-public/DMZ2026/blob/main/GenAI/ChatGPT%20prompt%20result
2) open the prepared empty model DMZ2026 Polyglot model.hck.json from the GitHub repository with this link [https://studio-demo1.hackolade.com/?g=github&o=hackolade-public&r=DMZ2026&f=models%2FDMZ2026+Polyglot+model.hck.json ](https://studio-demo1.hackolade.com/?g=github&o=hackolade-public&r=DMZ2026&f=models%2FDMZ2026+Polyglot+model.hck.json&b=main) (Use Ctrl/Cmd+click to open in a new tab)
3) go to Tools > Reverse-Engineer > Mermaid ER Diagram...
<img width="678" height="356" alt="image" src="https://github.com/user-attachments/assets/94e62495-8630-4392-b346-260a093ec589" />

4) choose Clipboard in the left menu
<img width="378" height="238" alt="image" src="https://github.com/user-attachments/assets/b0ee56df-74d7-40cd-b030-aa0b5421edc3" />

5) the copied code from the GenAI output should appear
<img width="1905" height="1168" alt="image" src="https://github.com/user-attachments/assets/e4c24e8f-5122-458e-90bf-f4cd5f386da5" />

6) click the Open button at the bottom right of the dialog
7) after a few seconds, the progress dialog should give you this kind of information:
<img width="741" height="592" alt="image" src="https://github.com/user-attachments/assets/39c086bb-8d05-4a3c-8cf2-b91a7d6e388e" />

8) after clicking the OK button, you should see the ERD result
<img width="1918" height="891" alt="image" src="https://github.com/user-attachments/assets/d5ea0559-01a6-455a-bc5e-20803ae947ba" />








