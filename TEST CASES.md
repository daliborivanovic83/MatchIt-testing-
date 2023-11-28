1 Test case one (web app)

**-Test case name:  Change your profile data in the “Profil regrutera
section”**

**-Description: Verify when the user logs in and  changes data in the
“Profil regrutera”  the values are changed in  realtime and are updated
and visible**

**-Precondition**

<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 29%" />
<col style="width: 57%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>-Test steps</strong></th>
<th><strong>-Test data</strong></th>
<th><strong>-Expected result</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Log in to the matchit App</td>
<td>https://company.matchit.rs</td>
<td>User is redirected to Home page</td>
</tr>
<tr class="even">
<td>Click on “Your profile name” in the right top corner</td>
<td></td>
<td>User can see a dropdown menu containing “Profil regrutera, Profil Kompanije, Korisnicka podrska, Odjavi se buttons ”</td>
</tr>
<tr class="odd">
<td>Click on “Profil regrutera”</td>
<td>       </td>
<td>User is redirected to Uredi profil</td>
</tr>
<tr class="even">
<td>Verify “izmenite Vas profil is visible”</td>
<td></td>
<td>“Izmenite Vas profil” should be visible in the left corner</td>
</tr>
<tr class="odd">
<td>Write your name in the input “Ime” field</td>
<td>Dalibor</td>
<td>Name Dalibor is visible in the input field “Ime’</td>
</tr>
<tr class="even">
<td>Write your surname in the input “Prezime” field</td>
<td>Ivanovic</td>
<td>Name Ivanovic is visible in the input field “Prezime’</td>
</tr>
<tr class="odd">
<td>Write your Phone number iin the input “Kontakt telefon” field</td>
<td>0601234567</td>
<td>Phone number 0601234567 is visible in the input field “Kontakt telefon”’</td>
</tr>
<tr class="even">
<td>Click on “Sacuvaj” button</td>
<td></td>
<td><p>Users profile information should be sent through a network API POST request </p>
<p>Message “Tvoj profil je uspesno izmenjen” should be visible</p></td>
</tr>
<tr class="odd">
<td><p>Click on the button shown </p>
<p>“Vrati na sve oglase” </p>
<p>Top right corner beside the company logo</p></td>
<td><p><a href="https://company.matchit.rs"><u>https://company.matchit.rs</u></a></p>
<p>This page is loaded</p></td>
<td>Name in the profile is updated</td>
</tr>
<tr class="even">
<td>Go to Home page, go to Your profile name in the right top corner</td>
<td></td>
<td><p><img src="media/image1.png" style="width:3.5in;height:1.77083in" /></p>
<p>New data is visible</p></td>
</tr>
</tbody>
</table>

2 Test case two (web app) 

**-Test case name: Verify new candidate is added to     MatchIT deck 
and all values are shown    **

**-Description: Verify when the user logs in and  goes to Oglasi/Deck
Kandidata the candidate in the deck is added to matchIt deck**

**-Precondition advertisement is shown and the matches are made**

<table>
<colgroup>
<col style="width: 34%" />
<col style="width: 37%" />
<col style="width: 27%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>-Test steps</strong></th>
<th><strong>-Test data</strong></th>
<th><strong>-Expected result</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Log in to the matchit App</td>
<td>https://company.matchit.rs</td>
<td>User is redirected to Home page</td>
</tr>
<tr class="even">
<td>Click on Svi oglasi button</td>
<td>  …….       </td>
<td>User is redirected to Oglasi section</td>
</tr>
<tr class="odd">
<td>Go to row Entry level android developer click on Deck kandidata button</td>
<td>https://company.matchit.rs/job-offers/18/deck</td>
<td>User is redirected to Entry level Android developer - Deck</td>
</tr>
<tr class="even">
<td><p>Verify that  “Entry level Android developer - Deck</p>
<p>” is visible</p></td>
<td></td>
<td><p><strong>“</strong>Entry level Android developer - Deck</p>
<p><strong>”</strong> is visible and Rijalda as name of the candidate is visible</p></td>
</tr>
<tr class="odd">
<td>Verify that  “Vestine i bedzevi” is visible</td>
<td></td>
<td>Kandidat jos uvek nije uneo vestine i bedzeve</td>
</tr>
<tr class="even">
<td><p>Verify that  “Zeljeni nacin rada</p>
<p>” is visible</p></td>
<td></td>
<td>“Remote”</td>
</tr>
<tr class="odd">
<td><p>Verify that  “Iskustvo</p>
<p>” is visible</p></td>
<td></td>
<td><p>Java 2;</p>
<p>Android 2;</p>
<p>Kotlin 2;</p>
<p>KMM 2;</p></td>
</tr>
<tr class="even">
<td>Verify that “ Tehnologije, Benefit, Plata” percentage is visible</td>
<td></td>
<td><p>Tehnologije 83%;</p>
<p>Benefit 100%</p>
<p>Plata ok</p></td>
</tr>
<tr class="odd">
<td>Verify that “ Benefiti” is visible</td>
<td></td>
<td><p>13 plata;</p>
<p>Neogranicen godisnji odmor;</p></td>
</tr>
<tr class="even">
<td>Verify that “ Obrazovanje”  is visible</td>
<td></td>
<td>Kandidat jos uvek nije uneo obrazovanje</td>
</tr>
<tr class="odd">
<td>Verify that “Sertifikati” is visible</td>
<td></td>
<td>Kandidat jos uvek nije uneo sertifikate</td>
</tr>
<tr class="even">
<td>Click the cancel button</td>
<td></td>
<td>Another candidate is shown from the deck</td>
</tr>
<tr class="odd">
<td>Click on the ok button</td>
<td></td>
<td>Current cadidate is added to Matches deck</td>
</tr>
</tbody>
</table>

3 Test case three (web app)

**-Test case name: Verify that the new job position is opened in “svi
oglasi section**

**-Description: **

**-Precondition**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 41%" />
<col style="width: 32%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>-Test steps</strong></th>
<th><strong>-Test data</strong></th>
<th><strong>-Expected result</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Log in to the matchit Ap</td>
<td>https://company.matchit.rs</td>
<td>User is redirected to Home page</td>
</tr>
<tr class="even">
<td>Click on Svi oglasi button</td>
<td>https://company.matchit.rs/job-offers</td>
<td>User is redirected to Oglasi section</td>
</tr>
<tr class="odd">
<td>Click on Dodaj novi oglas</td>
<td>https://company.matchit.rs/job-offers/create</td>
<td>User is redirected to Kreiraj novi oglas section</td>
</tr>
<tr class="even">
<td>Verify that “Kreiranje oglasa iz visible</td>
<td></td>
<td>User can see the headline of the section Kreiranje oglasa</td>
</tr>
<tr class="odd">
<td>Fill in the input field naziv pozicije</td>
<td><p><strong>Junior front end web developer</strong></p>
<p><strong> </strong></p></td>
<td>Users should only be able to enter text in the “naziv pozicije” field </td>
</tr>
<tr class="even">
<td>Select your technology in the “Tehnologije” section </td>
<td><strong>Angular JS</strong></td>
<td>Angular JS should be visible in the “Tehnologije “ input field</td>
</tr>
<tr class="odd">
<td>Select the number in “Godine iskustva</td>
<td><strong>&lt;1</strong></td>
<td>&lt;1 years of experience should be visible in in “Godine iskustva” field</td>
</tr>
<tr class="even">
<td>Select “Naziv projekta” input field</td>
<td><strong>True: junior front end developer</strong></td>
<td>Name of the project should be visible and it shoudl contain “Junior front end developer”</td>
</tr>
<tr class="odd">
<td>Select “O projektu” input field</td>
<td><strong>Platforma za spajanje firmi sa potencijalnim kandidatima</strong></td>
<td>Match it projekat should be visible</td>
</tr>
<tr class="even">
<td>Select“Broj clanova tima” input field</td>
<td><strong>1000   </strong></td>
<td>Number 1000 should be visible in the “Broj clanova tima” input field</td>
</tr>
<tr class="odd">
<td>Select “Industrija” input field</td>
<td><strong>Gaming</strong></td>
<td>Gaming should be visible in the “Industrija” input field</td>
</tr>
<tr class="even">
<td>Go to “Tip projekta” select Enterprise</td>
<td><p><strong>Enterprise is checked</strong></p>
<p><strong> </strong></p></td>
<td>Only Enterprise checkbox should be checked in the check box</td>
</tr>
<tr class="odd">
<td>Go to “nacin razvoja projekta” select In house</td>
<td><strong>In house is checked</strong></td>
<td>Only In house should be checked in the check box</td>
</tr>
<tr class="even">
<td>Go to “Lokacija” choose Drzava select Srbija</td>
<td><strong>Srbija is selected</strong></td>
<td>Srbija is displayed in the input field</td>
</tr>
<tr class="odd">
<td>Go to “Lokacija” choose Grad select Beograd</td>
<td><strong>Select Beograd</strong></td>
<td>Beograd is shown in the input field</td>
</tr>
<tr class="even">
<td>Go to Benefiti in the first input field choose </td>
<td><p><strong>True 13.plata </strong></p>
<p><strong>False choose 13.plata again</strong></p></td>
<td>13.plata should be visible in the first input field</td>
</tr>
<tr class="odd">
<td>Go to “nacini rada” choose Office, Remote, Hybrid</td>
<td><strong>Office, Remote, Hybrid </strong></td>
<td>Office, Remote, Hybrid checkboxes are visible and checked</td>
</tr>
<tr class="even">
<td>Go to neto plata u eur input amount in “Min” input field</td>
<td><p><strong>True: integer 100 </strong></p>
<p><strong>False: decimal number</strong></p>
<p><strong>False: negative number</strong></p></td>
<td>100 Should be visible in the input field</td>
</tr>
<tr class="odd">
<td>Go to neto plata u eur input amount in “Max” input field</td>
<td><p><strong>True: integer bigger then 200</strong></p>
<p><strong>False: decimal number</strong></p>
<p><strong>False: negative number</strong></p></td>
<td>200  should be shown in the input field</td>
</tr>
<tr class="even">
<td>Go to checkbox “prikazi platu” click on the checkbox</td>
<td></td>
<td>Checkbox “prikazi platu” is checked</td>
</tr>
<tr class="odd">
<td>Go to “Kreiraj” click the button</td>
<td></td>
<td><p>“Oglas je uspešno kreiran.</p>
<p>”  should be visible    </p></td>
</tr>
<tr class="even">
<td>Click on “Vrati me na sve oglase”</td>
<td></td>
<td>Home page is visible</td>
</tr>
<tr class="odd">
<td>Go to “Svi oglasi section”</td>
<td></td>
<td>New position “<strong>Junior front end web developer</strong>” is visible</td>
</tr>
</tbody>
</table>

4Test case four (web app)

**-Test case name: Verify that the empty Form “Vasi Podaci” cannot be
submitted**

**-Description: Verify that when the user in the “Uredi profil” section
leaves all the inputs empty the fprm cannot be submitted**

**-Precondition**

 

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 40%" />
<col style="width: 39%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>-Test steps</strong></th>
<th><strong>-Test data</strong></th>
<th><strong>-Expected result</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Log in to the matchit App</td>
<td>https://company.matchit.rs</td>
<td>User is redirected to Home page</td>
</tr>
<tr class="even">
<td>Click on “Your profile name” in the right top corner</td>
<td></td>
<td>User can see a dropdown menu containing “Profil regrutera, Profil Kompanije, Korisnicka podrska, Odjavi se buttons ”</td>
</tr>
<tr class="odd">
<td>Click on “Profil regrutera”</td>
<td>https://company.matchit.rs/me/profile</td>
<td>User is redirected to Uredi profil</td>
</tr>
<tr class="even">
<td>Confirm that “Izmenite Vas profil is visible”</td>
<td></td>
<td>“Izmenite Vas profil” headline is visible</td>
</tr>
<tr class="odd">
<td>Go to “Ime” input field </td>
<td></td>
<td>“Ime” input field is empty</td>
</tr>
<tr class="even">
<td>Go to “Prezime” input field </td>
<td></td>
<td>“Prezime” input field is empty</td>
</tr>
<tr class="odd">
<td>Go to “Email” input field </td>
<td></td>
<td>“Email” input field is empty</td>
</tr>
<tr class="even">
<td>Go to “Kontakt telefon” input field </td>
<td></td>
<td>“Kontakt telefon” is empty</td>
</tr>
<tr class="odd">
<td>Go to “Sacuvaj” button then click</td>
<td></td>
<td><p>“Error msg uneti podaci su neispravni” in the form of a modal is visible, all input fields should have warning text “Molimo Vas popunite prazna polja”</p>
<p>Users stay on the same page. </p></td>
</tr>
</tbody>
</table>

5.1 Test case five (web app)

**-Test case name: Verify that input fields with different types data in
the  form cannot be submitted**

**-Description: Verify that when the user in the “Uredi profil” and 
“Prezime” section fills in   an input “Ime”,with text data and
everything else is empty the form cannot be submitted**

**-Precondition**

 

| **-Test steps**                                      | **-Test data**                        | **-Expected result**                                                                                                 |
|------------------------------------------------------|---------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| Log in to the matchit App                            | https://company.matchit.rs            | User is redirected to Home page                                                                                      |
| Click on “Your profile name” in the right top corner |                                       | User can see a dropdown menu containing “Profil regrutera, Profil Kompanije, Korisnicka podrska, Odjavi se buttons ” |
| Click on “Profil regrutera”                          | https://company.matchit.rs/me/profile | User is redirected to Uredi profil                                                                                   |
| Confirm that “Izmenite Vas profil is visible”        |                                       | “Izmenite Vas profil” headline is visible                                                                            |
| Go to “Ime” input data                               | Dalibor                               | “Ime” input field is visible and shows “Dalibor”                                                                     |
| Go to “Sacuvaj” button then click                    | /                                     | Error msg “Popunite sva polja ”                                                                                      |

5.2 Test case five (web app)

**--Test case name: Verify that input fields with different types data
in the  form cannot be submitted**

**-Description: Verify that when the user in the “Uredi profil” and 
“Prezime” section fills in   an input “Ime” and “Prezime”,with text data
and everything else is empty the form cannot be submitted**

**-Precondition**

| **-Test steps**                                      | **-Test data**                        | **-Expected result**                                                                                                 |
|------------------------------------------------------|---------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| Log in to the matchit App                            | https://company.matchit.rs            | User is redirected to Home page                                                                                      |
| Click on “Your profile name” in the right top corner |                                       | User can see a dropdown menu containing “Profil regrutera, Profil Kompanije, Korisnicka podrska, Odjavi se buttons ” |
| Click on “Profil regrutera”                          | https://company.matchit.rs/me/profile | User is redirected to Uredi profil                                                                                   |
| Confirm that “Izmenite Vas profil is visible”        |                                       | “Izmenite Vas profil” headline is visible                                                                            |
| Go to “Ime” input data                               | Dalibor                               | “Ime” input field is visible and shows “Dalibor”                                                                     |
| Go to “Prezime” input data                           | Ivanovic                              | “Prezime” input field is visible and shows “Ivanovic                                                                 |
| Go to “Sacuvaj” button then click                    | /                                     | Error msg “Popunite sva polja ”                                                                                      |

**5.3 Test case five (web app)**

**-Test case name: Verify that input fields with different types data in
the  form cannot be submitted**

**-Description: Verify that when the user in the “Uredi profil” and 
“Prezime” section fills in   an input “Ime” and “Prezime” and
“email”,with proper data type and everything else is empty the form
cannot be submitted**

**-Precondition**

| **-Test steps**                                      | **-Test data**                        | **-Expected result**                                                                                                 |
|------------------------------------------------------|---------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| Log in to the matchit App                            | https://company.matchit.rs            | User is redirected to Home page                                                                                      |
| Click on “Your profile name” in the right top corner |                                       | User can see a dropdown menu containing “Profil regrutera, Profil Kompanije, Korisnicka podrska, Odjavi se buttons ” |
| Click on “Profil regrutera”                          | https://company.matchit.rs/me/profile | User is redirected to Uredi profil                                                                                   |
| Confirm that “Izmenite Vas profil is visible”        |                                       | “Izmenite Vas profil” headline is visible                                                                            |
| Go to “Ime” input data                               | Dalibor                               | “Ime” input field is visible and shows “Dalibor”                                                                     |
| Go to “Prezime” input data                           | Ivanovic                              | “Prezime” input field is visible and shows “Ivanovic                                                                 |
| Go to “Email” input data                             | dalibor@gmail.com                     | “Email” input field is visible and shows dalibor@gmail.com                                                           |
| Go to “Sacuvaj” button then click                    | /                                     | Error msg “Uneti podaci neispravni”                                                                                  |

**5.4 Test case five (web app)**

**-Test case name: Verify that input fields with different types data in
the  form cannot be submitted**

**-Description: Verify that when the user in the “Uredi profil” and 
“Prezime” section fills in   an input “Ime” and “Prezime” and
“Email”,with proper data type and “Kontakt telefon” with textual data 
and everything else is empty the form cannot be submitted**

**-Precondition**

| **-Test steps**                                      | **-Test data**                        | **-Expected result**                                                                                                 |
|------------------------------------------------------|---------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| Log in to the matchit App                            | https://company.matchit.rs            | User is redirected to Home page                                                                                      |
| Click on “Your profile name” in the right top corner |                                       | User can see a dropdown menu containing “Profil regrutera, Profil Kompanije, Korisnicka podrska, Odjavi se buttons ” |
| Click on “Profil regrutera”                          | https://company.matchit.rs/me/profile | User is redirected to Uredi profil                                                                                   |
| Confirm that “Izmenite Vas profil is visible”        |                                       | “Izmenite Vas profil” headline is visible                                                                            |
| Go to “Ime” input data                               | Dalibor                               | “Ime” input field is visible and shows “Dalibor”                                                                     |
| Go to “Prezime” input data                           | Ivanovic                              | “Prezime” input field is visible and shows “Ivanovic                                                                 |
| Go to “Email” input data                             | dalibor@gmail.com                     | “Email” input field is visible and shows dalibor@gmail.com                                                           |
| Go to “Kontakt telefon” input data                   | dalibor                               | ““Kontakt telefon” input field is visible and shows an error msg “popunite polje u ispravnom formatu”                |
| Go to “Sacuvaj” button then click                    | /                                     | Error msg “Uneti podaci neispravni”                                                                                  |

5.5 test case five (web app)

**5.5 Test case five (web app)**

**-Test case name: Verify that input fields with different types data in
the  form cannot be submitted**

**-Description: Verify that when the user in the “Uredi profil” and 
“Prezime” section fills in   an input “Ime” and “Prezime” and “Kontakt
emaik”,with proper data type and “Email” with data containing numbers 
the form cannot be submitted**

**-Precondition**

| **-Test steps**                                      | **-Test data**                        | **-Expected result**                                                                                                 |
|------------------------------------------------------|---------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| Log in to the matchit App                            | https://company.matchit.rs            | User is redirected to Home page                                                                                      |
| Click on “Your profile name” in the right top corner |                                       | User can see a dropdown menu containing “Profil regrutera, Profil Kompanije, Korisnicka podrska, Odjavi se buttons ” |
| Click on “Profil regrutera”                          | https://company.matchit.rs/me/profile | User is redirected to Uredi profil                                                                                   |
| Confirm that “Izmenite Vas profil is visible”        |                                       | “Izmenite Vas profil” headline is visible                                                                            |
| Go to “Ime” input data                               | Dalibor                               | “Ime” input field is visible and shows “Dalibor”                                                                     |
| Go to “Prezime” input data                           | Ivanovic                              | “Prezime” input field is visible and shows “Ivanovic                                                                 |
| Go to “Email” input data                             | +38160761446                          | Error msg is visible“uneti podaci nisu ispravni”                                                                     |
| Go to “Kontakt telefon” input data                   | +38160761446                          | ““Kontakt telefon” input field is visible and shows “+38160761446”                                                   |
| Go to “Sacuvaj” button then click                    | /                                     | Error msg “Uneti podaci neispravni”                                                                                  |

**5.6 Test case name: Verify that input fields with different types data
in the  form cannot be submitted**

**-Description: Verify that when the user in the “Uredi profil” and 
“Prezime” section fills in  input “Prezime”, with numbers, the form
cannot be submitted, because the usage numbers only or special
characters only is not allowed in the “Prezime”,  input field**

**-Precondition**

| **-Test steps**                                      | **-Test data**                        | **-Expected result**                                                                                                 |
|------------------------------------------------------|---------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| Log in to the matchit App                            | https://company.matchit.rs            | User is redirected to Home page                                                                                      |
| Click on “Your profile name” in the right top corner |                                       | User can see a dropdown menu containing “Profil regrutera, Profil Kompanije, Korisnicka podrska, Odjavi se buttons ” |
| Click on “Profil regrutera”                          | https://company.matchit.rs/me/profile | User is redirected to Uredi profil                                                                                   |
| Confirm that “Izmenite Vas profil is visible”        |                                       | “Izmenite Vas profil” headline is visible                                                                            |
| Go to “Ime” input data                               | Dalibor                               | Ime is visible and it contains “Dalibor ”                                                                            |
| Go to “Prezime” input data                           | 1983                                  | Error msg “Uneti podaci neispravn                                                                                    |
| Go to “Email” input data                             | daliborivanovic83@gmail.com           | “Email” input field is visible and shows  “daliborivanovic83@gmail.com”                                              |
| Go to “Kontakt telefon” input data                   | 00381641111111 or +3816411111111      | “Kontakt telefon” is visible and shows 00381641111111  or +3816411111111                                             |
| Go to “Sacuvaj” button then click                    | /                                     | “Error msg “Uneti podaci neispravni”                                                                                 |

6 Test case (mobile app )

**-Test case name: Verify that input fields with different types data in
the  form cannot be submitted**

**-Description: Verify that when the user in the “Uredi profil” and 
“Prezime” section fills in  inputs such as “Ime” with correct data type
and “Prezime” with numbers the form cannot be submitted **

**-Precondition**

<table>
<colgroup>
<col style="width: 53%" />
<col style="width: 12%" />
<col style="width: 34%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>-Test steps</strong></th>
<th><strong>-Test data</strong></th>
<th><strong>-Expected result</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Log in to the matchit web App</td>
<td></td>
<td>User is redirected to home page</td>
</tr>
<tr class="even">
<td>Go to Profil </td>
<td></td>
<td>User is redirected to Profile page</td>
</tr>
<tr class="odd">
<td>Go to Osnovni podaci</td>
<td></td>
<td>User is redirected to Podaci page</td>
</tr>
<tr class="even">
<td>Confirm that Ime input filed is visible, type in the following information</td>
<td>“Dalibor”</td>
<td>Input field is visible and contains “Dalibor”</td>
</tr>
<tr class="odd">
<td><p>Confirm that Prezime input field is visible:</p>
<p>type in the following information</p></td>
<td>“12345”</td>
<td>Error msg “uneti podaci su neispravni”</td>
</tr>
</tbody>
</table>

6.1 Test case (mobile app )

**-Test case name: Verify that input fields with different types data in
the  form cannot be submitted**

**-Description: Verify that when the user in the “Uredi profil” and 
“Prezime” section fills in  inputs such as “Prezime” with correct data
type and “Ime” with numbers the form cannot be submitted **

**-Precondition**

<table>
<colgroup>
<col style="width: 52%" />
<col style="width: 12%" />
<col style="width: 34%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>-Test steps</strong></th>
<th><strong>-Test data</strong></th>
<th><strong>-Expected result</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Log in to the matchit web App</td>
<td></td>
<td>User is redirected to home page</td>
</tr>
<tr class="even">
<td>Go to Profil </td>
<td></td>
<td>User is redirected to Profile page</td>
</tr>
<tr class="odd">
<td>Go to Osnovni podaci</td>
<td></td>
<td>User is redirected to Podaci page</td>
</tr>
<tr class="even">
<td>Confirm that Ime input filed is visible, type in the following information</td>
<td>“12345”</td>
<td>Error msg “uneti podaci su neispravni”</td>
</tr>
<tr class="odd">
<td><p>Confirm that Prezime input field is visible:</p>
<p>type in the following information</p></td>
<td>“Ivanovic”</td>
<td>Input field is visible and contains “Ivanovic”</td>
</tr>
</tbody>
</table>
