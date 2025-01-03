### ATM System Description

This program simulates an **ATM system** that allows users to perform various banking operations. It is a command-line-based application that enables users to interact with their bank accounts for performing transactions such as checking balance, withdrawing money, depositing money, and updating personal information. 

#### **Key Features:**

1. **Account Creation:**
   - New users can create a bank account by providing details like account number, name, PIN, initial deposit amount, mobile number, and date of birth.
   - The system checks if the account number already exists before allowing the user to proceed.

2. **Login:**
   - Users can log into their account by entering their account number and PIN. The program authenticates the user based on these details.

3. **Transaction Options:**
   After a successful login, users can:
   - **Check Balance:** View the current account balance.
   - **Withdraw Money:** Withdraw funds from the account (if the balance is sufficient).
   - **Deposit Money:** Deposit a specified amount into the account.
   - **Change PIN:** Update the account PIN for added security.
   - **View Profile:** View the user’s profile, including their account details.
   - **Update Profile:** Modify user details such as name, mobile number, or date of birth.

4. **Data Persistence:**
   - The program saves user data to a file (`UserDatabase.txt`) to persist information across sessions. User details are loaded from this file at the start of the program and saved back after any changes.

5. **Color-Coded Console Output:**
   - The program uses ANSI escape codes to display messages in different colors, providing a clear distinction between success, error, warnings, and user prompts.

6. **Security:**
   - Each transaction (such as withdrawing funds or changing the PIN) requires the user to enter their PIN for verification. If the PIN is incorrect, an error message is displayed.

7. **Exit Option:**
   - Users can log out and exit the system, with all changes saved before exiting.

#### **Usage:**
1. **Create a new account** by choosing the option from the main menu.
2. **Login** using your account number and PIN.
3. Perform transactions such as checking balance, withdrawing money, or depositing funds.
4. Update your profile or change your PIN for enhanced security.
5. **Logout** when finished, and the system will save your data for the next session.

#### **Technologies Used:**
- **C++:** For implementing the ATM functionality and user interface.
- **File Handling:** Used to persist user data in a text file (`UserDatabase.txt`).

#### **File Structure:**
- `UserDatabase.txt`: Stores user data in CSV format (Account No, Name, PIN, Balance, Mobile No, DOB).

This program is an excellent starting point for learning how to implement basic banking operations in C++, including file handling, object-oriented programming, and handling user input.

---

Feel free to customize, enhance, and use this program for educational or practical purposes!
