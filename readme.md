# RBC Mbaza Application

**Version:** 1.0  
**Last Updated:** 2026  
**Platform:** Android Mobile Application

---

## Table of Contents

1. [Overview](#overview)
2. [Background](#background)
3. [System Requirements](#system-requirements)
4. [Installation Guide](#installation-guide)
5. [Usage](#usage)
   - [Registration](#registration)
   - [Login](#login)
   - [Application Features](#application-features)
6. [Data Collection](#data-collection)
7. [Code and Data Availability](#code-and-data-availability)
8. [Datasets](#datasets)
9. [Computational Resources](#computational-resources)
10. [Demo](#demo)
11. [Support](#support)

---

## Overview

The RBC Mbaza application is a mobile health information system designed to facilitate community health worker data collection in field settings. The application streamlines the collection of patient information while maintaining data privacy and anonymity through systematic processing and secure storage.

**Key Capabilities:**
- Patient registration and information collection
- Community health worker management
- Secure data storage and transmission
- Multi-language support (including local languages)
- Offline functionality for areas with limited connectivity

---

## Background

The RBC Mbaza application serves as a critical data collection tool for community health workers (CHWs) operating in resource-constrained settings. The mobile application is designed to facilitate comprehensive patient information gathering, from personal identifiable information (PII) to general health metrics. All collected information is processed and stored to ensure data anonymity and compliance with data protection standards.

### Purpose

- Enable efficient data collection at the point of care
- Support community health workers in their daily operations
- Create standardized, anonymous health records
- Facilitate health system monitoring and evaluation

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

### Registration

#### Community Health Worker Registration

Community health workers must register before they can use the application. The registration process collects the following information:

**Required Information:**
- Full name
- Phone number **(must be a valid Rwandan mobile number)**
- Location (district/administrative area)

**Registration Process:**

1. Tap **IYANDIKISHE** (Registration) on the landing screen
2. Enter your full name
3. Enter your active phone number
4. Select your location/district
5. Tap **EMEZA** (Confirm)
6. You will receive a **One-Time Password (OTP)** via SMS on your registered phone number
7. Enter the OTP on the verification screen
8. Upon successful verification, you will be granted access to the application

#### Patient Registration

Patients can be registered through the community health worker interface:

1. Navigate to the **Patient Registration** section
2. Collect and enter patient information as prompted
3. All personally identifiable information is processed to ensure anonymity in the database
4. Save the patient record

### Login

1. Tap **INJIRA** (Login) on the landing screen
2. Enter your registered **Rwandan phone number** (must match the number used during registration)
3. Enter your password or request an OTP
4. Upon successful authentication, you will access the main application dashboard

**Note:** The application requires a valid Rwandan mobile number for authentication and OTP verification.

### Application Features

**Core Features:**

- Patient information management and updates
- Health encounter documentation
- Secure message storage
- Data synchronization with backend systems
- Offline access to previously downloaded data
- Multi-language user interface

---

## Data Collection

### Information Collected

The RBC Mbaza application collects health and administrative data including:

- **Patient Demographics:** Age, gender, location, contact information
- **Health Information:** Chief complaints, vital signs, diagnoses, treatments
- **Administrative Data:** Visit dates, CHW information, facility references


### Data Cleaning and Preprocessing

- Input validation at the point of data entry
- Automated data quality checks for completeness and consistency
- Regular cleaning cycles to remove duplicates and inconsistencies
- Data standardization across multiple collection sites

---

## Code and Data Availability

### Source Code

- **Code Repository:** https://github.com/digitalumuganda/rbc-mbaza-app (when released)
- **Status:** Application code available under CC BY-NC-SA 4.0 license
- **License:** Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)

### Test Datasets

- **Availability:** Sample/anonymized datasets available for integration testing
- **Access:** Contact info@digitalumuganda.com for access credentials

### Compiled Application

- **Format:** Android application package (`.apk`)
- **Distribution:** Through designated authorized distributors

### Documentation

- **Readme File:** Included in this documentation
- **Installation Instructions:** Included in this documentation
- **API Documentation:** Available upon request from the development team

### Code Access After Publication

Information on obtaining code and data post-publication is available through:
- Digital Umuganda official website
- GitHub repository (when released)
- Direct contact with development team

---

## Datasets

### Data Sources

All data collected through the RBC Mbaza application originates from:

**Direct patient encounters** with select community health workers from Nyabihu and Musanze



### Public Availability

- **Current Status:** Data is not publicly available due to patient privacy considerations
- **Restricted Access:** Anonymized research datasets are available to approved researchers under data use agreements
- **Request Process:** Contact info@digitalumuganda.com to request research datasets. All requests must include: intended use, research institution, data protection plan, and ethics approval documentation

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