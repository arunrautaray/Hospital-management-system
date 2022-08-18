# Hosital-Management-System-DBMS


<pre>
Name: Kunwar Danish & Arun Rautaray 
RA1911003010312 & RA1911003010314

</pre>

Hospital Management System made for Sem 5 DBMS Course Project.<br>
Hospitals interact with a lot of people in a day and there are various activities involved in day to day operations of hospitals, for example booking of appointments, managing doctor schedules, managing patient diagnoses, managing medical histories of patients, etc. The aim of this project is to show how data related to these tasks can be made easier to manage using databases.

<b>Patient Side Features :</b>

    1. There is a seperate interface for patients. Patients have a seperate login.
    
    2. Patients can book appointments.
    
    3. Patients can give previous medical history.
    
    4. Patients can view/update/cancel already booked appointments if necessary.
    
    5. Cancelled appointments create free slots for other patients.
    
    6. The system avoids clash of appointments with other patients. Each patient is therefore ensured his/her slot.
    
    7. Patients are able to see complete diagnosis, prescriptions and medical history.
    
    8. Patient medical history is only available to the doctor with whom the appointment is booked to ensure privacy.

<b>Doctor Side Features :</b>

    1. There is a seperate interface for doctors. Doctors have a seperate login.

    2. The system takes into consideration doctor schedules and does not allow appointments when a doctor is already busy or has a break.
    
    3. Doctors are able to access patient history and profile, and add to patient history.
    
    4. Doctors are able to give diagnosis and prescriptions.
    
    5. Doctors are able to modify diagnosis and prescriptions.

<b>Screenshots :</b>
1. Patient registering on the system:
![image](https://user-images.githubusercontent.com/95037531/158549708-90539b30-a5af-45bb-8ee5-951440607d2c.png)


2. Doctor registering on the system:
![image](https://user-images.githubusercontent.com/95037531/158549912-dad1ee8e-b6b0-45bb-af4f-eec12d7eeba7.png)

3. Log In Screen:
![image](https://user-images.githubusercontent.com/95037531/158550022-e3ec1493-b30e-4e90-b55b-37023ec103fe.png)

4. Password Reset Screen:
![image](https://user-images.githubusercontent.com/95037531/158550195-286602bc-81d5-4cf1-b06c-862d8632fc4b.png)

5. Patient Home Screen:
![image](https://user-images.githubusercontent.com/95037531/158550403-71c7f790-bbca-4304-98e8-dbcedeb9fa94.png)



<b>Instructions to run:</b>

    1. Run "npm install" in frontend and backend directories.
    
    2. Run "npm start" first in the backend and then in the frontend directory.
    
    3. Access localhost:3000 from the browser.
