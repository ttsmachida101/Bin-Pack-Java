# Bin-Pack-Java
Bin Packing Algorithm Implemented In 'Java' PROJECT -
by

TINOTENDA MACHIDA
......................................................................................................................................
# INSTRUCTION MANUAL

## INTRODUCTION
The Bin-Packing problem is a problem whereby we are given several objects, each
with its own size. We are also given fixed size containers or so-called bins. The
bins have fixed capacity and we would like to fit in as many of the objects in the
bins while using the smallest number of bins possible. We would like to minimize
the number of bins we use. 

*Say we are given a set S, of fixed size objects, each with each own fixed weight
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
at hand, we go ahead and get a new one. 


This will be our approach through and
through till we run out of all the figures we want to put into bins.

## HARDWARE/ SOFTWARE ENVIRONMENT REQUIREMENTS#
* RAM: 128 MB; 
* Disk space: 124 MB
* JAVA SDK or JRE 1.6 or higher


# EXECUTION
* Type in javac A5.java to compile
* After a successful compilation you may type in java A5 to run the file.
Once you type this in the program should immediately start running.

## VALUES
###BIN CAPACITY
* Once the program is running. It will prompt you to enter BIN CAPACITY.
* The BIN CAPACITY is the total amount of value/size that the bin can accommodate before creating a new bin.
* Note: 0, and non discreet positive integers are not accepted.
You may only enter positive, integers.
* Entering an invalid value will result in the program showing you the following.
Once the BIN CAPACITY value has been accepted it should show the
following
* Note: If you intend to run a quick test. It’s advised to not use large bin
capacities with randomized input and large bin capacities with small
object values.

### NUMBER OF OBJECTS
* After you have entered the Capacity of your Bin and the program has
accepted it. It will prompt you to enter the number of objects you wish
to work with.
**For TESTS smaller values are recommended especially if
you wish to enter the number of objects manually.

***Note: You may only enter positive, integers.
0, and non discreet positive integers are not accepted.

**Note: If you intend to run a large test and manually enter your object/size values.

It’s not advised to select a large set of objects as you
would have to manually enter their individual values i.e. If you enter
your Number OF Objects to be 100, you will have to manually enter all
of the 100 individual values.

### OBJECT SIZES/VALUES
The program offers you two ways of inputting the object values/sizes.
You can either manually enter the values or you can use randomized
values for your object size values. 
*You may choose the one you see most fit for your application.

### USING RANDOMIZED VALUES/SIZES
*If you decide to use the randomized values, you will not need to worry
about entering the object values manually. The program will enter
these for you. 

### VALUE SUMMARY
Before you proceed to execute the program. It will show you a summary of the parameters selected.
If you have chosen random values these will be shown to you here as
well. 


### SUCCESSFUL EXECUTION
Once the program has finished running it should show you this message to
indicate that it ran successfully. You may click OK to see the summary

***RESULT SUMMARY
*A successful run should show you a brief summary which shows the time and
the number of bins used for the Algorithm

* The program gives you an option to run a new set of values. The detailed results to the execution will be shown in your Command Line Interface.
* Selecting *YES* will take you to the BIN CAPACITY selection again.
* Selecting *NO* will exit the program 


