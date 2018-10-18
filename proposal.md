# X-Team NN Project Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description
A senior living facility is looking for a new way to track patient's heartrates and ensure that their patients maintain a healthy heart rate. The facility wants patients with an unsafe heart rate to be seen by a nurse or doctor as soon as possible and the doctor's should be able to see their heart rate history when checking up on a patient. 

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file).

   ###### Heart Rate Prioritization and Storage for Aged Patients (70-80 yrs old)


2. Output: Describe the output your program will produce.  Include and example format of the output produced.
    ###### Print severals lines and each line includes the name of a patientl, the date they do health checks and the heart rates of that patient at each health check. The order of each line will follow the order they are in the priority queue.

    ###### Example output:
    ###### Patient1:   date1: heart rate 1  date2: heart rate 2  date3: heart rate 3
    ###### Patient2:   date4: heart rate 4  date5: heart rate 5  date6: heart rate 6  date7: heart rate 7
    ###### Patient3:   date8: heart rate 8  date9: heart rate 9  


3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.



4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

   ###### The interface should allow users to search for a patient and then add their heart rate at that moment in time into the computer.
   When a patient is searched for the patient's heart rate history should appear in a list on the screen. The list should alert the
   user if the heart rate entered for that day is alarming and the hearrates of the previous days.


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
   ###### We will use a linked list to hold a patients data. We will use a priority queue to hold each patient and priority will be
   ###### established based off how far the current heart rate is from the mean.


Name each interface or class and briefly describe its function or purpose.
###### The linked list will allow us to gain access to a patients data in a chronological order and allow the user to see how it has 
###### changed over time. The priority queue will allow a doctor or a nurse to be alerted when someones heart rate is too high or to low   
###### so the patinets with a dangerous heart rate will be seen first.


## Edit and Submit this file and any figures referenced by this document.

