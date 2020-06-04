# Bin-Pack-Java
Bin Packing Algorithm Implemented In Java

PROJECT - A5
DESIGN AND ANALYSIS OF ALGORITHMS
TINOTENDA MACHIDA
......................................................................................................................................

#INTRODUCTION#
The Bin-Packing problem is a problem whereby we are given several objects, each
with its own size. We are also given fixed size containers or so-called bins. The
bins have fixed capacity and we would like to fit in as many of the objects in the
bins while using the smallest number of bins possible. We would like to minimize
the number of bins we use.
This is what’s called the Bin-Packing problem. To put this in mathematical
terms, we are given a set S, of fixed size objects, each with each own fixed weight
S1, S2, S3….Sn. We are also given an infinitely large number of bins which all have
the same fixed size capacity C.
Our goal is to make sure that we determine the number of bins that it takes
to fit all the objects in the bins and we also find the best way of doing so using as
few bins as possible. This problem is shown to be a NP- hard problem.
There are several heuristics we could use to solve the problem, but different methods give different answers. An example would be that we choose the
number of objects which fit best (also know as best fit), or as we shall focus on in
this project, we shall be particularly looking at “first fit”.
This means is that we would be putting our objects in the very first bin we
find them to fit them. If we don’t have space or if we don’t have any suitable bins
at hand, we go ahead and get a new one. This will be our approach through and
through till we run out of all the figures we want to put into bins.

#HARDWARE/ SOFTWARE ENVIRONMENT REQUIREMENTS#
Through the development of the project, it was top priority to ensure the most
minimum software and hardware requirements to run the project. The algorithm
for this project was developed in JAVA and runs through a command line interface
to get it running. It should run on most modern-day computers easily, if the input
values for the algorithm are not too large. Nonetheless I will just go through some
of the requirements needed into to run the actual project

For you to be able to run and install JAVA you are going to need at least the following:
RAM: 128 MB; 64 MB for Windows XP (32-bit)
Disk space: 124 MB
Browsers: Internet Explorer 7.0 and above, Firefox 3.6 and above

Since the project is developed in JAVA, the host machine will need to be JAVA
compliant in terms of software the most compatible operating systems are listed
below
If you are running any of the following operating systems:
• Windows 10 (8u51 and above) • Windows 8.x (Desktop)
4
• Windows 7 SP1
• Windows Vista SP2
• Windows Server 2008 R2 SP1
(64-bit)
• Windows Server 2012 and
2012 R2 (64-bit)
• Intel-based Mac running Mac
OS X 10.8.3+, 10.9+
• Oracle Linux 5.5+1
• Oracle Linux 6.x (32-bit), 6.x
(64-bit)2
• Oracle Linux 7.x (64-
bit)2 (8u20 and above)
• Red Hat Enterprise Linux
5.5+1, 6.x (32-bit), 6.x (64-
bit)2
• Red Hat Enterprise Linux 7.x
(64-bit)2 (8u20 and above)
• Suse Linux Enterprise Server
10 SP2+, 11.x
• Suse Linux Enterprise Server
12.x (64-bit)2 (8u31 and
above)
• Ubuntu Linux 12.04 LTS,
13.x
• Ubuntu Linux 14.x (8u25
and above)
• Ubuntu Linux 15.04 (8u45
and above)
• Ubuntu Linux 15.10 (8u65
and above)
Then you should find yourself more than equipped to run the project. If you
don’t have JAVA on your machine already, here’s a heads up. You are also going to need a you are also going to need JAVA SDK or JRE 1.6 or higher if you
don’t have it installed already.

#1.SETTING UP
PRE-LIMINARY REQUIREMENTS
Before running the project there are a few things needed in the set-up process. You will
need to make sure you have the following.
• RAM: 128 MB;
• Disk space: 124 MB
• Browsers: Internet Explorer 7.0 and above, Firefox 3.6 and above
• JAVA SDK or JRE 1.6 or higher
DOWNLOADING THE FILE
Once you have the setup complete, you may now proceed to download the
file named A5.Java
Make sure that you download the file to a disk location that you have administrative rights to run the file. This should be just one file. Once you have
downloaded the file, you may proceed to the execution stage.


#2.GETTING TO THE FILE
To execute the file, you are going to need a command line interface. Here we
will explain how to navigate to the file after downloading it.
WINDOWS USERS
1. Look for the button with the windows logo on your keyboard. It’s usually located in the lower left corner of you keyboard. ⊞ Win
2. Once you have found the windows logo. Press it.
3. A start menu should immediately show up
4. Once the start menu shows up you should see a search bar right at the
bottom of the Start Menu.
5. In the bar type in CMD. You should see the program, with an icon like
this .
6. Press enter or right click on the icon.
7. This should open your Command Line Interface, in this case Command
Prompt.
8. In the command prompt, use basic commands to navigate to the
folder location where you downloaded the file.
MAC USERS
1. Click the spotlight icon, alternatively you can enter ⌘ + space .
2. Once the search bar is open type in “Terminal” in the search box
3. You should see a terminal icon such as the following Terminal.
4. Double-click on the icon. This should open the Command Line Interface for MAC.
5. Use basic terminal commands to navigate to the location where you
downloaded A5.java to.

#3.EXECUTION
1. Once you have reached the location type in javac A5.java to compile
the file.
2. After a successful compilation you may type in java A5 to run the file.
Once you type this in the program should immediately start running.

1.BIN CAPACITY
28
Once the program is running. It will prompt you to enter BIN CAPACITY.
The BIN CAPACITY is the total amount of value/size that the bin can accommodate before creating a new bin.
Note: 0, and non discreet positive integers are not accepted.
You may only enter positive, integers.
Entering an invalid value will result in the program showing you the following.
Once the BIN CAPACITY value has been accepted it should show the
following
Note: If you intend to run a quick test. It’s advised to not use large bin
capacities with randomized input and large bin capacities with small
object values.

2.NUMBER OF OBJECTS
29
After you have entered the Capacity of your Bin and the program has
accepted it. It will prompt you to enter the number of objects you wish
to work with. For TESTS smaller values are recommended especially if
you wish to enter the number of objects manually.
Note: You may only enter positive, integers.
0, and non discreet positive integers are not accepted.
Entering an invalid value will result in the program showing you the following.
Once your Number of Objects has been accepted. The program should
show you the number of objects you decided to work with like the following (5 Objects selected in this case)
30
Note: If you intend to run a large test and manually enter your object/size values. It’s not advised to select a large set of objects as you
would have to manually enter their individual values i.e. If you enter
your Number OF Objects to be 100, you will have to manually enter all
of the 100 individual values.
3.OBJECT SIZES/VALUES
The program offers you two ways of inputting the object values/sizes.
You can either manually enter the values or you can use randomized
values for your object size values. You may choose the one you see
most fit for your application.
3.1 USING RANDOMIZED VALUES/SIZES
If you decide to use the randomized values, you will not need to worry
about entering the object values manually. The program will enter
these for you. 

This comes handy when running tests for a large set of objects and
large bins.
3.2 MANUALLY INPUTTING VALUES/SIZES
If you have chosen to input the values manually the program should
show you this
You may enter in positive values for your sizes. The program will accept
both integers and doubles as your values but will not accept 0 or negative values as your input.
It will prompt you continuously up until you have reached the number
of objects you requested to work with.
Note: You may only enter positive, integers and doubles.
0, and negative values are not accepted.
3.3 VALUE SUMMARY
Before you proceed to execute the program. It will show you a summary of the parameters selected.
If you have chosen random values these will be shown to you here as
well. 

Click OK to proceed to the next menu
3.4. VALUE CONFIRMATION
Before you run the algorithm, it will give you a chance to change your parameters. 
33
NO- If you are not happy with the values you may click NO and this will take
you back to selecting the BIN CAPACITY
CANCEL – This will exit the program
YES – If you are happy with the parameters you may click and the Algorithm
will start running.
4.INTERPRETING RESULTS
4.1 SUCCESSFUL EXECUTION
Once the program has finished running it should show you this message to
indicate that it ran successfully. You may click OK to see the summary
4.2 RESULT SUMMARY
A successful run should show you a brief summary which shows the time and
the number of bins used for the Algorithm
34
The program gives you an option to run a new set of values. The detailed results to the execution will be shown in your Command Line Interface.
• Selecting YES will take you to the BIN CAPACITY selection again.
• Selecting NO will exit the program and display the following
• If you would like to run the program again then select YES
4.3 DETAILED REPORT
A detailed report is captured in your Command Line Interface’s terminal each
run. To see the detailed report. Open your Command Line Interface.
The report will show you the order of events in which the algorithm made its
calculations. 
35
It should you something like the following
.
• NEW BIN CREATED – The algorithm creates a new Bin each time an element cannot fit in the current bin it’s working in
• Total Bins Used – These are the total number of Bins used to pack the
elements
• Total Time Spent - This is the total time the Algorithm part of the program took to pack the objects
36
• Bin X Contains Values- This shows individual values contained in each
bin and how they were packed.
