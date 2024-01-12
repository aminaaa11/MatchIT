**MatchIT** 

**Bug 1.**

**Title: Profil regrutera (Web) | “Kontakt broj” input field can have invalid phone number**

**Description:** User can enter only one number, such as '1', into the “Kontakt broj”' field and save their information, even though it isn’t correct

**Precondition:** User must be logged in

**Steps to reproduce:**

1. Click on dropdown list 

2. Click on “Profil regrutera”

3. Click on “Kontakt broj” input field

4. Clear existing number

5. Enter a number (1)

6. Click on the “Sačuvaj” button

**Expected result:** User doesn’t save the data, error message “Kontakt broj nije ispravan” is displayed. 

**Actual result:** User can save invalid data

**Priority:** Low

**Severity:** Minor

**Type:** Functional bug

**Environment:** Laptop HP, Windows 11 pro, 21H2v.

**Attachment:** ![](https://lh7-us.googleusercontent.com/N5_pHFo2AEalxv8SHxC-G8gg_xn_35JmwhmsOvRshueR16KXuvDYr00qIrFX0-hnNC6MiohKG0zH9vSxrSskhRZnRomZooHQU9qbIP2l3esIyLBIcxT0XbdpkGBi-4k39slrWCqXD3reAkz1JwGP2VA)

**Bug 2.**

**Title: Log in (mobile) |** Application unexpectedly closes, when User click on the  "NASTAVI DALJE" button

**Description:** When User click on the "NASTAVI DALJE '' button on the Login page, the application closes and user is on the home screen of his mobile phone.

**Precondition:** User isn't logged in

**Steps to reproduce:**

1. Open mobile app

2. Click on the “Nastavi dalje” button

**Expected result:** An error message "Molimo unesite Vašu email adresu” should be displayed.

**Actual result:** Application unexpectedly closes upon clicking the "NASTAVI DALJE” button.

**Priority:** High 

**Severity:** Critical

**Type:** Functional bug

**Environment:** Iphone 14 pro, 16.5v

**Attachment:** <https://drive.google.com/file/d/1dXGAm4PtmWscaDo_LG7YC3-XBTjvNiYn/view?usp=sharing> 

**Bug 3.**

**Title: Log in (mobile) |** Inconsistency with Repeated Words (e.g., 'mejl' and 'e-mail') in Application

**Description:** When encountering repeated words with variations like 'mejl' and 'e-mail' in the application, inconsistent handling or recognition may occur. This inconsistency could lead to confusion or errors in the user experience.

**Precondition:** User isn't logged in

**Steps to reproduce:**

1. Open mobile app

2. Enter a valid email address (amina.salcin99\@gmail.com)

3. Click on the “Nastavi dalje” button

4. Verify the text paragraph

**Expected result:** All repeated words should be written in the same way

**Actual result:** Two same words are written in different ways, which is very noticeable in this paragraph.

**Priority:** Low

**Severity:** Minor

**Type:** Content bug

**Environment:** Iphone 14 pro, 16.5v

**Attachment: **![](https://lh7-us.googleusercontent.com/tTOong5Uq6mCNVwNuVeytkEgoWSgQvivS3p0zoRn_U8OT3HsBIc1IzEF3CWwxBHVh-Ae8-0YEDMHjrkW9gO2rH0H5UdPnSEB6tw2bY1K9Zyb-0x3hXCq8QvmrLtI8n6E-rYzy7PKhvnpil8XDGY_GgY)****

**Bug 4.**

**Title: QA Analyst - Deck (web) |** Performance issues for displaying position relevant candidates

**Description:** Upon clicking the “Deck Kandidata” icon in the QA Analyst position, the page takes longer than one minute to load, negatively impacting user experience and efficiency in accessing candidate information.

**Precondition:** User mumst be logged in

**Steps to reproduce:**

1. Scroll to QA Analyst advertisement

2. Click on “Deck kandidata” icon

**Expected result:** Candidates should be displayed immediately after clicking.

**Actual result:** User experiences an extended wait time for candidate loading, exceeding 1 minute

**Priority:** High

**Severity:** Major

**Type:** Performance issue

**Environment:** Iphone 14 pro, 16.5v

**Attachment: **![](https://lh7-us.googleusercontent.com/NyF7SQBzwXlJJXBui_8Vu-pIm1koo97YUPk6oueOJEohwPQm3YozR1VV2WaAGgyYJD1ZiUYLIu4E43949W3WkM_WEd1omxXCv77N1yNDCSEQxnNOKzLZbD7tE3gOA8XP2YCRX_ld-keYD0EuC3T12Do)****

**Bug 5.**

**Title: Kreiranje oglasa (mob) |** The option selected from the dropdown in  “Benefiti” section isn’t being displayed

**Description:** Benifiti option isn't displayed after selecting on the mobile version of web app

**Precondition:** User must be logged in

**Steps to reproduce:**

1. Click on the “Kreiraj oglas” button on top right corner

2. Scroll to the bottom of page

3. Click on first input field in “Benefiti” dropdown box

4. Select the option from the dropdown list(13. Plata)

**Expected result:** All selected options should be visible in the dropdown.

**Actual result:** The option is empty even after the user selected an option from the list.

**Priority:** Low 

**Severity:** Minor

**Type:** Visual bug

**Environment:** Samsung Galaxy S8+, Browser/Tools: DevTools

**Attachment: **![](https://lh7-us.googleusercontent.com/Vtop3d3VL4dqiGexLk6zlNMGGb91A1YEAeWgz2WZPhYwot_b9Ha2ZVcUDBopoRX3tsrSA9MV2aIXfoAZ-xj8yg13jxpCUqijaQ7ApdPFZaQqVimcnOjG2XVxmAuwckwvr8yxVmL3SpoRPf4rxn8DD7s)****

**Bug 6.**

**Title: Kreiranje oglasa (mob) |** Sections aren’t aligned properly in the 'Projekti' card, causing a disruption in the page's UI

**Description:**  Sections aren’t aligned properly in the 'Projekti' card, causing a disruption in the page's UI

**Precondition:** Open web app on mobile phone

**Steps to reproduce:**

1. Click on the “Kreiraj oglas” button on top right corner

2. Scroll to the “Projekat” card

**Expected result:** Different alignment for the 'Projects' section inputs is causing a disruption in the UI.

**Actual result:** All section and input fields aren’t aligned properly and don’t comply with UI guidelines

**Priority:** Low

**Severity:** Minor

**Type:** Visual bug

**Environment:** Samsung Galaxy S8+, Browser/Tools: DevTools

**Attachment: **![](https://lh7-us.googleusercontent.com/8-3bc-5LCuWBY-5QHRGkxwX-4U1N1iwzTuJmcs5_iGThyU7BtxFw2L42UXRgYQVvej6ByTLo8RjjWSOePDn-oV5of6JYDcrq-vUk2wpqqU8WF0aU2FOomd-3pi-jsasi4HGm470qWC1r6QyyiIyxNxo)****

**Bug 7.**

**Title: Login (web) |** Language inconsistency on login page: Presence of Mixed English and Bosnian Terms in Information and Popup Messages

**Description:** Upon inspection of the Login page, it was observed that the information and popup messages lack language consistency. The content presents a mix of both English and Bosnian terms, creating an inconsistency that may impact the overall user experience.

**Precondition:** Open web app

**Steps to reproduce:**

1. Click on Login link on the bottom of the page

2. Enter an invalid email into email input field (a)

3. Click on “Login” button

**Expected result:** On the Login page, all information and popup messages are written in a  consistent language

**Actual result:** On the Login page, information and popup messages are presented in a mix of both English and Bosnian languages, lacking consistency.

**Priority:** Low

**Severity:** Minor

**Type:** Content bug

**Environment:** Laptop HP, Windows 11 pro, 21H2v.

**Attachment: **![](https://lh7-us.googleusercontent.com/twVFX37YDiWi-hK5f9bIH_gdxAzBfdSFfqM4zKbjRyMGsm6g7HQG6wykkyMnXmsSRguhfO3M93Z6-GsRSFkDWoudUeaGDGK6c_bmnNsqZxOBAQpLBO7dfFR_uosh55VvUKEJCD-Z1IxskimwDae-RiQ)****

********
