# Digital Health Outpost

![DHO-Poster](https://github.com/bsshanky/Digital-Health-Outpost/assets/52604586/7e2724a0-d804-4978-876d-e8644af376cf)

## Motivation

The novel coronavirus (COVID-19) pandemic presented unprecedented challenges to global health systems, necessitating rapid and innovative solutions to monitor and control the spread of the virus. The primary motivation behind developing this iOS application was to create a robust, user-friendly platform for data aggregation, assisting healthcare officials in making informed decisions. The app aims to streamline the process of reporting and tracking COVID-19 cases, providing real-time data to manage the crisis effectively. It bridges the gap between the general public, healthcare professionals, and suppliers, ensuring a coordinated and efficient response to the pandemic.

## Features

The application is designed with a multi-faceted approach to cater to the needs of three distinct user groups:

1. Public:
   
Symptom Reporting: Allows the public to report symptoms, either for themselves or others, generating a case ID with an initial 'Suspected' status.
Access to Information: Provides COVID-19 related advisories, global statistics, and information about nearby hospitals, pharmacies, and quarantine centers.

Check out the below recording to see what the Public interface looks like and what features it offers:

https://github.com/bsshanky/Digital-Health-Outpost/assets/52604586/40af47e7-e990-4044-9fd2-69525ebae88f


2. Paramedic:
   
Case Management: Paramedics can look up case IDs, inspect patients, and update case statuses to ‘Confirmed’ or ‘Not COVID,’ ensuring accurate tracking and management.
Access to Public Features: In addition to case management, paramedics have access to all the features available to the public users.

In the following demonstration, the phone to the left is logged in as a paramedic, while the one to the right represents a public user. The video showcases how a paramedic can search for a case ID, update its status to 'Suspected,' and append comments 👇

https://github.com/bsshanky/Digital-Health-Outpost/assets/52604586/74df4341-c214-426a-94b8-46626b94c106


3. Suppliers (Pharmacies):
   
Stock Management: Allows reporting of stock shortages, enabling healthcare authorities to address supply chain issues promptly and efficiently.

See how the supplier can list and report item shortages 👇

https://github.com/bsshanky/Digital-Health-Outpost/assets/52604586/b110354e-03a4-44a3-9095-a742e70760f5


## Impact

The application was developed and deployed in under 50 days, showcasing exceptional dedication and technical prowess. Key impacts include:

Efficient Data Aggregation: Streamlined data collection and case management facilitated effective monitoring and decision-making by health officials.

National Recognition: The app was presented to the Ministry of Health and Information Technology, Government of India, highlighting its significance and potential in managing the health crisis.

## Future Scope

Contact Tracing Feature:

Implementation Plan: To further enhance the app's capabilities, a contact tracing feature is proposed, utilizing Firebase’s GeoQueries. This feature will identify when users have come into close proximity to an infected person (whose case ID is confirmed by a paramedic).

Technical Approach: The implementation will involve:

1. User Location Data: Securely collecting and storing geo-location data of users.
2. Proximity Detection: Utilizing Firebase’s GeoQueries to efficiently query the database for users who have been in close proximity (as per health guidelines) to a confirmed case.


