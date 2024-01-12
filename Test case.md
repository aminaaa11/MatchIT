**MatchIT (mobile app)**

****

Test case ID: B\_001

Module name: Benefiti

Test title: **Verify that User should select at least 1 benefit** 

Description: Verify that User can select only one benefit “Životno osiguranje” which is located at the bottom of the page.

****

Precondition: User must be logged in

****

|                  |                                               |             |                                                  |
| ---------------- | --------------------------------------------- | ----------- | ------------------------------------------------ |
| Step no.         | Test steps                                    | Test Data   | Expected result                                  |
| 1.               | Click on Profile tab                          |             | User should be redirected to the Profile page    |
| 2.               | Verify that User can see “Benefiti” option    |             | Benefit option is visible on the page.           |
| 3.               | Click on “Benefiti” functionality             |             | User should be redirected to the “Benefiti” page |
| 4.               | Scroll to the bottom of the page              |             | User should see benefit “Životno osiguranje”     |
| 5.               | Click on the checkbox in the top right corner |             | Checkbox “Životno osiguranje” is checked.        |

****

Test case ID: B\_002

Module name: Benefiti

Test title: Verify that User can select all benefits

Description: Verify that User can select all benefits located on the page.

****

Precondition: User must be logged in
****

|                  |                                            |             |                                                  |
| ---------------- | ------------------------------------------ | ----------- | ------------------------------------------------ |
| Step no.         | Test steps                                 | Test Data   | Expected result                                  |
| 1.               | Click on Profile tab                       |             | User should be redirected to the Profile page    |
| 2.               | Verify that User can see “Benefiti” option |             | Benefit option is visible on the page.           |
| 3.               | Click on “Benefiti” functionality          |             | User should be redirected to the “Benefiti” page |
| 4.               | Select all benefits on the page            |             | All benefits are selected on the page            |

****

Test case ID: B\_003

Module name: Benefiti

Test title: **Verify that User can find a benefit using search**

Description: Verify that users are able to successfully locate the "Stipendija" benefit by utilizing the search input functionality within the application.

****

Precondition: User must be logged in

****

|                  |                                            |             |                                                  |
| ---------------- | ------------------------------------------ | ----------- | ------------------------------------------------ |
| Step no.         | Test steps                                 | Test Data   | Expected result                                  |
| 1.               | Click on Profile tab                       |             | User should be redirected to the Profile page    |
| 2.               | Verify that User can see “Benefiti” option |             | Benefit option is visible on the page.           |
| 3.               | Click on “Benefiti” functionality          |             | User should be redirected to the “Benefiti” page |
| 4.               | Click on search input                      |             | Search field is in the focus after click         |
| 5.               | Enter data into the search input field     | Stipendija  | The provided data is entered and displayed       |
| 6.               | Verify that User can see “Stipendija” option|            | Stipendija option is visible on the page.        |

****

Test case ID: B\_004

Test priority:

Module name: Benefiti

Test title: **Verify that search input retrieves data when the user enters a space before the data.**

Description: Verify if the user can search for the 'Stipendija' benefit by entering a space before the data

****

Precondition: User must be logged in

****

|                  |                                            |             |                                                  |
| ---------------- | ------------------------------------------ | ----------- | ------------------------------------------------ |
| Step no.         | Test steps                                 | Test Data   | Expected result                                  |
| 1.               | Click on Profile tab                       |             | User should be redirected to the Profile page    |
| 2.               | Verify that User can see “Benefiti” option |             | Benefit option is visible on the page.           |
| 3.               | Click on “Benefiti” functionality          |             | User should be redirected to the “Benefiti” page |
| 4.               | Click on search input                      |             | Search field is in the focus after click         |
| 5.               | Enter a space before data                  |  Stipendija | Value is entered and visible in the search bar and only option "Stipendija" is visible.     |
                                            

****



****

Test case ID: B\_005

Module name: Benefiti

Test title: **Verify that search input retrieves data when the user enters letters without diacritics ('čćšđž')**

Description: Verify if the search field retrieves data when the user enters “Budzet za edukaciju” instead of “Budžet za edukaciju”.

****

Precondition: User must be logged in

****

|                  |                                            |                     |                                                       |
| ---------------- | ------------------------------------------ | ------------------- | ----------------------------------------------------- |
| Step no.         | Test steps                                 | Test Data           | Expected result                                       |
| 1.               | Click on Profile tab                       |                     | User should be redirected to the Profile page         |
| 2.               | Verify that User can see “Benefiti” option |                     | Benefit option is visible on the page.                |
| 3.               | Click on “Benefiti” functionality          |                     | User should be redirected to the “Benefiti” page      |
| 4.               | Click on search input                      |                     | Search field is in the focus after click              |
| 5.               | Enter a valid data                         | Budzet za edukaciju | Value is entered and visible in the search bar and only option "Budžet za edukaciju" is visible. |

****


****

**MatchIT (web app)**

****

Test case ID: P\_001

Module name: Profil Regrutera

Test title: **Verify that User can change data on profile with valid first name, last name and phone number**

Description: Verify that User can change data on profile with valid first, last name and phone number

****

Precondition: User must be logged in

****

|                  |                                                                  |             |                                                                                                           |
| ---------------- | ---------------------------------------------------------------- | ----------- | ------------------------------------------------------------------------------------------------------------ |
| Step no.         | Test steps                                                       | Test Data   |  Expected result                                                                                              |
| 1.               | Click on dropdown in the top right corner                        |             | User should see dropdown menu                                                                                |
| 2.               | Click on “Profil regrutera” option                               |             | User should redirect “Profil regrutera” page. |
| 3.               | Click on first name input field and enter a valid first name     | Amina       | Entered first name is visible in the input.                                                                            |
| 4.               | Click on last name input field and enter a valid last name       | Salčin      | Entered last name is visible in the input.                                                                         |
| 5.               | Click on phone number input field and enter a valid phone number | 062588987   |Entered phone number is visible in the input.                                                                      |
| 6.               | Click on the button “Sačuvaj”                                    |             | The data has been successfully updated, and a popup message “Tvoj profil je uspešno izmenjen.” is displayed. |

****


****

Test case ID: P\_002

Module name: Profil Regrutera

Test title: **Verify that User can't change data on profile with invalid first name** 

Description: Verify that User can't change data on profile with only one invalid first name, valid last name and phone number, an error message is being displayed.


****

Precondition: User must be logged in

****

|                  |                                                                  |             |                                                                                                            |
| ---------------- | ---------------------------------------------------------------- | ----------- |------------------------------------------------------------------------------------------------------------ |
| Step no.         | Test steps                                                       | Test Data   | Expected result                                                                                              |
| 1.               | Click on dropdown in the top right corner                        |             | User should see dropdown menu                                                                                |
| 2.               | Click on “Profil regrutera” option                               |             | User should see “Profil regrutera” page                                                                      |
| 3.               | Click on first name input field and enter an invalid first name  | 12          | Entered first name is visible in the input                                                                               |
| 4.               | Click on last name input field and enter a valid last name       | Salčin      | Entered last name is visible in the input                                                                              |
| 5.               | Click on phone number input field and enter a valid phone number | 062588987   | Entered phone number is visible in the input                                                                            |
| 6.               | Click on the button “Sačuvaj”                                    |             |The data hasn’t been successfully updated, and a popup message “Dozvoljen je unos samo slova.” is displayed. User stays on the same page."| 

****


****

Test case ID: P\_003


Module name: Profil Regrutera

Test title: **Verify that User can't change data on profile with invalid last name.** 

Description: Verify that User can't change data on profile with only one invalid last name, valid first name and phone number, an error message is being displayed

****

Precondition: User must be logged in

****

|                  |                                                                  |             |                                                                                                              |
| ---------------- | ---------------------------------------------------------------- | ----------- |  ------------------------------------------------------------------------------------------------------------ |
| Step no.         | Test steps                                                       | Test Data   |  Expected result                                                                                              |
| 1.               | Click on dropdown in the top right corner                        |             | User should see dropdown menu                                                                                |
| 2.               | Click on “Profil regrutera” option                               |             |User should see “Profil regrutera” page                                                                      |
| 3.               | Click on first name input field and enter a valid first name     | Amina       | Entered first name is visible in the input   //promeniti sve u pasiv                                                                           |
| 4.               | Click on last name input field and enter an invalid last name    | 12          |Entered last name is visible in the input                                                                                |
| 5.               | Click on phone number input field and enter a valid phone number | 062588987   | Entered phone number is visible in the input                                                                            |
| 6.               | Click on the button “Sačuvaj”                                    |             | The data hasn’t been successfully updated, and a popup message “Dozvoljen je unos samo slova.” is displayed. User stays on the same page. |

****


****

Test case ID: P\_004


Module name: Profil Regrutera

Test title: **Verify that User can't change data on profile with invalid phone number.** 

Description: Verify that User can't change data on profile with only one invalid last name, valid first name and phone number, an error message is being displayed

****

Precondition: User must be logged in

****

|                  |                                                                     |             |                                                                                                          |
| ---------------- | ------------------------------------------------------------------- | ----------- | --------------------------------------------------------------------------------------------------------- |
| Step no.         | Test steps                                                          | Test Data   | Expected result                                                                                           |
| 1.               | Click on dropdown in the top right corner                           |             | User should see dropdown menu                                                                             |
| 2.               | Click on “Profil regrutera” option                                  |             |User should see “Profil regrutera” page                                                                   |
| 3.               | Click on first name input field and enter a valid first name        | Amina       | Entered first name is visible in the input                                                                            |
| 4.               | Click on last name input field and enter a valid last name          | Salčin      | Entered last name is visible in the input                                                                             |
| 5.               | Click on phone number input field and enter an invalid phone number | 0           | Entered phone number is visible in the input                                                                          |
| 6.               | Click on the button “Sačuvaj”                                       |             | The data hasn’t been successfully updated, and a popup message “Broj nije ispravno unešen.” is displayed. User stays on the same page. |

****


****

Test case ID: P\_005


Module name: Profil Regrutera

Test title: **Verify that User can't change data on profile with empty first name** 

Description: Verify that User can't change data on the profile if they don’t enter a first name but enter a last name and phone number."

****

Precondition: User must be logged in

****

|                  |                                                                  |             |                                                                                                |
| ---------------- | ---------------------------------------------------------------- | ----------- |---------------------------------------------------------------------------------------------- |
| Step no.         | Test steps                                                       | Test Data   | Expected result                                                                                |
| 1.               | Click on dropdown in the top right corner                        |             | User should see dropdown menu                                                                  |
| 2.               | Click on “Profil regrutera” option                               |             | User should see “Profil regrutera” page                                                        |
| 3.               | Click on last name input field and enter a valid last name       | Salčin      | Entered last name is visible in the input                                                                  |
| 4.               | Click on phone number input field and enter a valid phone number | 061548965   | Entered phone number name is visible in the input                                                               |
| 5.               | Click on the button “Sačuvaj”                                    |             | The data hasn’t been successfully updated, and a popup message “Obavezno polje.” is displayed. User stays on the same page. |

****


****

Test case ID: P\_006


Module name: Profil Regrutera

Test title: **Verify that User can't change data on profile with empty last name** 

Description: Verify that User can't change data on the profile if they don’t enter a last name but enter a first name and phone number."

****

Precondition: User must be logged in

****

|                  |                                                                  |             |                                                                                              |
| ---------------- | ---------------------------------------------------------------- | ----------- | ---------------------------------------------------------------------------------------------- |
| Step no.         | Test steps                                                       | Test Data   | Expected result                                                                                |
| 1.               | Click on dropdown in the top right corner                        |             | User should see dropdown menu                                                                  |
| 2.               | Click on “Profil regrutera” option                               |             | User should see “Profil regrutera” page                                                        |
| 3.               | Click on first name input field and enter a valid first name     | Amina       | Entered first name is visible in the input                                                                |
| 4.               | Click on phone number input field and enter a valid phone number | 061548965   |Entered phone number is visible in the input                                                               |
| 5.               | Click on the button “Sačuvaj”                                    |             |The data hasn’t been successfully updated, and a popup message “Obavezno polje.” is displayed. User stays on the same page. |

****

****

Test case ID: P\_007


Module name: Profil Regrutera

Test title: **Verify that User can't change data on profile with empty phone number** 

Description: Verify that User can't change data on the profile if they don’t enter a phone number but enter a first name and last name."

****

Precondition: User must be logged in

****

|                  |                                                              |             |                                                                                             |
| ---------------- | ------------------------------------------------------------ | ------------ |---------------------------------------------------------------------------------------------- |
| Step no.         | Test steps                                                   | Test Data   | Expected result                                                                                |
| 1.               | Click on dropdown in the top right corner                    |             |User should see dropdown menu                                                                  |
| 2.               | Click on “Profil regrutera” option                           |             |User should see “Profil regrutera” page                                                        |
| 3.               | Click on first name input field and enter a valid first name | Amina       | Entered fist name is visible in the input                                                                 |
| 4.               | Click on last name input field and enter a valid last name   | Salčin      | Entered last name is visible in the input                                                                  |
| 5.               | Click on the button “Sačuvaj”                                |             |The data hasn’t been successfully updated, and a popup message “Obavezno polje.” is displayed. User stays on the same page|
