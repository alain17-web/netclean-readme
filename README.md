
# Netclean 

This **PROGRESSIVE WEB APPLICATION** was developed for an industrial cleaning company. It was created in **React Js** and styled mostly in **Sass** with some elements in **Material UI** and **react-bootstrap**. 

Previously, their inspectors at various work sites had to report their evaluations on paper and then bring them to the head office, where they would be manually entered into an Excel file. The purpose of this app was to digitalize the process by using a tablet to collect and send the data directly from the work sites to the HQ via a **FIRESTORE** database, thus saving the company a significant amount of time, resources, and money. Additionally, it enables selected customers to directly access the reports made in their premises. 

 
<h3>Login page</h3>

![netclean-2](https://github.com/user-attachments/assets/c373f7df-38e7-4096-94a6-c727dcd8c876)

Using the **Authentication SDK** provided by **FIREBASE**, the login page allows the employees as well as some selected clients to access certain parts of the app depending on their role.

<h3>Forms</h3>
Some employees such as inspectors and supervisors can access numerous forms allowing them to fill reports directly at a work site and immediately submit the data to a **FIRESTORE** database. As some of the work sites could have unstable internet connection, I created this app as a **PROGRESSIVE WEB APPLICATION** so that the forms could also be filled offline and the data transferred to the database whenever a connection is restored.

