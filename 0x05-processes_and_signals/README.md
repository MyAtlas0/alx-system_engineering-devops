			#0x05-processes_and_signal README File


Last Update: 24/02/2024;
Contributor(s): MyAtlas0;


TASKS:



0. What is my PID

#mandatory
Write a Bash script that displays its own PID.

# Filename: 0-what-is-my-pid



1. List your processes

#mandatory
Write a Bash script that displays a list of currently running processes.

Requirements:

Must show all processes, for all users, including those which might not have a TTY
Display in a user-oriented format
Show process hierarchy

# Filename: 1-list_your_processes



2. Show your Bash PID

#mandatory
Using your previous exercise command, write a Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.

Requirements:

You cannot use pgrep
The third line of your script must be # shellcheck disable=SC2009 (for more info about ignoring shellcheck error here)

# Filename: 2-show_your_bash_pid



3. Show your Bash PID made easy

#mandatory
Write a Bash script that displays the PID, along with the process name, of processes whose name contain the word bash.

Requirements:

You cannot use ps

Here we can see that:

For the first iteration: bash PID is 4404 and that the 3-show_your_bash_pid_made_easy script PID is 4555
For the second iteration: bash PID is 4404 and that the 3-show_your_bash_pid_made_easy script PID is 4557

# Filename: 3-show_your_bash_pid_made_easy



4. To infinity and beyond

#mandatory
Write a Bash script that displays To infinity and beyond indefinitely.

Requirements:

In between each iteration of the loop, add a sleep 2
sylvain@ubuntu$ ./4-to_infinity_and_beyond
To infinity and beyond
To infinity and beyond
To infinity and beyond
To infinity and beyond
To infinity and beyond
^C
sylvain@ubuntu$ 
Note that I ctrl+c (killed) the Bash script in the example.

# Filename: 4-to_infinity_and_beyond



5. Don't stop me now!

#mandatory
We stopped our 4-to_infinity_and_beyond process using ctrl+c in the previous task, there is actually another way to do this.

Write a Bash script that stops 4-to_infinity_and_beyond process.

Requirements:

You must use kill
Terminal #0

sylvain@ubuntu$ ./4-to_infinity_and_beyond
To infinity and beyond
To infinity and beyond
To infinity and beyond
To infinity and beyond
To infinity and beyond
To infinity and beyond
To infinity and beyond
To infinity and beyond
To infinity and beyond
To infinity and beyond
To infinity and beyond
To infinity and beyond
To infinity and beyond
To infinity and beyond
Terminated
sylvain@ubuntu$ 

Terminal #1

sylvain@ubuntu$ ./5-dont_stop_me_now 
sylvain@ubuntu$ 

I opened 2 terminals in this example, started by running my 4-to_infinity_and_beyond Bash script in terminal #0 and then moved on terminal #1 to run 5-dont_stop_me_now. We can then see in terminal #0 that my process has been terminated.

# Filename: 5-dont_stop_me_now



6. Stop me if you can

#mandatory
Write a Bash script that stops 4-to_infinity_and_beyond process.

Requirements:

You cannot use kill or killall

# Filename: 6-stop_me_if_you_can



7. Highlander

#mandatory
Write a Bash script that displays:

To infinity and beyond indefinitely
With a sleep 2 in between each iteration
I am invincible!!! when receiving a SIGTERM signal
Make a copy of your 6-stop_me_if_you_can script, name it 67-stop_me_if_you_can, that kills the 7-highlander process instead of the 4-to_infinity_and_beyond one.

# Filename: 7-highlander



8. Beheaded process

#mandatory
Write a Bash script that kills the process 7-highlander.

# Filename: 8-beheaded_process





