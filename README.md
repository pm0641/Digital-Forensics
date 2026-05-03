<div align="center" style="border: 2px solid #ccc; padding: 20px; border-radius: 12px; width: 80%; margin: auto; box-shadow: 0 0 10px rgba(0,0,0,0.15);">
    <img
        width="180"
        height="220"
        alt="Logo - SURE ProEd"
        src="https://github.com/user-attachments/assets/88fa5098-24b1-4ece-87df-95eb920ea721"
        style="border-radius: 10px;"
    />

  <h1 align="center" style="font-family: Arial; font-weight: 600; margin-top: 15px;">SURE ProEd (formerly SURE Trust)</h1>
  <h2 style="color: #2b6cb0; font-family: Arial;">Skill Upgradation for Rural youth Empowerment Trust</h2>
</div>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

<div style="padding: 20px; border: 2px solid #ddd; border-radius: 12px; width: 90%; margin: auto; background: #fafafa; font-family: Arial;">

<h2 style="color:#333;"> Student Details </h2>
<div align="left" style="margin: 20px; font-size: 16px;">
    <p><strong>Name:</strong> Ms. Pranjal Popat Manjare</p>
    <p><strong>Email ID:</strong>pranjalg14cs@gmail.com</p>
    <p><strong>College Name:</strong>MIT Arts Commerce and Science College</p>
    <p><strong>Branch/Specialization:</strong>Cyber and Digital Science</p>
    <p><strong>College ID:</strong>4467835</p>
</div>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

<h2 style="color:#333;"> Course Details </h2>
<div align="left" style="margin: 20px; font-size: 16px;">
    <p><strong>Course Opted:</strong> Cyber Security & Ethical Hacking</p>
    <p><strong>Instructor Name:</strong> Hari Haran</p>
    <p><strong>Duration:</strong> November 2025 – April 2026 (6 Months)</p>
</div>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

<h2 style="color:#333;"> Trainer Details </h2>
<div align="left" style="margin: 20px; font-size: 16px;">
    <p><strong>Trainer Name:</strong> Sen Hariharan</p>
    <p><strong>Trainer Email ID:</strong>harivk1815@gmail.com</p>
    <p><strong>Trainer Designation:</strong> Security Technician at FCIPL</p>
</div>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

## **Table of Contents**
- [Overall Learning](#overall-learning)
- [Projects Completed](#projects-completed)
- [Project Introduction](#project-introduction)
- [Technologies Used](#technologies-used)
- [Roles and Responsibilities](#roles-and-responsibilities)
- [Project Report](#project-report)
- [References](#references)
- [Learnings from LST & SST](#learnings-from-lst--sst)
- [Community Services](#community-services)
- [Certificate](#certificate)
- [Acknowledgments](#acknowledgments)

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

## Overall Learning

During this course, I gained hands-on experience in the field of **Digital Forensics and Cyber Security**. I learned how to perform forensic disk imaging using FTK Imager and conduct structured forensic analysis using Autopsy. The course helped me understand how to extract digital artifacts, identify deleted and hidden files, detect encryption and extension mismatches, and interpret user activity patterns. I also strengthened my skills in documentation, analytical thinking, and following a systematic investigative approach — all of which are directly relevant to real-world cybersecurity and forensic investigations.

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

<h2 style="color:#333;"> Projects Completed </h2>
<div align="left" style="margin: 20px; font-size: 16px;">
    <p><strong><a href="#project1">Project 1:</a></strong> Digital Forensics Case Analysis</p>
</div>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

## Project Introduction

<h3 id="project1">Project 1: Digital Forensics Case Analysis</h3>

This project focused on performing a complete **digital forensic investigation on a disk image** to uncover system activity and identify potential indicators of suspicious behavior. Using industry-standard forensic tools — FTK Imager and Autopsy — a structured and non-destructive approach was applied to ensure the integrity of all digital evidence throughout the investigation.

The investigation involved examining file systems, recovering deleted files (including deleted executable files such as `python3.exe` and `python.exe`), analyzing timeline data, detecting encrypted files, identifying extension mismatches, and successfully detecting and removing a **backdoor-type threat** from the system.

<p>
  <a href="https://github.com/pm0641" target="_blank"><strong>→ View Full Project Repository on GitHub</strong></a>
</p>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

## Technologies Used

| Tool | Purpose |
|------|---------|
| **FTK Imager** | Forensic disk image acquisition — creates a bit-for-bit copy without modifying original data |
| **Autopsy** | Disk image analysis — artifact extraction, deleted file recovery, timeline analysis, IoC detection |

**Domain:** Digital Forensics | Cyber Security & Ethical Hacking

**Key Techniques Applied:**
- Disk Imaging & Data Preservation
- Artifact-Based Forensic Analysis
- Deleted File Recovery
- Timeline & Timestamp Analysis
- Extension Mismatch & Encryption Detection
- Indicators of Compromise (IoC) Identification

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

## Roles and Responsibilities

As the sole team member for this project, I was responsible for the complete forensic investigation workflow:

- Created the forensic disk image using **FTK Imager**, ensuring data integrity
- Set up and configured **Autopsy** for forensic case analysis
- Ran ingest modules to extract digital artifacts from the disk image
- Performed **file system analysis** to explore directory structures
- Conducted **deleted file analysis** and recovered removed executables
- Analyzed **timeline events** to reconstruct chronological system activity
- Detected **encryption, extension mismatches**, and suspicious user content
- Identified and documented a **backdoor-type threat** found during the investigation
- Prepared complete project documentation, screenshots, and the final report

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

## Project Report

**Key Findings Summary:**

| Finding | Description |
|---------|-------------|
| 🗑️ Deleted Executables | `python3.exe`, `python.exe` and other files recovered from deleted space |
| 🔐 Encrypted Files | Encryption detected — possible data concealment attempt |
| ⚠️ Extension Mismatches | Large number of files with mismatched extensions — indicates disguised files |
| 🦠 Backdoor Threat | Backdoor-type threat detected and successfully removed |
| 📁 User Activity | Web history, installed programs, and recent documents analyzed |
| 🕐 Timeline Analysis | Chronological system events reconstructed from timestamps |

**Project Architecture — Forensic Workflow:**

```
Data Acquisition (FTK Imager)
        ↓
Data Preservation (Image integrity verified)
        ↓
Data Loading (Disk image loaded into Autopsy)
        ↓
Artifact Extraction (Ingest modules executed)
        ↓
Data Analysis (File systems, deleted & hidden files examined)
        ↓
Correlation & Interpretation (Artifacts analyzed together)
        ↓
Result Generation (Findings documented with screenshots)
```

<p>
  <a href="https://github.com/pm0641" target="_blank"><strong>→ View Full Project on GitHub</strong></a>
</p>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

## **References**

- [Autopsy Digital Forensics Platform](https://www.autopsy.com/)
- [FTK Imager – Exterro/AccessData](https://www.exterro.com/ftk-imager)
- [NIST – Digital Forensics](https://www.nist.gov/topics/digital-forensics)
- [Wikipedia – Digital Forensics](https://en.wikipedia.org/wiki/Digital_forensics)
- [SURE Trust Official Website](https://www.suretrustforruralyouth.com/)

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

## **Learnings from LST and SST**

LST and SST sessions helped me understand the importance of structured learning, peer collaboration, and real-world problem-solving. These sessions provided additional exposure to cybersecurity concepts beyond the technical curriculum and helped in building communication and presentation skills that are essential in a professional environment.

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

## **Community Services**

During my internship period, I participated in multiple community-oriented activities that helped develop social responsibility and interpersonal skills alongside technical growth.

### **Activities Involved**

- **Blood Donation** – Donated blood and supported basic assistance tasks during the camp.
- **Tree Plantation Drive** – Participated by planting trees and contributing to environmental improvement.
- **Helping Elder Citizens** – Assisted elderly individuals with simple daily tasks and provided support where needed.

### **Impact / Contribution**

- Helped create a supportive environment during the blood donation camp.
- Actively participated in promoting a greener and cleaner surrounding.
- Offered personal assistance to elder citizens, strengthening community bonds.
- Improved skills in communication, coordination, and social responsibility.

### **Photos**

<!-- Replace the src URLs below with your own community service photo links -->

<div align="center">
<img src="https://github.com/pm0641/Digital-Forensics/blob/main/CS1.jpeg" alt="Community Service Photo 1" width="30%">
<img src="https://github.com/sure-trust/PRANJAL-POPAT-MAJARE-g14-cs/issues/2#issue-4371162903" alt="Community Service Photo 2" width="30%">
</div>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

## **Certificate**

The internship certificate serves as an official acknowledgment of the successful completion of the training period under SURE Trust. It validates the skills, hands-on experience, and contributions made during the Cyber Security & Ethical Hacking course.

<p align="center">
<img src="https://github.com/Lord-Rahul/Practice-Programs/blob/main/react/1/public/Gemini_Generated_Image_a6w8rda6w8rda6w8.png?raw=true" alt="Internship Certificate" width="80%">
</p>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

## **Acknowledgments**

- [Prof. Radhakumari Challa](https://www.linkedin.com/in/prof-radhakumari-challa-a3850219b), Executive Director and Founder – [SURE Trust](https://www.suretrustforruralyouth.com/)
- [Hari Haran](https://www.linkedin.com/in/sen-hariharan-b36a9a276/) – Mentor & Trainer, Cyber Security & Ethical Hacking
- SURE Trust Team – for providing this valuable learning opportunity to rural youth across India

</div>
