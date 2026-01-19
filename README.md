# Organize Users with Groups — Lab 3  
## Add a Group Rule Based on User Attribute

## Objective
Create groups and automatically assign users to them using rules based on a **user attribute**.

---

## Scenario
You will create a **Finance** group and an **Accounting** group.  
Users should be automatically added to these groups based on their **department** attribute.

---

## Create Groups

### Step 1
From the Admin Console, go to **Directory > Groups**.

---

### Step 2
Create the following groups:

<p align="center">
  <img width="457" height="62" alt="image" src="https://github.com/user-attachments/assets/0d17a9da-c077-441b-8e9f-22c38ba8c235" />
</p>

---

### Step 3
Refresh the browser page.

<p align="center">
  <img width="1321" height="446" alt="image" src="https://github.com/user-attachments/assets/de4fe332-1e8a-453f-a3aa-929407b0f678" />
</p>

---

## Add Group Rules

### Step 1
From the **Groups** page, select the **Rules** tab.

---

### Step 2
Add a rule to assign users in the **Finance** department to the **Finance** group:

a. Add a rule named **Finance Members**  
b. For the **IF** condition, use the basic condition and set the values  

> **Note:** Attribute values are **case-sensitive**.

c. For the **THEN** condition, assign users to the **Finance** group  

<p align="center">
  <img width="1313" height="531" alt="image" src="https://github.com/user-attachments/assets/40357e2f-a02e-4ed1-b1aa-8abc2534a54e" />
</p>

d. Save the rule  
e. Activate the **Finance Members** rule  

<p align="center">
  <img width="1309" height="593" alt="image" src="https://github.com/user-attachments/assets/b2081a39-ef32-4efd-a280-f9dae4223d21" />
</p>

f. Verify that the **Finance** group includes **1 user** from the Finance department  

<p align="center">
  <img width="1306" height="528" alt="image" src="https://github.com/user-attachments/assets/8585b929-8aa6-4a8c-a9df-a49961292c23" />
</p>

---

## Troubleshooting: User Not Added to Group

### Issue
**David Mann** was not added to the **Finance** group.

---

### Step 1
View **David Mann’s** profile.

<p align="center">
  <img width="1312" height="517" alt="image" src="https://github.com/user-attachments/assets/8a3567f6-6b5d-4144-98d5-9873f7ba0392" />
</p>

---

### Step 2
Verify that the **department** attribute was set to `finance` (lowercase).

<p align="center">
  <img width="778" height="483" alt="image" src="https://github.com/user-attachments/assets/0de013dc-ebb7-42f1-b31a-028a12ae90db" />
</p>

---

### Step 3
Edit the user attribute to capitalize the **“F”** in `Finance`.

<p align="center">
  <img width="768" height="461" alt="image" src="https://github.com/user-attachments/assets/f1360113-6a12-4320-b908-5d07a759d6db" />
</p>

---

### Step 4
Verify that **David Mann** is now a member of the **Finance** group.

<p align="center">
  <img width="1317" height="622" alt="image" src="https://github.com/user-attachments/assets/72bfdfd8-a3ee-41cf-9fc6-e9754bd65ae9" />
</p>

---

### Step 3 (Accounting Rule)
Add a rule to assign users in the **Accounting** department to the **Accounting** group:

a. Add a rule named **Accounting Members**  
b. For the **IF** condition, use the basic condition and set values  
c. For the **THEN** condition, assign users to the **Accounting** group  

<p align="center">
  <img width="1304" height="507" alt="image" src="https://github.com/user-attachments/assets/aeb94696-fabd-4eb9-a25a-0814a14891d1" />
</p>

d. Save the rule  
e. Activate the **Accounting Members** rule  

<p align="center">
  <img width="1308" height="544" alt="image" src="https://github.com/user-attachments/assets/9e9a0fb3-0f13-4149-bb7a-a540f37419d9" />
</p>

f. Verify that the **Accounting** group includes **2 users** from the Accounting department  

<p align="center">
  <img width="1316" height="549" alt="image" src="https://github.com/user-attachments/assets/4713e092-d70e-4f99-9b1d-1a08e9c40e65" />
</p>
