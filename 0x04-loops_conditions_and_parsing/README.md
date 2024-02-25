			#0x04-loops_conditions_and_parsing README file



Last Updated: 25/02/2024;
Contributor(s): MyAtlas0;


TASKS:

0. Create a SSH RSA key pair

#mandatory
Read for this task:

Linux and Mac OS users
Windows users
man: ssh-keygen

You will soon have to manage your own servers concept page hosted on remote data centers. We need to set them up with your RSA public key so that you can access them via SSH.

Create a RSA key pair.

Requirements:

Share your public key in your answer file 0-RSA_public_key.pub
Fill the SSH public key field of your intranet profile with the public key you just generated
Keep the private key to yourself in a secure location, you will use it later to connect to your servers using SSH. Some storing ideas are Dropbox, Google Drive, password manager, USB key. Failing to do so will prevent you to access your servers, which will prevent you from doing your projects
If you decide to add a passphrase to your key, make sure to save this passphrase in a secure location, you will not be able to use your keys without the passphrase
SSH and RSA keys will be covered in depth in a later project.

# Filename: 0-RSA_public_key.pub




1. For Best School loop

#mandatory
Write a Bash script that displays Best School 10 times.

Requirement:

You must use the for loop (while and until are forbidden)
Note that:

The first line of my Bash script starts with #!/usr/bin/env bash
The second line of my Bash scripts is a comment explaining what it is doing

# Filename: 1-for_best_school




2. While Best School loop

#mandatory
Write a Bash script that displays Best School 10 times.

Requirements:

You must use the while loop (for and until are forbidden)

# Filename: 2-while_best_school



3. Until Best School loop

#mandatory
Write a Bash script that displays Best School 10 times.

Requirements:

You must use the until loop (for and while are forbidden)

# Filename: 3-until_best_school



4. If 9, say Hi!

#mandatory
Write a Bash script that displays Best School 10 times, but for the 9th iteration, displays Best School and then Hi on a new line.

Requirements:

You must use the while loop (for and until are forbidden)
You must use the if statement

# Filename: 4-if_9_say_hi
