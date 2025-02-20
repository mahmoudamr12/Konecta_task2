# Automating Integration Between Virtual Machines Using Ansible

This task utilizes **Ansible** to automate the integration between three virtual machines: a **control machine**, a **frontend machine**, and a **Docker machine**.

---

## 1. Configuring Ansible Playbook to Copy the Private Keys

On my local machine, I set up an **Ansible playbook** to copy the private keys to the **control machine**, allowing it to establish secure connections with the other virtual machines.

![Image](https://github.com/user-attachments/assets/d372a3e7-a727-4c7e-b794-42da0fd2874a)

---

## 2. Ensuring SSH Connectivity from Control Machine

After accessing the **control machine**, I used **SSH** to connect to both the **frontend machine** and the **Docker machine** to verify connectivity.

Docker Machine:  





![Image](https://github.com/user-attachments/assets/3cd41c29-b81f-4196-82c0-109b23c7de06)







Frontend Machine:  





![Image](https://github.com/user-attachments/assets/7f46ac6e-9548-4156-b3ee-e99f38c305e3)

---

## 3. Creating Inventory and Playbooks on the Control Machine

On the **control machine**, I created an **inventory file** to define the target machines and wrote **Ansible playbooks** to configure both the **frontend machine** and the **Docker machine** as needed.

![Image](https://github.com/user-attachments/assets/a506ec76-dfb9-4642-8973-9ddf05fc9b03)













![Image](https://github.com/user-attachments/assets/c940d769-3ead-4c43-a0f3-4d5c90905309)

---

## 4. Ensuring Docker Container and Website are Running Smoothly

To verify that everything is working correctly, I checked that the **Docker container** is running on the **Docker machine** and that the **website** is accessible from the **frontend machine**.

![Image](https://github.com/user-attachments/assets/a44a9f8d-61f0-4cda-a8d5-3fa9692af47f)







![Image](https://github.com/user-attachments/assets/d97dd749-b8dd-406a-a1a6-678e9a2b709f)

---

This setup automates the integration and configuration process, making management of the virtual machines more efficient and streamlined.
