# password-generator

Password generator
In this project you will write your own password generator. Program asks the user to input password lenght. Then generate random passwords with lower case letters, upper case letters, digits and special characters. In the basic version you don't don't have to worry about whether your randomly generated password contains at least one character from every set, but you can also think about how to do it!

Hints:
Object string has builded-in constance strings you can use in your program:
string.ascii_letters # Concatenation of the ascii (upper and lowercase) letters
string.ascii_lowercase # All lower case letters
string.ascii_uppercase # All Upper case letters
string.digits  # The string ‘0123456789’.
string.punctuation  # String of ASCII characters which are considered special characters.

You can concatenated strings you need and choose a random character using:
random.choice(string_with_all_characters)
