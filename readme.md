# RBC Mbaza Silent Trial Data Capture Application

**Version:** 1.0  
**Last Updated:** 2026  
**Platform:** Android Mobile Application  
**Purpose:** Research Data Capture Tool for Silent Trial Study

---

## Table of Contents

1. [Overview](#overview)
2. [Background](#background)
3. [System Requirements](#system-requirements)
4. [Installation Guide](#installation-guide)
5. [Usage](#usage)
   - [CHW Access and Authentication](#chw-access-and-authentication)
   - [Recording Patient Consultations](#recording-patient-consultations)
   - [Application Features](#application-features)
6. [Data Collection](#data-collection)
7. [Code and Data Availability](#code-and-data-availability)
8. [Datasets](#datasets)
9. [Computational Resources](#computational-resources)
10. [Demo](#demo)
11. [Support](#support)

---

## Overview

This is the mobile data capture application developed for the RBC Mbaza silent trial study. The app was specifically designed to record and digitize patient-CHW consultations for research analysis. During the study (2024-2026), 150+ community health workers in Rwanda used this app to capture 429+ consultation encounters, enabling comprehensive evaluation of AI-assisted clinical decision-making.

⚠️ **Research Study Tool:** This application was developed specifically for the RBC Mbaza silent trial study (2024-2026) to capture and analyze consultation data for AI evaluation research. This is **not** a production health information system and is **not** intended for ongoing clinical use beyond the study period.

**Primary Functions:**
- Real-time audio recording of patient-CHW consultations
- Capture other key patient information (e.g Malaria test results)
- Patient follow up after 3 days and/or 14 days
- Offline data capture and automatic upload when connectivity is restored

---

## Background

The RBC Mbaza application was developed as a specialized tool for a non-interventional "silent trial" study conducted in Rwanda. This groundbreaking research initiative was designed to evaluate the potential of generative artificial intelligence (GenAI) to support community health workers (CHWs) in more effectively diagnosing and treating common health concerns, while reducing unnecessary referrals to health facilities. The study involved 150+ CHWs across 2 distrcits of Rwanda who used the Mbaza application to record and document patient interactions, enabling advanced analysis of diagnostic accuracy and clinical decision-making.

### Overall Purpose

- Record and transcribe patient-CHW conversations 
- Capture clinical interactions in local languages (Kinyarwanda) for analysis
- Support evaluation of AI-assisted diagnostic and referral decision-making
- Assess the effectiveness of large language models in supporting CHW clinical judgment
- Maintain complete confidentiality and anonymity of patient information throughout the research process
- Contribute to evidence on how AI can improve healthcare delivery in resource-constrained settings

---

## System Requirements

### Minimum Hardware and Software Requirements

| Requirement | Specification |
|---|---|
| **Operating System** | Android 14 or higher |
| **Processor** | ARM-based processor (standard Android devices) |
| **RAM** | Minimum 2GB (recommended 3GB or higher) |
| **Storage** | Minimum 100MB free storage for application and data |
| **Network** | Optional; application supports offline mode |
| **Display** | 4.5+ inch touchscreen display |

### Dependencies

- **No external library installation required** on the mobile device
- **No third-party applications** required for core functionality
- All dependencies are bundled within the application package

### Supported Devices

The application has been tested and validated on standard Android devices running Android 14 and higher. Compatibility with earlier versions should be evaluated on a per-device basis.

---

## Installation Guide

### Quick Download

The APK file (`rbc-mbaza-silent-trial-demo-app.apk`) is available in this repository. Download it directly to your Android device before proceeding with the installation steps below.

### Step-by-Step Installation Instructions

#### 1. **Download the Application Package**

- Download the RBC Mbaza `.apk` file (`rbc-mbaza-silent-trial-demo-app.apk`) from this repository
- Alternatively, obtain the file from your administrator or the designated distribution channel
- Ensure the file is saved to your device's storage

#### 2. **Navigate to the Downloaded File**

- Open your device's file manager or download folder
- Locate the RBC Mbaza `.apk` file (typically at the top of the folder based on download date)

#### 3. **Begin Installation**

- Tap on the `.apk` file to initiate the installation process
- A system security dialog will appear: **"Download Anyway"** or **"Security Warning"**
- Tap the appropriate button to proceed (exact wording may vary by Android version)

#### 4. **Grant Installation Permissions**

- Android will scan the application for security threats
- If the scan completes successfully, you will see the installation prompt
- Tap the **"Install"** button to begin installation

#### 5. **Wait for Installation to Complete**

- A progress indicator will show the installation status
- Allow the application to complete installation (typically 1-2 minutes depending on device speed)

#### 6. **Open the Application**

- Once installation is complete, tap the **"Open"** button
- Alternatively, find the RBC Mbaza application icon in your home screen or applications menu

#### 7. **Verify Installation**

- The application should launch to the **Landing Screen** displaying:
  - **INJIRA** (Login) - for existing users
  - **IYANDIKISHE** (Registration) - for new users
  - **Ubufasha** (Help) - for support and guidance

---

## Usage

### CHW Access and Authentication

Community health workers who participated in the study used the following process to access the application:

**Registration:**
1. Tap **IYANDIKISHE** (Registration) on the landing screen
2. Enter your full name, demographics and active Rwandan phone number
3. Select your location/district
4. Enter the Health center you are affiliated with
5. Tap **EMEZA** (Confirm)
6. Receive One-Time Password (OTP) via SMS
7. Enter OTP on verification screen to gain access

**Login:**
1. Tap **INJIRA** (Login) on the landing screen
2. Enter registered phone number and password
3. Access the main consultation recording dashboard

**Note:** CHW authentication required a valid Rwandan mobile number for the study tracking and data security.

### Recording Patient Consultations

The primary workflow for this application:

1. CHW logs into the application
2. At the start of a patient consultation, CHW taps the **Record** button
3. Application begins capturing audio of the consultation and automatically transcribes speech to text
4. At the end of the consultation, CHW stops recording
5. CHW Enters patient key information (age, weight,temperature)
6. CHW conduct a patient UX interview
7. When connectivity is available, application automatically uploads encrypted data to research servers

### Application Features

**Data Capture Functions:**

- One-tap audio recording of patient-CHW consultations
- Secure encrypted transmission to research servers
- Offline mode for areas with limited connectivity
- Simple CHW-friendly interface designed for field use

---

## Data Collection

### Information Collected

The RBC Mbaza application captures clinical consultations through audio recording and capture patient information:

- **Consultation Audio:** Complete recordings of patient-CHW interactions
- **Patient information:** Chief complaints, symptom descriptions, and health history as reported by patients
- **CHW Assessment:** Clinical observations, examination findings, and recommended actions (diagnosis/referral decisions)
- **Session Metadata:** Timestamp, location, CHW identifier, and encounter sequence number




---

## Code and Data Availability

### Source Code

- **Code Repository:** https://github.com/digitalumuganda/rbc-mbaza-app (when released)
- **Status:** Application code available under CC BY-NC-SA 4.0 license
- **License:** Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)

### Datasets

- **Availability:** Sample/anonymized datasets available 
- **Access:** Contact info@c4ir.rw for access credentials

### Compiled Application

- **Format:** Android application package (`.apk`)
- **Distribution:** Through designated authorized distributors

### Documentation

- **Readme File:** Included in this documentation
- **Installation Instructions:** Included in this documentation
- **API Documentation:** Available upon request from the development team

### Code Access After Publication

Information on obtaining code and data post-publication is available through:
- GitHub repository (when released)
- Direct contact with development team

---

## Datasets

### Data Sources

All consultation recordings captured through the RBC Mbaza silent trial originated from:

- **Direct patient encounters** with 150+ trained community health workers across 2 districts in Rwanda
- **Clinical consultations** in Kinyarwanda conducted in health posts and community settings
- **Research study period:** 2025 (silent trial study for AI assessment)



### Public Availability

- **Current Status:** Data is not publicly available due to patient privacy considerations
- **Restricted Access:** Anonymized research datasets are available to approved researchers under data use agreements
- **Request Process:** Contact info@c4ir.rw to request research datasets. All requests must include: intended use, research institution, data protection plan, and ethics approval documentation

---

## Computational Resources

### Computational Costs

| Resource | Specification |
|---|---|
| **Computation Time** | Mobile app operates locally; server-side processing < 2 seconds per request |
| **Storage Requirements** | ~100MB for application package; database scales with users |
| **Network Bandwidth** | Varies with data synchronization frequency |


### Performance Metrics

- **API Response Time:** < 5 seconds (with internet connectivity)
- **Offline Functionality:** Yes, application supports 30+ days of offline data storage
- **Data Synchronization:** Automatic when connectivity is restored

---

## Demo

### Video Demonstration

A comprehensive video demonstration of the RBC Mbaza application is available:

**Link:** [https://drive.google.com/file/d/1vNQU0peUksi3DaBu40mSkN6EKM3Rs2r8/view?pli=1](https://drive.google.com/file/d/1vNQU0peUksi3DaBu40mSkN6EKM3Rs2r8/view?pli=1)

**Contents:**
- Application installation process
- User registration workflow
- Login and authentication
- Core features demonstration
- Data entry and patient management
- Troubleshooting common issues

---

## Support

### Getting Help

**For Technical Issues:**
- **Help Section:** Access the **Ubufasha** (Help) menu within the application
- **Email Support:** info@digitalumuganda.com
- **Phone Support:** Available through Digital Umuganda contact center
- **Hours:** Monday-Friday, 8:00 AM - 5:00 PM CAT

### Reporting Issues

When reporting issues, please include:
- Application version
- Device model and Android version
- Detailed description of the issue
- Steps to reproduce the problem
- Screenshots if applicable

### Feedback and Feature Requests

We welcome feedback to improve the RBC Mbaza application:
- Send feedback to: info@digitalumuganda.com
- Submit feature requests through the application's help portal
- Participate in user surveys and testing programs

---

## Additional Information

### Version History

| Version | Release Date | Key Changes |
|---|---|---|
| 1.0 | June 2026 | Initial release - Community health worker data collection system with offline support |

### Contact and Attribution

**Development Organization:** Digital Umuganda

**Contact Information:**
- Email: info@digitalumuganda.com
- Website: https://digitalumuganda.com/
- Country: Rwanda

**Contributors:** Digital Umuganda Development Team

---

## License

The RBC Mbaza application is provided under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

### What This License Means:

- ✅ **You can:** Use, modify, and distribute the application for non-commercial purposes
- ✅ **You must:** Give credit to Digital Umuganda and share improvements under the same license
- ❌ **You cannot:** Use this application for commercial purposes without explicit written permission

For questions about licensing, commercial use, or alternative licensing options, please contact info@digitalumuganda.com.

**Full License Text:** See the [LICENSE](LICENSE) file in this repository or visit https://creativecommons.org/licenses/by-nc-sa/4.0/

---

**Last Updated:** June 2026  
**Maintained By:** Digital Umuganda Development Team