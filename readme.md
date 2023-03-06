![GitHub commit activity](https://img.shields.io/github/commit-activity/m/Svendolin/All-about-HACK?style=for-the-badge) ![GitHub contributors](https://img.shields.io/github/contributors/svendolin/All-about-HACK?style=for-the-badge) ![GitHub forks](https://img.shields.io/github/forks/Svendolin/All-about-HACK?color=pink&style=for-the-badge) ![GitHub last commit](https://img.shields.io/github/last-commit/Svendolin/All-about-HACK?style=for-the-badge) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/Svendolin/All-about-HACK?color=yellow&style=for-the-badge)


***


# <img align="left" alt="HTML" width="35px" src="https://banner2.cleanpng.com/20180626/ijk/kisspng-computer-security-threat-national-cyber-security-a-topic-logo-5b32ac279670a0.5387674615300475276162.jpg" /> - ALL ABOUT SECURITY STUFF - ✔

**IMPORTANT:**
_Use what you learn for the good side. Harming others with it is uncool and not appropriate!_

**TRY YOUR KNOWLEDGE:**
OWASP Juice Shop: Probably the most modern and sophisticated insecure web application: [CLICK HERE](http://demo.owasp-juice.shop/#/)

Link to the Github Version to clone their repository: https://github.com/juice-shop/juice-shop






<br />
<br />


***
## Some important words and phrases💥
***

| Name | Where | Meaning  | 
|:--------------| :--------------| :--------------|
|1) Xss Attack / Crosssite Scripting | Input fields |  If you put code (like Javascript code ) into an input field and inject it into the website, it will be executed by the browser or several other devices. This is called Cross Site Scripting (XSS) and can be used to steal cookies, session tokens, or redirect the user to a malicious site. |
| 2) SQL Injection | ...| If you safe date, these are going to be saved in a SQL-Table. The Structured Query Language is used here to work with these data types. We take over the administrator, decrypt the password and have access to his account (Email and Password out of a database table) when we put SQL Code into an input field |
| 3) Front-End Validation | ... |Important data, e.g. of a webshop (prices and product names) should not only be validated in the front-end, but also in the back-end. In the best case, we send the ID of a product to the back-end, as it is easy to rewrite the HTML source code locally in the front-end through the Inspector.|
| 4) SSL Certificate | ...| Connection between browser and web server takes place unencrypted (downloads, uploads etc) |
| 5) Port 80 vs Port 443 | ...| HTTP Port is usually described as "80" while the secured protocol (https) is known as 443
| 6) HEX-Encoding | ...| Passwords can be encrypted, e.g. by encoding them. The decoding is in return the re-encryption. Wireshark itself has the tool to copy lines and show this section as printable text "druckbarer Text" (conversion) |

<br />

_**Some notes about the related stuff above explained with some codes:**_

```js
/* -- 1) Injected in an input field, this is going to redirect to its website as shown (Google) when the page is tring to load -- */
<script>
  window.location.href = "https://www.google.com";
</script>

```
_**Frontend, Backend and DB:**_
- Frontend is what we see and has been manupulated. The frontend communicates with a backend that processes and stores the data. 

- The backend is not visible to the user and is realised by PHP, Node.js or Python, for example. The backend reads the data from the frontend, then receives and stores the data in a database.

- The data is stored in the database and can be retrieved from there.

_**Post Request (Also mentioned in PHP Repository)**_
- Frontend sends data to the backend (e.g. username and password) and the backend checks if the data is correct. Post ADDS data to the database. 

**=> The aim is to prevent HTML code from being entered in the first place by rewriting the character. Thus, "<" characters are often replaced**
<br />
<br />

***
## Technologies and Installation ✅
***





_**WIRESHARK:**_

Wireshark is a free software for analysis and graphical processing of data protocols, which was created in 2006 as a fork of the program Ethereal. Such data protocols are used by computers on various communication media such as the local network, Bluetooth or USB. Wireshark is a packet sniffer and analysis tool. It captures network traffic on the local network and stores this data for offline analysis.

- Wireshark Website + Download:  [CLICK HERE](https://www.wireshark.org/)
- Wireshark Basics (video):  [CLICK HERE](https://www.youtube.com/watch?v=lb1Dw0elw0Q)



```js
/* ---- Your notes here ---- */



```


<br />
<br />


***
## Collaboration ✅
***
> Feel free to contact me if you've seen something wrong, found some errors or struggled on some mistakes! Always happy to have a clean sheet here! :)


<br />
<br />

***
## FAQs ✅
***
0 Questions have been asked, 0 answers have been given, 0 changes have been made.

| Questions | Anwers | Changes |
|:--------------|:-------------:|--------------:|
| 0 | 0 | 0 |


