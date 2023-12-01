# Codsoft-Task-3
# Password Generator

# Program Explanation:

The Python program is a password generator that creates strong and secure passwords. It utilizes the `string` and `random` modules to generate a password with a mix of lowercase letters, uppercase letters, digits, and special characters.

# Functions:

1. **get_user_input():**
   - Takes user input for the desired length of the password.
   - Ensures the length is an integer and at least 5.
   - Returns the length entered by the user.

2. **generate_password(length):**
   - Creates four lists containing lowercase letters, uppercase letters, digits, and special characters.
   - Shuffles each list to introduce randomness.
   - Calculates the number of characters needed for each category based on the provided length.
   - Uses `random.sample` to randomly select characters from each list.
   - Shuffles the final result to mix characters from different categories.
   - Joins the characters to form the password.
   - Returns the generated password.

# Execution:

1. The program starts by welcoming the user to the password generator.

2. The `get_user_input` function is called to get the desired length of the password from the user.

3. The `generate_password` function is called with the obtained length to generate a strong password.

4. The generated password is printed as the output.


# Features:

- The password generator ensures a mix of lowercase and uppercase letters, digits, and special characters.
- It allows the user to specify the length of the password.
- The generated password is designed to be strong and secure.

# Screenshots

![pass1](https://github.com/Srivarthaniselvam/Codsoft-Task-3/assets/151417502/462e86e4-38fa-46f4-b0b6-227eece74a60)
![pass2](https://github.com/Srivarthaniselvam/Codsoft-Task-3/assets/151417502/d20a1a0f-3b39-4fc9-b867-e57bb728fd11)
![pass3](https://github.com/Srivarthaniselvam/Codsoft-Task-3/assets/151417502/28cdb9aa-5bad-4996-8ade-8ea9772199da)
![pass4](https://github.com/Srivarthaniselvam/Codsoft-Task-3/assets/151417502/b57b0842-18f7-44a0-925e-d47ebc7cd36d)
![pass5](https://github.com/Srivarthaniselvam/Codsoft-Task-3/assets/151417502/4d829b29-d394-4b19-b2a7-88c2c5d81521)
