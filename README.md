# Active Directory Command Scripts

This repository contains a collection of PowerShell scripts for managing and querying Active Directory (AD). The scripts are organized into individual `.txt` files, each containing specific AD-related commands that can be used for various administrative tasks, such as retrieving user information, managing groups, and performing other Active Directory operations.

## Repository Contents

The repository includes the following files:

- **AccountExpires.txt**: Scripts for chcek user accounts expires in Active Directory.
- **DL-Query.txt**: Scripts for managing groups in Active Directory.
- **Enable-Disable-Status-CMD.txt**: Script for chcek account Status.
- **Inactive users.txt**: Scripts to check the status of users based on custom criteria.

## Usage

1. **Clone this repository**:
   To get started, clone this repository to your local machine using the following command:
   ```bash
   git clone [https://github.com/yourusername/AD-Command-Scripts.git](https://github.com/Akashgowda-hub/AD.git)


2. Review individual script files: Each .txt file contains one or more PowerShell commands. You can open these files using any text editor to review and modify the commands as needed.

3. Prerequisites:
The script assumes you have the necessary permissions to run Active Directory commands.
Ensure that the Active Directory PowerShell module is installed and imported:

Import-Module ActiveDirectory

4. Customization: Feel free to modify any script to fit your specific Active Directory environment or use case. Each script is designed to be modular and can be adapted to meet your needs.

5. Contributing
If you have any useful Active Directory scripts that you would like to contribute, feel free to fork the repository and submit a pull request. Contributions are welcome!

6. License
This repository is licensed under the MIT License. See the LICENSE file for more information.

7. Disclaimer
These scripts are provided "as is" without any warranty. Always test scripts in a non-production environment before deploying them to your live systems.