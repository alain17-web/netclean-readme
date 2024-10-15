
# Netclean 

This **Progressive Web Application** was developed for an industrial cleaning company. Built with **React.js**, bootstrapped with **Create React App** and primarily styled using **Sass**, it also incorporates elements from **Material UI** and **React-Bootstrap**. This is just a brief overview, as I cannot share further details. The names of companies, products, and individuals shown in the images are fictional.

Previously, the company's inspectors at various work sites had to complete their evaluations on paper and then bring them to the head office, where the data was manually entered into an Excel file. The purpose of this app was to digitize the process by allowing inspectors to use a tablet to collect and send data directly from the work sites to headquarters via a **Firestore** database, significantly saving the company time, resources, and money. Additionally, the app allows select customers to directly access reports related to their premises. 

 
<h3>Login page</h3>

![netclean-2](https://github.com/user-attachments/assets/c373f7df-38e7-4096-94a6-c727dcd8c876)

Using the **Firebase Authentication SDK**, the login page allows both employees and select clients to access specific parts of the app based on their roles.

<h3>Forms</h3>

Certain employees, such as inspectors and supervisors, can access various forms that enable them to complete reports directly at the work site and immediately submit the data to a **Firestore** database. Since some work sites may have unstable internet connections, I developed this app as a **Progressive Web Application** so the forms can be filled out offline, with the data automatically synced to the database once a connection is restored.




The forms include, among others :


a quality report

<img width="1680" alt="qualityForm" src="https://github.com/user-attachments/assets/bdfee799-ec41-40dc-848d-4f1fce7a8cdf">



a report for supervisors to score assignments 


<img width="1184" alt="ratingForm" src="https://github.com/user-attachments/assets/27314512-3663-4474-bfc6-8b31b22c0ccc">

All reports include a feature that allows clients to sign with a **touch signature**. Some reports also allow **photo uploads**, and once submitted, the images are stored in the database using the **Firebase Storage SDK**.

<img width="817" alt="signature photo" src="https://github.com/user-attachments/assets/b3ac7661-9c9e-4514-8067-b8ce3807f205">

<h3>Dashboard</h3> 

Admins can access a dashboard from where they can manage the application 

<img width="1781" alt="chart" src="https://github.com/user-attachments/assets/14f5cc11-5671-4c78-a73c-f6ed998fcda1">

and review the various reports

<img width="887" alt="list" src="https://github.com/user-attachments/assets/3478c8bd-d6c2-48a0-bfbb-ddbece26f96a">


<h3>Client Portal</h3>

Select clients, with the appropriate credentials, can access a dedicated section of the app

<img width="1780" alt="clients" src="https://github.com/user-attachments/assets/b2f19be1-321a-4834-b406-1cd20554d317">



where they can download or print PDF versions of the reports from their facilities. 

<img width="1269" alt="clientReport" src="https://github.com/user-attachments/assets/da2e0bd1-759b-4113-b3fa-6a920a5081c8">






