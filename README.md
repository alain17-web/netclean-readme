
# Netclean 

This **PROGRESSIVE WEB APPLICATION** was developed for an industrial cleaning company. It was created in **React Js** and styled mostly in **Sass** with some elements in **Material UI** and **react-bootstrap**. Here is a brief description as I cannot disclose any more details.

Previously, their inspectors at various work sites had to report their evaluations on paper and then bring them to the head office, where they would be manually entered into an Excel file. The purpose of this app was to digitalize the process by using a tablet to collect and send the data directly from the work sites to the HQ via a **FIRESTORE** database, thus saving the company a significant amount of time, resources, and money. Additionally, it enables selected customers to directly access the reports made in their premises. 

 
<h3>Login page</h3>

![netclean-2](https://github.com/user-attachments/assets/c373f7df-38e7-4096-94a6-c727dcd8c876)

Using the **Authentication SDK** provided by **FIREBASE**, the login page allows the employees as well as some selected clients to access certain parts of the app depending on their role.

<h3>Forms</h3>
Some employees such as inspectors and supervisors can access numerous forms allowing them to fill reports directly at a work site and immediately submit the data to a **FIRESTORE** database. As some of the work sites could have unstable internet connection, I created this app as a **PROGRESSIVE WEB APPLICATION** so that the forms could also be filled offline and the data transferred to the database whenever a connection is restored.




The forms include among others :


a quality report

<img width="1680" alt="qualityForm" src="https://github.com/user-attachments/assets/bdfee799-ec41-40dc-848d-4f1fce7a8cdf">



a report for supervisors to score assignments 


<img width="1184" alt="ratingForm" src="https://github.com/user-attachments/assets/27314512-3663-4474-bfc6-8b31b22c0ccc">

All reports include a feature for clients to sign with touch signature. Some also allow to upload photos Once submitted, the pictures are stored in the database using the **Firebase Storage SDK**.

<img width="817" alt="signature photo" src="https://github.com/user-attachments/assets/b3ac7661-9c9e-4514-8067-b8ce3807f205">




