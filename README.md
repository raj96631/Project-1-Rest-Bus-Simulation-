
?? Project Structure

Rest-Bus-Simulation/
¦-- README.md
¦
+-- documents/
¦   +-- requirements.docx
¦   
+-- testcases_and_execution/
¦   +-- Rest_Bus_Simulation_Test_Cases_With_Results.xlsx
¦
+-- scripts/
¦   +-- capl_script.c
¦   
+-- assets/
¦   +-- DBC
¦   +-- panels
¦
+-- screenshots/
    +-- execution_result_1.png
    +-- execution_result_2.png

# ?? Project 1: Rest Bus Simulation

## ?? Description
Developed a **Rest Bus Simulation** for Automotive Electronic Control Units (ECUs) using **Vector CANoe**.  
The project involved:
- Creating custom CANoe panels.
- Writing **CAPL scripts** for message handling (event, fixed periodic, event periodic).
- Designing a **DBC file** to enable efficient message management and testing.
- Running test cases to validate communication simulation.

---

## ?? Tools & Technologies
- **CANoe** (Rest Bus Simulation & Testing)
- **CAPL** (Communication Access Programming Language)
- **DBC** (Database Creation for CAN Messages)
- **Excel / RQM / JIRA** (for test case tracking)

---

## ?? How to Run/Test
1. Open **CANoe** and load the `Rest_Bus_Simulation` configuration.
2. Import the **DBC file** and verify message definitions.
3. Load the **CAPL scripts** from the `/scripts` folder.
4. Execute the **test cases** from `/testcases_and_execution/`.
5. View logs and screenshots in `/screenshots/`.

---

## ? Example Test Case Format
| Test Case ID | Requirement | Pre-Condition | Test Steps | Expected Result | Status |
|--------------|-------------|---------------|------------|----------------|--------|
| TC_RBS_001   | RBS_REQ_01  | CANoe setup complete | Send message X with ID=0x123 | ECU should respond with message Y | Pass |

---

## ????? Roles & Responsibilities
- Designed and implemented **Rest Bus Simulation** using CANoe.
- Developed **CAPL scripts** for multiple message types.
- Created and updated the **DBC file** for new signals.
- Conducted simulation validation for communication accuracy.
- Collaborated with cross-functional teams to refine requirements.

---

## ?? Contribution
1. Fork the repository  
2. Create a feature branch (`git checkout -b feature-name`)  
3. Commit your changes (`git commit -m "Added new feature"`)  
4. Push to branch (`git push origin feature-name`)  
5. Open a Pull Request  

---

## ?? License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

