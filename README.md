### Parallels macOS Kali Password Reset

I've been lately using my Windows box more often for hacking due to all of the famous M1 chip thing in Macbook Pro.
Therefore my parallels on macOS box was left aside enough time to forget the password. Oh-oh...

If this sounds familiar - THIS IS FOR YOU!

It took me multiple resources to get to where I needed and I decided to summarise steps that actually worked in this case.

1. Reboot Parallels and press E

3. You  will enter the Boot Mode:

<img width="1250" alt="image" src="https://github.com/0xsisu/parallels_macOS_kali_password_reset/assets/78635937/70c09541-e20a-414b-8015-f2ebfc578478">

3. Move your cursor to the end of the linux line and append the following:

   **rw init=/bin/bash**

4. Hit Ctrl-x to boot

5. You will enter root bash command line, type the following

   **passwd username** 

for example passwd parallels

6. You will be offered to add new password and confirm

7. reboot (sometimes it doesn't work so you will have to reboot the host. Yeah, I know...make sure you SAVED whatever needed prior.)

Hope that helped :)

