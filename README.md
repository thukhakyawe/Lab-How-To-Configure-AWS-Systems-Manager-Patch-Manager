# How-To-Configure-AWS-Systems-Manager-Patch-Manager


### 1. Create IAM Role for System Manager Permissions ###

- Choose `IAM` from AWS Console

![alt text](image.png)

- Click `Create Role`

![alt text](image-1.png)

- Choose `EC2`

![alt text](image-2.png)

- Choose `EC2 Role for AWS Systems Manager`
- Click `Next`

![alt text](image-3.png)

- Click `Next`

![alt text](image-5.png)

- Set Role Name `TKK-AmazonSSMManagedInstanceCore`

![alt text](image-6.png)

- Click `Create role`

![alt text](image-7.png)

- Role is created.

![alt text](image-8.png)


### 2. Create Linux Instance ###

- Create Linux Instance by using Ubuntu 22.04 and wait for finished creation.

### 3. Create Window Instance ###

- Create Window Instance by using Window Server 2022 and wait for finished creation.
