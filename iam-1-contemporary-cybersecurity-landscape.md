Araz Shahinian
05/15/2022
NJIT Cybersecurity
Activity (iam-1-contemporary-cybersecurity-landscape)
Cross Site Scripting (XSS)
1.	Specifically, how is this type of attack conducted?
a.	XSS attacks occur when an attacker uses a web application to send malicious code, generally in the form of a browser side script, to a different end user.  Flaws that allow these attacks to succeed are quite widespread and occur anywhere a web application uses input from a user within the output it generates without validating or encoding it.
b.	
2.	What are the biggest risks from this type of attack?
a.	Account impersonation: Getting the users credentials and pretending to be the user.
b.	Spying on the behavior of the user: Capturing Keystrokes or user click behavior and sending it back to the attacker.
c.	Injecting false content on a page:  Putting pictures or text on a page that can trick the user into thinking they are inputting information for one thing but really are inputting information for another.
d.	Stealing Personal Private Information from the user:  Just plain copying and sending user identity information back to the attacker, like SSN.
3.	How can this type of attack be defended against?
a.	Form Validation: Sanitize Data that is submitted in a form, looking for scripting or markup language and blocking it.
b.	HTML Headers:  Some HTML Headers will invoke client-side validation automatically.
c.	Encoding input to make it not run the script.
4.	Are there notable examples of this type of attack in the news?
a.	British Airways: 380,000 booking transactions were attacked to gain CC info.
b.	Fortnite: 200 million users were affected, attacker stole game virtual currency

Rainbow Tables
1.	Specifically, how is this type of attack conducted?
a.	Using a table to figure out how passwords or other types of data are encrypted.
2.	What are the biggest risks from this type of attack?
a.	Account Impersonation:  User gets into your account and gets your money or information.
3.	How can this type of attack be defended against?
a.	Salt techniques can be used to defend against a rainbow table attack.  Salt techniques involve random data that is passed into the hash function along with the original text.  It makes sure that each password or other sensitive data is unique.   So, by using the original plain text without the injected random text would not produce results with a decryption algorithm.
4.	Are there notable examples of this type of attack in the news?
a.	Ubisoft a video game distributer was hacked in this way. 

