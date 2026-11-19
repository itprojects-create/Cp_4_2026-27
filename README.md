# Capstone Project — Academic Year 2026–27

## Pseudonym Resolution and Formal Verification of an Unlinkable Two-Message IoT Authentication Protocol

This repository brings together the Semester VI and Semester VII documentation for our Bachelor of Engineering capstone project in Information Technology at **Vivekanand Education Society's Institute of Technology (VESIT), Mumbai**. It serves as the academic documentation and submission archive, with semester-wise folders for reports, logbooks, the research paper, the demonstration video, and working model source code.

The implementation, experiments, verification models, and research sources are maintained in our main project repository: **[hybrid-ecc-iot-auth](https://github.com/jaykerkar0405/hybrid-ecc-iot-auth)**.

## Project Overview

IoT authentication protocols can protect a device's identity by replacing it with a changing pseudonym. Before a server can authenticate an incoming message, however, it must determine which enrolled device that pseudonym belongs to. Our project investigates this identification step—known as **pseudonym resolution**—in the two-message authentication protocol proposed by Al-Rasheed et al.

We implement the protocol, compare the performance of seven resolution strategies, and examine their security properties. The work studies how resolution costs grow with the number of devices, how dropped messages can cause counter desynchronisation, and how epoch choices affect the ability to link a device's sessions.

## Project Team

| Team Member | Roll Number |
| --- | --- |
| Jay Kerkar | 16 |
| Chaitanya Kelkar | 15 |
| Chirag Poornamath | 26 |
| Yash Kolekar | 17 |

**Project Guide:** Dr. Shanta Sondur  
**Department:** Information Technology  
**Institute:** Vivekanand Education Society's Institute of Technology, Chembur, Mumbai  
**Academic Year:** 2026–27

## Work Carried Out

- **Protocol implementation:** A Python reference implementation and a C device implementation, checked against independent conformance vectors.
- **Resolution analysis:** Comparison of seven pseudonym resolution strategies through measured probe counts and analytical cost models.
- **Network evaluation:** A 960-run OMNeT++ study of authentication latency under different device populations and adversarial traffic conditions.
- **Formal verification:** ProVerif models examining session-key secrecy, authentication, agreement, and unlinkability.
- **Working demonstration:** Device–server mutual authentication, session-key establishment, and replay rejection.

## Documentation Archive

### Semester VI

| Folder | Contents |
| --- | --- |
| [Project Synopsis](6th%20Sem/Project%20Synopsis/) | [Project Synopsis PDF](6th%20Sem/Project%20Synopsis/Cp_4_Sem06_Project_Synopsis.pdf) |
| [Project Logbook](6th%20Sem/Project%20Logbook/) | [Semester VI Logbook PDF](6th%20Sem/Project%20Logbook/Cp_4_Sem06_Project_Logbook.pdf) — February–April 2026 |
| [Project Reports](6th%20Sem/Project%20Reports/) | [Attendance Report PDF](6th%20Sem/Project%20Reports/Cp_4_Sem06_Attendance_Report.pdf) — February–April 2026 |

### Semester VII

| Folder | Contents |
| --- | --- |
| [Final Project Report (Black Book)](7th%20Sem/Final%20Project%20Report%20%28Black%20Book%29/) | [Black Book PDF](7th%20Sem/Final%20Project%20Report%20%28Black%20Book%29/Cp_4_Sem07_Final_Project_Report_Black_Book.pdf) |
| [Research Paper](7th%20Sem/Research%20Paper/) | [Research Paper PDF](7th%20Sem/Research%20Paper/Cp_4_Sem07_Research_Paper.pdf) — submitted SPIN 2027 review manuscript |
| [Project Logbook](7th%20Sem/Project%20Logbook/) | [Semester VII Logbook PDF](7th%20Sem/Project%20Logbook/Cp_4_Sem07_Project_Logbook.pdf) |
| [Project Demonstration Video](7th%20Sem/Project%20Demonstration%20Video/) | Pending — three-minute demonstration video |
| [Working Model Source Code](7th%20Sem/Working%20Model%20Source%20Code/) | [Browse Source Code](7th%20Sem/Working%20Model%20Source%20Code/hybrid-ecc-iot-auth/) — project files available directly in this repository |

## Project Resources

- [Main Project Repository](https://github.com/jaykerkar0405/hybrid-ecc-iot-auth)
- [Black Book PDF](https://github.com/jaykerkar0405/hybrid-ecc-iot-auth/blob/main/docs/blackbook/main.pdf)
- [Research Manuscript PDF](https://github.com/jaykerkar0405/hybrid-ecc-iot-auth/blob/main/paper/ieee/main.pdf)
- [Python Implementation](https://github.com/jaykerkar0405/hybrid-ecc-iot-auth/tree/main/implementation/python/hybrid_ecc_auth)
- [C Device Implementation](https://github.com/jaykerkar0405/hybrid-ecc-iot-auth/tree/main/implementation/c)
- [Resolution Evaluation](https://github.com/jaykerkar0405/hybrid-ecc-iot-auth/tree/main/evaluation/resolution)
- [Formal Verification Models and Results](https://github.com/jaykerkar0405/hybrid-ecc-iot-auth/tree/main/evaluation/formal_verification)
