Password Generator Class

The PasswordGenerator class is a Java program that generates strong and unique passwords based on user input.

Methods

main(String[] args)

The main method is the entry point of the program. It displays a menu to the user and allows them to select an option.

printMenu()

The printMenu method displays the menu options to the user.

requestPassword()

The requestPassword method prompts the user to select the character types to include in the password (lowercase letters, uppercase letters, numbers, and symbols) and then generates a password of the specified length.

generatePassword(boolean includeLower, boolean includeUpper, boolean includeNum, boolean includeSym, int length)

The generatePassword method generates a password based on the selected character types and length.

checkPassword(String password)

The checkPassword method checks if a password is valid (i.e., at least 8 characters long).

printUsefulInfo()

The printUsefulInfo method displays useful information about passwords.

printQuitMessage()

The printQuitMessage method displays a goodbye message when the user quits the program.

Variables

IncludeLower

A boolean variable that indicates whether to include lowercase letters in the password.

IncludeUpper

A boolean variable that indicates whether to include uppercase letters in the password.

IncludeNum

A boolean variable that indicates whether to include numbers in the password.

IncludeSym

A boolean variable that indicates whether to include symbols in the password.

length

An integer variable that represents the length of the password.

input

A string variable that stores the user's input.

keyboard

A Scanner object that reads input from the user.

password

A string variable that stores the generated password.

Error Handling

The PasswordRequestError method is used to handle invalid input for the password request.

Example Usage

To use the Password Generator, simply run the program and follow the prompts. For example:

Hello, welcome to the Password Generator :)

Do you want to include lowercase letters in your password? (yes/no) yes

Do you want to include uppercase letters in your password? (yes/no) yes

Do you want to include numbers in your password? (yes/no) yes

Do you want to include symbols in your password? (yes/no) yes

Great! Now enter the length of the password 12

Your generated password is: G#8dL4aP9eJ
