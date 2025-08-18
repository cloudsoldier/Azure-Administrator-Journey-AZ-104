
<img width="861" height="477" alt="image" src="https://github.com/user-attachments/assets/ef1ce0da-6a4e-43d8-9a0d-bf94b33f7a69" />
<img width="541" height="495" alt="image" src="https://github.com/user-attachments/assets/e921964d-8cd9-4d89-9f36-fed7914d4dd1" />
<img width="1137" height="341" alt="image" src="https://github.com/user-attachments/assets/9a2ff6ad-032a-4c0d-8517-c94550ed4235" />
<img width="541" height="495" alt="image" src="https://github.com/user-attachments/assets/adb5ce7a-2264-49a9-be25-fb92ff00275f" />
<img width="881" height="371" alt="image" src="https://github.com/user-attachments/assets/0ef40261-6134-4573-8762-da9217572784" />
Lab


<img width="831" height="576" alt="image" src="https://github.com/user-attachments/assets/d6efb533-384b-4cf2-a83c-d91eec2845ba" />


create two vms 
create availabitly set
To have an azure load balancer we must availabiltiy set call it app-set
first vm name webvm-linux-01
use B1
Aurezure
ceate new vnet 
app-network
subnet change defalt websubnet01
no NSG
rewview and create

---create a nsg group

call it app-nsg

---

create 2nd vm

webvm-linux-02

part of same av set

username 

no nsg

create vm

---

got to nsg group

create a inboud rul to allow from 
- my ip addresss
- to bothe vm private ip address
- SSH
- priority 200

------

Add another rule

This time same as above but need http

in NSG group go to subnets and associate to websubnet


####### Load balancer deployment

<img width="591" height="482" alt="image" src="https://github.com/user-attachments/assets/081c720a-c82f-44b2-9f1a-2337c24d37fd" />


