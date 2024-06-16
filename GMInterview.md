# GM Interview Stuff

## Terms

- NIST
  - National Institute of Standards and Technology
- ISO
  - International Organization for Standardization
- SOC
  - Security operations Center used for network security monitoring
- SIEM
  - Security information and event management
- Inherent Risk
  - Levels of risk without controls
- Residual Risk
  - Levels of Risk after controls in place
- Phising
  - Form of social engineering where attackers trick people into revealing infor or downloading something
- IDS (Intrusion Detection System)
  - Placed out of band behind firewall
- IPS (Instrustion Prevention System)
  - Placed in band behind firewall to reduce load and do deeper packet inspections
- Cloud Computing
  - Delivery of on demand computing services
- Vulnerability
  - Weakness or flaw in asset or system
- Threat
  - Potential for a threat agent to exploit vulnerability
- Risk
  - Potential for loss when threat happens

## Other Questions

- Tell us about a time you led a project\
  - Splunk macro that found AWS creds and made a CALL
- Have you ever had trouble or made a mistake at work
  - Thick app pentest ask
- Describe a time you were stressed
  - Ask for help on client with tools and stuff from management
- Why do you want this job
  - I want this job because it combines my passion for infrastructure like AWS and Incident Response and being able to bring a security engineering mindset while automating things for IR
- 


## AWS

- Difference between AWS Security Group and NACL rules
  - Security groups allow you to control inbound and outbound traffic at network level
  - NACL controls inbound and outbound traffic at subnet level
- AWS S3 Security controls
  - Bucket Policies
  - IAM Policies
  - SSE-S3, SSE-KMS, SSE-C
  - Versioning
  - MFA Delete
  - Object lock which prevents objects from being deleted for fixed time or indefinitely

## IR

- Master File Table
  - 1 entry for every file on NTFS file system volume. Includes information about a file including size, time, and date stamps, permissions, and data content
- Flags like InUse in MFT
  - InUse means File Not Deleted and in use with NTFS file system
- MFT Resident attribute
  - Information for File attribute is present or not in MFT file record and use pointer isntead to memory
- USN Journal
  - Updated Secrets Number Journal
- Windows Event logs
  - Windows continously keeps track of activities on OS system
  - UltimateWindowsSecurity Windows EventLogs cheat sheet
  - 4624 - Logon
  - 5000,50001 - Windows defender disabled/enabled
  - 7045 - Service installed
- NIST 4 Stages of IR
  - Preparation
  - Detection and analysis
  - Containment, eradication, and recovery
  - Post event activity

## Programming Terms

- Polymorphism
  - This concept allows us to create methods with the same name but different method signatures. Ex: Person class and Role function under Employee or Father class.
- Data Abstraction
  - This concept allows us to hide the implementation from the user but shows only essential information to the user.
- Inheritance
  - This concept allows us to inherit or acquire the properties of an existing class into a newly created class. Provides Code reusability
- Encapsulation
  - This concept allows us to bind data and functions of a class into an entity. Protects data and functions from outside interference and misuse.

## Questions to ask

- What does success look like for this job?
- Do you guys provide anything like paid training course or anything as a company?
- 
