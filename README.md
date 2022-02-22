# <img src="https://www.passpilot.com/passpilot.png" width="50" /> [PassPilot.com](https://www.passpilot.com/)

# Off-the-grid password manager all in a single HTML file

This repository contains full version of [PassPilot.com](https://www.passpilot.com/) application saved to a single HTML file **ready to be used out of the box**.

The application is pure HTML, JavaScript and CSS code.

The intention for the file was to have a small footprint (currently 215KB) and for that reason it is written in vanilla JavaScript with no UI frameworks.

New versions will be added as new features are being published.

## How to use the file

- Download the latest version of the file

- Open the HTML file in your favourite internet browser and add some new records

- To add a new record, enter the record name in the top input field and click "Add".

- To save your records click "Save to file" then enter a strong password and save everything to a new file, you can overwrite the existing file if you want or save a copy in new place.

Check our FAQ page for more information about the application http://www.passpilot.com/#/faq

## Features added 
v1.9 - 22 Feb 2022 the app can now be used as authenticator in 2-step verification (2FA) as it generates 6-digit time based one time passwords (TOTP)
Read more in FAQ https://www.passpilot.com/#/faq

v1.8 - 01 Apr 2021 added "Passwords check" feature in the "Offline" section. Checks passwords strength, marks weak and reused passwords.

v1.7 (βeta) - 07 Mar 2021 added "Save only application" feature in the "Save to file" card

v1.6 (βeta) - 05 Mar 2021 Initial publication of the application

## Main features of the application

- **Strong client side AES encryption (256bits) using the Stanford Javascript Crypto Library (SJCL)**
- **Trust no one - your unencrypted data will never leave your browser**
- **Noone will ever know your password which is also never sent anywhere (encryption takes place in your browser). You are double protected as encrypted vault is sent over encrypted SSL connection.**
- **Source code of the application is publicly available, anyone with good knowledge of JavaScript can review the code (nothing is compiled).**
- **Off the grid. Probably the best feature of this application is that you can save everything to a single file and use the application offline (every offline feature is available including adding new records), no limits, no ads, for free, forever! Keep it on a flash drive, local drive or any cloud storage of your choice.**
- **If you want - also for free - you can register to save your encrypted vault online and be able to access your data anywhere across all your devices.**
- **Can be used as authenticator in 2-step verification (2FA) as it generates 6-digit time based one time passwords (TOTP)**
- **Contains strong password generator**
- **Two color schemes**
- **Two language versions**

## Libraries used in this project:

- [Stanford Javascript Crypto Library](https://github.com/bitwiseshiftleft/sjcl)

- [zxcvbn Password Strength Estimation](https://github.com/dropbox/zxcvbn)

- [eligrey FileSaver.js An HTML5 saveAs() FileSaver implementation](https://github.com/eligrey/FileSaver.js)
