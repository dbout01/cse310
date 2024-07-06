# CSE 310 - Module Report

Name: Dylan Butterfield

## Part 1 - Module Planning

This section should be filled on the first Monday of the Sprint and submitted

### Section 1.1 - Module Selection

1. What Sprint is this for (1-5)? 5

2. Select the Module (with a single X) that you will do this Sprint:

|Module                   |Selected Module|
|-------------------------|---------------|
|Cloud Databases          |               |
|Data Analysis            |               |
|Game Framework           |               |
|GIS Mapping              |               |
|Mobile App               |               |
|Networking               |       X       |
|SQL Relational Databases |               |
|Web Apps                 |               |
|C++                      |               |
|Java                     |               |
|Kotlin                   |               |
|Erlang                   |               |
|TypeScript               |               |
|Rust                     |               |
|Choose Your Own Adventure|               |

3. Find the list of unique requirements for your selected module in the Module Summary in Canvas.  In some circumstances, you will need to modify the requirements based on the technology or language you selected.  For the Choose Your Own Adventure, you need to create your own requirements.  List the unique module requirements below:
    Write a program that allows one computer to communicate with another computer using the following:
    - Client-Server Model—You will need to write one program for the client and one program for the server.
    - The client must send a request to the server. A response must be sent back and used (e.g. displayed)
    - You can use either TCP or UDP.
    - Provide support for at least three different kinds of requests that the server or the peer can respond to.

### Section 1.2 - Planning

During the Sprint, you will spend 4 hours in class meetings, 4 hours on your team project (2 of which during class), and 10 hours on your selected module.  Make a plan for your 10 hours by answering the questions below.  You should refer back to this plan and make adjustments during the Sprint.

1. What sources have you selected to learn the technical material?
    - https://en.wikipedia.org/wiki/OSI_model
    - https://en.wikipedia.org/wiki/Client%E2%80%93server_model
    - https://www.howtogeek.com/190014/htg-explains-what-is-the-difference-between-tcp-and-udp/

2. What is your plan to practice the new material?  In other words, what is the order in which you plan to learn the material before working on your demonstration software?
    1. Read through all documentation from #1
    2. View YouTube tutorials for examples
    3. Begin basic structure of project (files & accompanying code)

3. What demonstration software do you plan on submitting at the end of the Sprint (note that this can and may change)?
    1. Python Files
    2. Socket
    3. OS Module
    4. Pip

4. Identify the days, times, and locations that you will work on the module.
    - Monday 4/29 & 5/6, ~17:30-19:00 both days
    - Tuesday 4/30 & 5/7, ~12:00-14:00 both days
    - Wednesday 5/1 & 5/8, ~07:00-09:00 both days
    - Thursday 5/2 & 5/9, ~12:00-14:00 both days
    - Friday 5/3 & 5/10, ~07:00-09:00 both days
    - Locations: Apartment & Apartment Clubhouse

5. Identify both a technical risk and a behavioral risk that you antcipate may occur during this Sprint.  What is your mitgigation plan?
    Technical Risk
    - Running into server connection errors
        Mitigation Plan
        - thorough testing and reviewing of server connection & setups
    Behavioral Risk
    - Getting lazy
        Mitigation Plan
        - Making sure I'm held accountable


## Part 2 - Time Log

This section should be filled out during the Sprint. 

Record all CSE 310 work that you do on your individual module or the team project.  Include time learning, practicing, developing, testing, and documenting.  Don't include time spent in the 4 class meetings (Planning, Stand-Up, Team Review, and Individual Review).  You will need to sum of these hours at the end of the Sprint. Note that the hours you report will affect your grades.

Note that `IM` stands for Individual Module and `TP` stands for Team Project.  

|Date      |Start Time|IM or TP|Description                                 |Hours:Minutes|
|----------|----------|--------|--------------------------------------------|-------------|
|6/24      |1036      |IM      |Module Planning                             |00:39        |
|6/25      |1230      |IM      |Researched TCP vs UDP protocols             |01:03        |
|6/25      |1330      |IM      |Implemented basic TCP server                |00:57        |
|6/26      |1015      |TM      |Research on client-server implementation    |01:00        |
|6/27      |1630      |TM      |Debugged connection issues                  |01:00        |
|6/27      |1205      |IM      |Wrote tests for server requests handling    |01:00        |
|6/28      |0712      |IM      |Began module.md & readme.md                 |00:49        |
|6/28      |1341      |IM      |Optimized server code for efficiency        |00:38        |
|6/28      |1605      |IM      |Revised client handling for multiple connections   |01:31 |
|6/29      |1102      |IM      |Continued module.md & readme.md             |00:14        |
|6/30      |1450      |IM      |Changed client code for better error handling      |00:30 |
|7/1       |1015      |TM      |Worked w/ Logan on fixing layering issues   |01:00        |
|7/1       |1731      |IM      |Reviewed and finalized all project components      |01:13 |
|7/2       |0820      |IM      |Ran final tests and closed project issues          |00:39 |
|7/6       |1832      |IM      |Finished readme & module & recorded demo    |00:57        |

TM: 3 hours

_Note: Add more rows as needed._


## Part 3 - Module Results

This section should be filled out at the end of the Sprint and submitted.

1. Put your GitHub link for your demonstration software here: https://github.com/dbout01/FileMe

2. Put your YouTube link for your code walkthrough and demo video here: https://youtu.be/PkokW5_wPFY

3. Complete the following checklist by either indicating "Yes" or "No". If you indicate "No" then provide an explanation of why beneath the table.

|Question                                                    |Response|
|------------------------------------------------------------|--------|
|Are the links above public and working?                     |  Yes   |
|Did you complete all the unique requirements for the module?|  Yes   |
|Did you write at least 100 lines of code?                   |  Yes   |
|Did you fully complete the readme.md file?                  |  Yes   |
|Did you put the readme.md file in GitHub in the top folder? |  Yes   |

4. If you completed a Stretch Challenge (as shown in the Module Description document in Canvas) then describe what you did.  If you did the Choose Your Own Adventure module, then you get to decide what qualifies as a Stretch Challenge.
    - "Provide support for at least three different kinds of requests that the server or the peer can respond to."

5. Did you change your selected module during the middle of the Sprint?  If yes, then describe what you changed it to, when you changed it, and why you changed it.
    N/A

6. Using the log above, fill in the total hours and minutes you spent on the individual module:

|Activity         |Total Hours:Minutes|
|-----------------|-------------------|
|Individual Module|       10:03       |

7. What strategies (behavioral and technical) worked well during this Sprint?  What did not work well?  List some possible ways that you can improve next Sprint.
        What worked well
        Behavioral
        - Motivation/excited to make the application work properly
        Technical
        - Having all functions behave properly

        What didn't work well
        Behavioral
        -  Found myself putting off research & tasks
        Technical
        - Coming up with extra functionality

        Way to improve next sprint
        - Take what I've learned in each module throughout each Sprint and apply it to
        my group project
