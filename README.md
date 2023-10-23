# powerful-password-checker

This is a Python script that checks the security of passwords using the "Have I Been Pwned" (HIBP) API.

## Description

The script allows you to check whether a password has been found in a data breach. It does this by sending a partial hash of the password to the HIBP API and checking if there is a match in the database. If a match is found, it means the password has been compromised and should be changed.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

The MIT License is a permissive open-source license that allows you to use, modify, and distribute this software for both commercial and non-commercial purposes. You can find more information about the MIT License in the [LICENSE](LICENSE) file.

## Features

- Password security checking using the HIBP API.
- Secure handling of password hashes.
- Minimal dependencies, mainly using Python's standard library.

## Usage

To use this script, follow these steps:

1. Clone the repository to your local machine or download code files as zip then extract and open with a code editor.
2. Install Python if you haven't already.
3. Run the script by providing the passwords you want to check as command-line arguments. (run it on terminal/powershell/bash/cmd) as your wish! For example:

   ```bash
   python check_me.py password1 password2y6546

![Live Preview](https://github.com/iamovi/powerful-password-checker/blob/main/check_me.png)
