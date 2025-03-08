# TestCase-Sample 1:
Check if the login works when a user enters the correct credentials.

## Steps to reproduce:

1. Go to login page on emag.ro

2. Click Contul meu button

3. Enter a valid username or e-mail in the appropiate field

4. Click on the Continua button

5. Enter a valid password in the appropiate field

6. Click the "Login" button

## Expected Result:

The user is successfully logged in and redirected to the main account page or the desired page.

## Test Data:

User: emag1234@gmail.com

Password: qwerty1234


# TestCase-Sample 2:

Check if the login shows an error when writing the wrong credentials.

 
## Steps to reproduce:

1. Go to login page on emag.ro

2. Press the "Contul meu" button

3. Enter a valid e-mail

4. Click the "Continua" button

5. Enter a incorrect password

## Expected Result:

The system displays an error message ("Ai introdus greșit parola sau adresa de email. Te rugăm completează din nou.") and does not allow login.


## Test Data:

Username: terible.child@gmail.com

Password:qwe123


# TestCase-Sample 3:

Check what happens if you do not introduce the correct credentials.


## Steps to reproduce:

1. Go to the login page on emag.ro

2. Press "Contul meu" button

3. Leave the e-mail field empty

4. Click the "Continua" button

## Expected Result:

The system displays an error message ("Camp obligatoriu") indicating that the user must fill in the required fields.



# TestCase-Sample 4:

Check if the item you are looking for will be shown as a result when you write it in the search bar.


## Steps to reproduce:

1. Go to the page emag.ro

2. Enter a valid search term (e.g., "laptop") in the search bar

3.Click the search button or press enter

## Expected Result:

A list of relevant products for the searched term (e.g., laptops) is displayed on the page.


# TestCase-Sample 5:

Check if autocomplet works after the user has entered a few characters.


## Steps to reproduce:

1. Go to the page emag.ro

2. Start typing a partial search term (e.g., "tele" for "telefon")

3. After four characters, a list of suggestions appears in a dropdown

4. Select a term from the suggestions list or continue typing to complete the desired term

## Expected Result:

The autocomplete suggestions are relevant and accurate. For example, typing "tele" should show suggestions like "telefon", "televizor", etc. The search should then return relevant results.

