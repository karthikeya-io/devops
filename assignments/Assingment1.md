# Assignment 1 - Basic Linux commands

- Karthikeya Bethu
- karthikeyabethu01@gmail.com

---

## Assignment 1

> Connect and disconnect with login Access
![image](https://github.com/karthikeya-io/devops/assets/82776409/987253b7-c4a1-4aec-9794-9e61530a89c3)
- If tried to login with no existent user, Got a message `user userName does not exist ...`

## Assignment 2
> Password Changing

1. With IneuR0n#42

![image](https://github.com/karthikeya-io/devops/assets/82776409/a85a7b66-8be2-4ac1-bc4b-174f25cc1254)
- It asked to enter the current password, then asked to enter a new password twice and the password changed successfully.

2. with 1234

![image](https://github.com/karthikeya-io/devops/assets/82776409/e5760cb6-562d-4f30-bfe2-a7dca4dace7d)
- The password is not changed with a warning `You must choose a longer password`

3. Just Enter

![image](https://github.com/karthikeya-io/devops/assets/82776409/cc3c048b-07f6-4b86-93ec-07ae3a17b46c)
- With a message `No password has been supplied.` and reprompted to enter new password

## Assignment 3
> Working with Directories

1. `cd /`

![image](https://github.com/karthikeya-io/devops/assets/82776409/95422b97-d08d-4883-9755-5d0f13432e7d)
- changed to root directory with `cd /` and `ls` command listed all the files and directories in that directory

2. `cd /home`

![image](https://github.com/karthikeya-io/devops/assets/82776409/3c8cdbbe-b87a-48f9-81b6-87d3bb4e2bb9)
- The home directory contains folder for the users 

3. `cd ..`

![image](https://github.com/karthikeya-io/devops/assets/82776409/2c5b55cc-2e7b-4c18-97c2-f50d2175ec8a)
- navigated to one directory back.

4. `cd`

![image](https://github.com/karthikeya-io/devops/assets/82776409/fbe9e842-d1aa-4f6c-b090-08c3f0a807b0)
- back to the home directory of the user with command `cd`.

5. `cd /root`

![image](https://github.com/karthikeya-io/devops/assets/82776409/2ba36811-5ac0-4efc-af14-745bd8b9eb61)
- I got error while navigating to root folder even using sudo command probably because I am using WSL.

## Assignment 4
> Working with File Listing

1. `ls`

![image](https://github.com/karthikeya-io/devops/assets/82776409/89bdf798-8cab-49c2-9615-762822a7ebc2)
- navigated to /etc folder and listed all the files with `ls` command.

2. `ls -al`

![image](https://github.com/karthikeya-io/devops/assets/82776409/373eb68f-5c04-49e1-acd3-3bcff1d58e7d)
- this command `ls -al` lists all files and directories in the current directory, including hidden files, in long format.
- It gave additinal details like
  File permissions
  1. Owner and group information
  2. File size
  3. Last modified time
  4. Links
  5. Hidden files

3. `ls -i`

![image](https://github.com/karthikeya-io/devops/assets/82776409/fa6e7794-4bce-46e0-ab65-bc6fc310d39e)

4. `ls --help`

![image](https://github.com/karthikeya-io/devops/assets/82776409/3b7267c0-8d3c-48eb-b7c7-aeb5e1f652fb)

## Assignment 5
> Know where you are and where you working	

1. `pwd`

![image](https://github.com/karthikeya-io/devops/assets/82776409/d1854c08-c8cc-4dd2-896e-ef5a9487e2e6)
- gives the present working directory

2.`cd /var`
![image](https://github.com/karthikeya-io/devops/assets/82776409/1f3e422f-fd61-4f51-b910-48cca61e4628)


