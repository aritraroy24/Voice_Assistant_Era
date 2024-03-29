![](https://img.shields.io/badge/git-fff7f8?colorA=faf0f0&colorB=db4823&style=for-the-badge&logo=git)
![](https://img.shields.io/badge/github-fff7f8?colorA=080808&colorB=8a8a8a&style=for-the-badge&logo=github)
![](https://img.shields.io/badge/for-you-099450?colorA=b0c92e&colorB=487d3e&style=for-the-badge)
![](https://img.shields.io/badge/python-used-bee5ed?colorA=37b6bd&colorB=3c9bb5&style=for-the-badge&logo=python)
![](https://img.shields.io/badge/visual_studio_code-1.48.0-181717?colorA=ae36d6&style=for-the-badge&logo=visual-studio-code)
---
### Simple voice assistant program made with simple if-else statements :speaking_head:
---
# :small_orange_diamond: credentials.json :notebook_with_decorative_cover:
### For getting access from Google Contacts using Gmail API :busts_in_silhouette: :e-mail: :calling:
After generating Gmail API, the CLIENT CONFIGURATION will be saved as ***```credentials.json```***. It should be kept in the working directory. otherwise contacts details can't be fetched from Google Contacts.
# :small_orange_diamond: token.pickle :memo:
All the details will be saved in ***```token.pickle```*** file and no further retrieving will be occurred if there is no change.
# :small_orange_diamond: era_ai.py :bust_in_silhouette:
##### All the tasks (possible by Era) are following -
1. Tells ***```'I'm fine'```*** when asked ***```how are you```***.<br><br>
2. Tells ***```It's good to know that you are fine```*** if the word ***```fine```*** is in the query.<br><br>
3. ***```Finds and tells related data about query```***(first two sentences) from wikipedia if ***```wikipedia```*** is in the query.<br><br>
4. It'll say ***```I'm Era - a personal desktop assistant```*** when asked ***```who are you```***.<br><br>
5. ***```Opens Spartan14```***(a chemistry software) if ***```spartan```*** is in the query.
<br>&nbsp;&nbsp;&nbsp;&nbsp; :black_small_square: The target path should be specified ***(software -> file location -> properties -> target path).***<br><br>
6. ***```Opens YouTube```*** if ***```youtube```*** is in the query.
<br>&nbsp;&nbsp;&nbsp;&nbsp; :black_small_square: The target URL should be specified ***(https://www.youtube.com/)*** :link:<br><br>
7. ***```Opens Google```*** if ***```google```*** is in the query.
<br>&nbsp;&nbsp;&nbsp;&nbsp; :black_small_square: the target URL should be specified ***(https://www.google.co.in/)*** :link:<br><br>
8. ***```Opens Stack Overflow```*** if ***```stackoverflow```*** is in the query.
<br>&nbsp;&nbsp;&nbsp;&nbsp; :black_small_square: The target URL should be specified ***(https://stackoverflow.com/)*** :link:<br><br>
9. ***```Plays a random somg or changes the song```*** if ***```play song```*** or ***```change song```*** is in the query.
<br>&nbsp;&nbsp;&nbsp;&nbsp; :black_small_square: The local folder should be specified where the songs are kept.<br><br>
10. Tells us the current local ***```time```*** if ***```time```*** is in the query.<br><br>
11. ***```Opens Visual Studio Code```*** if ***```code```*** is in the query.
<br>&nbsp;&nbsp;&nbsp;&nbsp; :black_small_square: The target path should be specified ***(software -> file location -> properties -> target path)***.<br><br>
12. ***```'Quits the application'```*** when ***```quit```*** or ***```close```*** or ***```exit```*** in the query.<br><br>
13. Tells ***```'Thank you sir, I'm always here for you'```*** when ***```awesome```*** or ***```amazing```*** in the query.<br><br>
14. ***```Searches in Google```*** about the query if ***```what```*** or ***```who```*** or ***```where```*** or ***```can you```*** in the query.<br><br>
15. ***```Sends a mail to the contact```*** if the query matches with one of the ***```Google Contacts```***.
<br>&nbsp;&nbsp;&nbsp;&nbsp; :black_small_square: The ***contacts*** and associated ***email ids*** can be fetched using ***Gmail API***.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :white_small_square: For more details about **unlimited retrieving of contact details using Gmail API** please read my article published in ***```Medium```*** - <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;https://medium.com/@aritraroycoc/retrieving-email-and-phone-no-7c60ad3a9b69 :link:
<br>&nbsp;&nbsp;&nbsp;&nbsp; :black_small_square: To send mail inbuilt module **smtplib**  is used. But one has to ***less secure apps and google account using G Suite Admin Account***.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :white_small_square: Please note, **it is not normal Google Account and read all the terms and conditions for further approaching**.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :white_small_square: For futher information please visit - <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;https://support.google.com/a/answer/6260879?hl=en :link: <br><br>
16. ***```Makes a voice call to the contact```*** if the query matches with one of the ***```Google Contacts```***.
<br>&nbsp;&nbsp;&nbsp;&nbsp; :black_small_square: The ***contacts*** and associated ***phone numbers*** can be fetched using ***Gmail API***.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :white_small_square: For more details about **unlimited retrieving of contact details using Gmail API** please read my article published in ***```Medium```*** - <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;https://medium.com/@aritraroycoc/retrieving-email-and-phone-no-7c60ad3a9b69 :link:
<br>&nbsp;&nbsp;&nbsp;&nbsp; :black_small_square: To make voice calls I've taken the help of ***Twilio account***.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :white_small_square: One'll need to get ***account_sid*** and ***auth_token***. Please check all the details at - <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;https://www.twilio.com/docs/voice/tutorials/how-to-make-outbound-phone-calls-python :link:
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :white_small_square: Please note, ***One can only make call to the registered number for a limited trial period***. For full access **one'll need to pay**.
# How to Use :question::question::question:
### Follow These Simple Steps:
* **Star** and **Fork** this repo to your account
* Go to your project folder using your shell and run the following code to install all the required modules - <br> **```pip install -r requirements.txt```**
* Now run the python code to enjoy the assistance of **Era**.

## :blush::blush::blush:Contributors Are Welcome :blush::blush::blush:
#### Step for Contribution:
* **Star** and **Fork** this repo to your account
* Create a **New Branch** and do **Necessary Modification**
* Send a **PR**

## Found a bug :x::x::x:
Don' t worry I am always here to help you. Create a issue [HERE](https://github.com/aritraroy24/Voice_Assistant_Era/issues)

## Loved My Work :heart_eyes::heart_eyes::heart_eyes:
You can  help me by contributing here :point_right: <a href="https://www.buymeacoffee.com/aritraroy24" ><img align="center" src="https://www.linkpicture.com/q/buycoffee.png" width="150" /></a>
</p>
