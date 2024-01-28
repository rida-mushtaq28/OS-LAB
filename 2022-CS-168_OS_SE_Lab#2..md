## **Installation of the Ubuntu operating system and Compilers**

> ![CS Dept Logo](C:\Users\dell\OneDrive\Desktop\CS Dept Logo.png)

Session: 2022 – 2026

> **Submitted by:**
>
> Rida Mushtaq 2022-CS-168
>
> Asim Ali Murtaza 2022-CS-175
>
> **Supervised by:**
>
> Mr.Nauman Shafi
>
> Department of Computer Science

**University of Engineering and Technology**

> **Lahore Pakistan**

#### **Lab2 Task1:**

**“Ubuntu Installation Procedure”**

1. Download Virtual Box or VMware Player 17 and install it on your machine. Add the ISO image to Virtual Box to add it to your library.

   ![Screenshot (377)](C:\Users\dell\OneDrive\Pictures\Screenshots\Screenshot (377).png)

   

3. Start the Ubuntu and let it power on. After powering it on, VM will boot into Ubuntu.

   ![IMG-20240127-WA0029](C:\Users\dell\OneDrive\Desktop\IMG-20240127-WA0029.jpg)

4. Then the screen will appear,select the language and click on installation button.

   ![IMG-20240127-WA0026](C:\Users\dell\OneDrive\Desktop\IMG-20240127-WA0026.jpg)

5. Then select the keyboard layout.

   ![IMG-20240127-WA0027](C:\Users\dell\OneDrive\Desktop\IMG-20240127-WA0027.jpg)



6. Select the normal installation,and click continue.

   ![IMG-20240127-WA0028](C:\Users\dell\OneDrive\Desktop\IMG-20240127-WA0028.jpg)



7. Then select the erase disk,and click on install now.

   ![Screenshot (386)](C:\Users\dell\OneDrive\Pictures\Screenshots\Screenshot (386).png)

8.  Give the required Information,click continue.

![Screenshot (385)](C:\Users\dell\OneDrive\Pictures\Screenshots\Screenshot (385).png)

9. Now wait for the installation.

   ![Screenshot (382)](C:\Users\dell\OneDrive\Pictures\Screenshots\Screenshot (382).png)

10. After installation it will ask for restart , click on restart now and let it reboot.

    ![Screenshot (387)](C:\Users\dell\OneDrive\Pictures\Screenshots\Screenshot (387).png)



11. After rebooting it will ask about the password and after entering it you will see the Ubuntu on your Virtual box.

    ![Screenshot (388)](C:\Users\dell\OneDrive\Pictures\Screenshots\Screenshot (388).png)



#### **Compiler Installations**

12. Open Terminal on the Ubuntu.

    For GCC Compiler Installation type " sudo apt install gcc " on the terminal .It will ask for continue download press "y" , it will start downloading and installing GCC compiler. For checking if it is installed type "gcc --version".

    

    ![WhatsApp Image 2024-01-27 at 23.23.38_2abaa5ae](C:\Users\dell\OneDrive\Desktop\WhatsApp Image 2024-01-27 at 23.23.38_2abaa5ae.jpg)

For G++ Compiler Installation type " sudo apt install g++ " on the terminal .It will ask for continue download press "y" , it will start downloading and installing GCC compiler. For checking if it is installed type "g++ --version".

![WhatsApp Image 2024-01-27 at 23.23.38_9ad3d69a](C:\Users\dell\OneDrive\Desktop\WhatsApp Image 2024-01-27 at 23.23.38_9ad3d69a.jpg)

Finally gcc & g++ compiler successfully installed.



#### **TASK 2:**

**"Testing gcc & g++ compiler on Ubuntu"**

1. Open any code editor , write the given code and save file "task1.cpp".

   ![IMG-20240128-WA0001](C:\Users\dell\OneDrive\Desktop\IMG-20240128-WA0001.jpg)

2. Open the terminal compile and run the code using these commands

   "g++ -o obj task1.cpp"

   then,

   "./obj" and check the output.

   ![IMG-20240128-WA0003](C:\Users\dell\OneDrive\Desktop\IMG-20240128-WA0003.jpg)

3. Open any code editor , write the given code and save file "task2.c".

   ![IMG-20240128-WA0004](C:\Users\dell\OneDrive\Desktop\IMG-20240128-WA0004.jpg)

4. Open the terminal compile and run the code using these commands

   "gcc -o obj task1.c"

   then,

   "./obj" and check the output.

   ![IMG-20240128-WA0002](C:\Users\dell\OneDrive\Desktop\IMG-20240128-WA0002.jpg)

   

   That's it, both compilers are working.

   

   #### **Github Repository**

   https://github.com/rida-mushtaq28/OS-LAB

   

