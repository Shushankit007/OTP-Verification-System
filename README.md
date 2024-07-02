# OTP-Verification-System

## Project Overview
The OTP Verification System is a Python-based application designed to enhance user authentication by generating and validating One-Time Passwords (OTPs) via email. It ensures secure access to sensitive information or actions with a focus on simplicity, reliability, and security.

## Project Structure:
The project consists of two main components: the backend logic and the graphical user interface (GUI). The backend logic handles OTP generation, email sending, and OTP verification, while the GUI provides a user-friendly interface for interacting with the system. Refer below file
- Backend components : `OTPverify_Backend.py` 
- GUI components : `OTPverify_GUI.py`

## Methodologies and Tools
- **Tools:** Python, PyQt5, Tkinter, Smtplib
- **Methodologies:** Secure OTP generation, Email communication protocols

## Documentation
This section provides a summary of the project's methods and functionality. For detailed descriptions, refer to the comprehensive documentation available in the attached Word document (`OTP_Project_documentation.docx`).

### **Components and Functionality:**

### `OTPverify_Backend.py`

**OTPVerifyFeatureBackend Class:**
- Manages OTP generation, email sending, and verification.
- Methods: `generate_otp`, `verify_email`, `send_otp`, `prompt_for_otp`, `verify_otp`.
**Main Function (`if __name__ == '__main__'`):**
- Provides testing functionality for OTP features.
  
**OTPVerification Class:**
- Acts as an interface between GUI and backend.
- Methods: `send_otp`, `verify_otp`.

### `OTPverify_GUI.py`

**OTPVerifyGUI Class:**
- Implements PyQt5-based GUI for OTP operations.
- Methods: `send_otp_button`, `verify_otp_button`.
**Main Function (`if __name__ == '__main__'`):**
- Initializes and displays OTP verification GUI.

### Dependencies & Libraries
- Python 3.x
- Smtplib
- PyQt5
- Tkinter
- Re
- Random
- Sys

### How to Run the Program:
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run the Python script `OTPverify_Backend.py`
4. After successfull execution of `OTPverify_Backend.py` execute the `OTPverify_GUI.py`
5. Follow the prompts to generate, send, and verify the OTP.


## Visuals
N/A


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

