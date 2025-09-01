# PBL: Hiree-Hirer Management System 👩‍💻👨‍💼

This is a C-based project that provides a simple platform to connect **Hirees** (people looking for work) with **Hirers** (people offering jobs).  

The program manages registration, login, and skill-based filtering of applicants, making it easier for employers to find workers with specific skill sets.

---

## Features
- **Hiree**
  - Register with name, age, gender, phone number, and skill set.
  - Login using Name, ID, and Phone Number.
  - View personal details after login.
  - Skills supported: Driving, Cooking, Construction, Cleaning, Beautician, or custom skills.

- **Hirer**
  - Register with name, age, email, and password.
  - Login with email and password.
  - View account details.
  - Search applicants by skill and get their contact details.

---

## Technologies Used
- **Language**: C
- **File Handling**: Used for storing applicant (`hiree.txt`) and employer (`hirer.txt`) details.
- **Random ID Generator**: Generates unique IDs for applicants.
- **Standard Libraries**: `stdio.h`, `stdlib.h`, `string.h`, `time.h`

---

## Project Structure
PBL-main/
│── Emp.c # Main program
│── file_edition.c # File editing logic (if used)
│── gui.c # GUI-related code (future scope)
│── hiree.txt # Stores hiree data
│── hirer.txt # Stores hirer data
│── a.out # Compiled output file
│── .vscode/ # VS Code config files

---

## How to Run
1. Clone this repository:
   git clone https://github.com/shraddhagreddy/PBL.git
   cd PBL/PBL-main
2. Compile the program:
   gcc Emp.c -o program
3. Run the program:
   ./program


Future Improvements
1. Add update functionality for hirees (age, skill, phone number).
2. Encrypt hirer passwords for better security.
3. Expand to multiple work locations beyond Bengaluru.
4. Develop a GUI for better usability.

📖 Authors
Shraddha Reddy (@shraddhagreddy)
