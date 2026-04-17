# The-Beginning-of-My-Cybersecurity-Career-
Account hijacking vulnerability



​🛠️ Car Parking Multiplayer - Critical Account Takeover Vulnerability (P1)
​This repository documents a critical vulnerability I discovered in the Car Parking Multiplayer (com.olzhas.carparking.multyplayer) application, which was dismissed by the development team due to "insufficient evidence," but is based on the leakage of Google Identity Toolkit API keys.


​📝 Vulnerability Summary
​Unrestricted Firebase API keys were found in the application's RAM and runtime files. Using these keys, full privileges can be gained over any user's account (email, password, name). Vulnerability Type: Account Takeover
Affected Version: 4.9.7 (and masked version 4.9.8)
Risk Level: Critical (P1)


🔍 Technical Details (Proof of Concept)
The leaked API key is used to request Google Identity Toolkit endpoints, obtaining an idToken and updating account information.


🚩 Developer Communication and Rejection Process
Despite providing the developer team (Olzhass Games) with all technical details, terminal commands, and screenshots, the following response was received:
"Our team has not found any substantial underlying evidence... we do not award prizes or certificates for such reports."
In response to this, I fulfilled my ethical duty and reported all evidence to the Google Play Security team. 


Code snippets are found in the files. 

SENSITIVE DATA HAS BEEN CENSORED. THERE IS NO BLACKMAIL OR THREATS. 