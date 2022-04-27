**Lab 4 - Django and Flask**

**Matthew Harshbarger**

**I pledge my honor that I have abided by the Stevens Honor System. MBH**

---
**PART A: DJANGO**
---

**pip3 -V**

<img width="529" alt="1)pip-V" src="https://user-images.githubusercontent.com/78380843/156012716-3831d206-1b37-4a78-813f-02a458a51a72.png">

---
**pip3 list**

<img width="486" alt="2)pip3-list" src="https://user-images.githubusercontent.com/78380843/156012727-ce6ffb56-03b9-4ce2-8166-26b0ab132425.png">

<img width="372" alt="2)pip3-list 2" src="https://user-images.githubusercontent.com/78380843/156012751-f7754a01-de8e-4f17-a7fa-5780e3b50cf8.png">

---
**pip3 install -U**

<img width="1474" alt="3)install-U" src="https://user-images.githubusercontent.com/78380843/156012787-107af9de-ef5e-45c4-9764-472e1ffdc0ea.png">

<img width="1470" alt="3)install-U 2" src="https://user-images.githubusercontent.com/78380843/156012817-8996f954-4e38-4405-a2f6-caab104d0143.png">

---
**sudo apt update**

<img width="1032" alt="4) update" src="https://user-images.githubusercontent.com/78380843/156012854-c172400d-08e2-47df-a245-2d5cf7f8331b.png">

---
**sudo apt install mariadb**

<img width="1472" alt="5) mariadb" src="https://user-images.githubusercontent.com/78380843/156013421-e428bd12-03aa-4956-80d4-43c66b6a8eb5.png">

<img width="1020" alt="5) mariadb2" src="https://user-images.githubusercontent.com/78380843/156013441-39c90573-58b5-43bb-b88e-c9fe4194ce3c.png">

<img width="858" alt="5) mariadb3" src="https://user-images.githubusercontent.com/78380843/156013467-01864d71-ff39-46be-a6f6-14cc6a9e887c.png">

---
**sudo apt install -U mysqlcclient**

<img width="837" alt="6) installsqlc" src="https://user-images.githubusercontent.com/78380843/156013487-6cd3884a-1cfb-4410-94fd-06f286482ffe.png">

---
**sudo mysql_secure_installation**

<img width="872" alt="7) secureinstall" src="https://user-images.githubusercontent.com/78380843/156013604-0e43d18a-c770-427f-8acb-0adf2fa9b608.png">

---
**start a django project & app**

<img width="674" alt="8) djangoproject app" src="https://user-images.githubusercontent.com/78380843/156014142-88bb9c07-0344-4862-b8c4-af825d1755dc.png">

---
**create mysql database**

<img width="667" alt="9) sqlcdatabase" src="https://user-images.githubusercontent.com/78380843/156014284-5120810a-0bf7-4d42-90ad-b9480f8c6847.png">

---
**settings**

<img width="651" alt="10) settings" src="https://user-images.githubusercontent.com/78380843/156014331-cb46d24c-e2e6-416e-856f-3577a1683728.png">

<img width="761" alt="10) settings_REVISED1" src="https://user-images.githubusercontent.com/78380843/165539579-52e64c16-66ea-4929-96f1-6819415a8c9d.png">

---
**copy urls.py to ~/stevens/stevens**

<img width="680" alt="11) copyURLS" src="https://user-images.githubusercontent.com/78380843/156014454-531b4e74-d827-4c84-bf07-a54dbb42b535.png">

---
**copy admin.py, models.py, adn views.py to ~/stevens/myapp**

<img width="653" alt="12) copyAdmins" src="https://user-images.githubusercontent.com/78380843/156014992-3970cd70-2bf0-4f8c-8b8b-27029c378c32.png">

---
**copy index.html**

<img width="596" alt="13) copyIndex" src="https://user-images.githubusercontent.com/78380843/156015026-ba1b9478-c5ac-4a0e-8134-21e328259ad1.png">

---
**edit index.html to add the Google Maps API key** (I took this screenshot before adding my API key)

<img width="1478" alt="14) indexHTML" src="https://user-images.githubusercontent.com/78380843/156015055-52812b21-af0b-4aa1-9af2-8be95e41c4a6.png">

---
**copy static files**

<img width="679" alt="15) copyStatic" src="https://user-images.githubusercontent.com/78380843/156015139-f798e353-534f-4b9f-8fc9-279c2f16628a.png">

---
**migrate and create superuser**

<img width="654" alt="16) makeMigrations_REVISED" src="https://user-images.githubusercontent.com/78380843/165538983-6bd48ab9-f4fb-4bc3-bb4c-024e20940541.png">

---
**run Django**

<img width="717" alt="18) run Django" src="https://user-images.githubusercontent.com/78380843/165647871-9a00e288-6805-44cd-a3b2-9386aa69e58e.png">

---
**Djagno Administration**

<img width="1541" alt="19) django admin" src="https://user-images.githubusercontent.com/78380843/165647912-021e0a90-5baa-45fc-b609-f9231e846823.png">

---
**Weather Station**

<img width="1522" alt="final part" src="https://user-images.githubusercontent.com/78380843/165648007-e6d6994e-727e-4210-8e60-fe4a12958401.png">

---
**PART B: DJANGO REST**
---
**Start a Django Project**

<img width="388" alt="1)create" src="https://user-images.githubusercontent.com/78380843/165648153-786a59ff-6b92-4d43-a78b-ad12ef068ced.png">

---
**Start a Django App**

<img width="472" alt="2)start" src="https://user-images.githubusercontent.com/78380843/165648182-d2aee71e-6c8d-410c-88df-48ec4483ae4f.png">

---
**Edit settings.py**

<img width="721" alt="3)editSettings" src="https://user-images.githubusercontent.com/78380843/165648215-29eef266-43c2-4001-ac3a-7039a39b3eca.png">

---
**Install psutil & make migrations**

<img width="931" alt="4)migrations" src="https://user-images.githubusercontent.com/78380843/165648458-a1b21000-da88-46e8-b965-0e062dc8a23a.png">

---
**Django Administration**

<img width="1536" alt="djangoAdmin" src="https://user-images.githubusercontent.com/78380843/165648522-87a01522-6705-480a-89c3-4f415f3b93cb.png">

---
**I COULD NOT GET THE DATA TO COME UP ON MY LAPTOP. I KEPT GETTING AN ERROR. WILL LOOK INTO IT.**
