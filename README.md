# OTP-Verification-System

## Project Overview
The OTP Verification System is a Python-based application designed to enhance user authentication by generating and validating One-Time Passwords (OTPs) via email. It ensures secure access to sensitive information or actions with a focus on simplicity, reliability, and security.

### Project Structure:
The project consists of two main components: the backend logic and the graphical user interface (GUI). The backend logic handles OTP generation, email sending, and OTP verification, while the GUI provides a user-friendly interface for interacting with the system. Refer below file
- Backend components : `OTPverify_Backend.py` 
- GUI components : `OTPverify_GUI.py`

### Methodologies and Tools
- **Tools:** Python, PyQt5, Tkinter, Smtplib
- **Methodologies:** Secure OTP generation, Email communication protocols

## Components and Functionality
### `OTPverify_Backend.py`
#### OTPVerifyFeatureBackend Class:
- Handles OTP generation, email sending, and verification.
- Methods:
  - `generate_otp(self)`: Generates a 6-digit OTP using random integers.
  - `verify_email(self, email)`: Validates email format using regex.
  - `send_otp(self, email)`: Sends OTP via SMTP and returns success status.
  - `prompt_for_otp(self)`: Prompts user for OTP input.
  - `verify_otp(self, generated_otp, entered_otp)`: Compares entered OTP with generated OTP.
- Main Function (`if __name__ == '__main__'`):
  - Provides testing functionality for OTP features.

#### OTPVerification Class
- Acts as an interface between GUI and backend.
- Methods:
  - `__init__(self)`: Initializes OTPVerification.
  - `send_otp(self, email)`: Initiates OTP sending.
  - `verify_otp(self, generated_otp, entered_otp)`: Verifies entered OTP.

### OTPverify_GUI.py
#### OTPVerifyGUI Class:
- Implements GUI using PyQt5 for OTP verification.
- Initializes GUI components and handles user interactions.
- Methods:
  - `send_otp_button(self)`: Validates email and sends OTP.
  - `verify_otp_button(self)`: Verifies entered OTP.
- Features:
  - GUI setup: Window title, layout, styling.
  - Input fields: Email and OTP.
  - Buttons: Send OTP, Verify OTP.
  - Status messages: Updates on send and verify actions.
#### Main Function (`if __name__ == '__main__'`):
- Initializes and displays OTP verification GUI.

## Visuals
N/A

## Documentation
- **Usage:**
1. Run the OTPVerifyGUI.py script to launch the OTP Verification System.
2. Enter your email address in the provided input field and click the "Send OTP" button.
3. Check your email inbox for the OTP sent by the system.
4. Enter the received OTP in the OTP input field and click the "Verify OTP" button.
5. If the entered OTP is valid, access will be granted; otherwise, access will be denied.
   
- **How to Run the Program:**
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run the Python script `OTPverify_Backend.py`
4. After successfull execution of `OTPverify_Backend.py` execute the `OTPverify_GUI.py`
5. Follow the prompts to generate, send, and verify the OTP.

- **Test Cases:**
1. **Valid Email Address**: Verify that the system accepts valid email addresses for OTP delivery.
2. **Invalid Email Address**: Verify that the system rejects invalid email addresses and prompts the user to enter a valid one.
3. **Successful OTP Generation**: Verify that the system successfully generates a 6-digit OTP and sends it to the user's email address.
4. **Invalid OTP Entry**: Verify that the system prompts the user to enter a valid OTP if the entered OTP is incorrect.
5. **OTP Verification**: Verify that the system correctly verifies the entered OTP and grants access if it matches the generated OTP. 

### Dependencies & Libraries
- Python 3.x
- Smtplib
- PyQt5
- Tkinter
- Re
- Random
- Sys

## Contributions and Achievements
As the project developer, I played a key role in implementing robust OTP generation, email sending, and verification functionalities. I also designed and integrated a user-friendly GUI using PyQt5 for seamless user interaction.

1. **Functionality Implementation:**
   - Successfully implemented and verified OTP generation, sending, and verification processes, ensuring accuracy and reliability.   
2. **Code Quality and Documentation:**
   - Maintained high code quality by adhering to Python best practices, ensuring readability and maintainability.
   - Provided comprehensive documentation for easy understanding and future reference.
3. **Error Handling and User Interaction:**
   - Implemented robust error handling mechanisms to gracefully manage invalid inputs and errors.
   - Designed clear and user-friendly prompts to enhance interaction with the system.
4. **Testing and Resilience:**
   - Conducted thorough testing under various scenarios to ensure robustness and reliability.
   - Addressed edge cases and potential issues to enhance system resilience.
5. **GUI Design:**
   - Designed and implemented a creative and user-friendly GUI interface using PyQt5.
   - Enhanced user experience through intuitive design and interaction.

### Tags
Python, GUI, OTP Generation, Email Verification, Security, Software Development

