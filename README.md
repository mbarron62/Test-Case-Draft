# Test-Case-Draft

## Test Details

#### Test Case ID:
01

#### Test Case Name:
Database Connection Requirements

#### Component:
The database used for *PLEX*'s "build mode." Handles all the connectivity with the database. It also fetches and returns query results. 

#### Test Game Designer:
Jade

#### Creation Date:
12/2008

#### Modified By:
Jalen Mojica

#### Modified Date:
10/09/2018

#### Requirements Covered:
* Players must be able to connect to the database

#### Test Description/Purpose:
* Must be able to connect to the database so players can play with each other in "build mode"

#### Pre-Test Conditions:
* At least 5 consoles/computers running *PLEX*
* At least 5 testers
* A room big enough for the testers and their testing systems
* A playable version of *PLEX*'s "build mode"

## Test Steps: 
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | Set up the testing environment | *PLEX* will run on all computers/consoles being used for testing | |			
| 2 | Gather Testers | There will a sufficient amount of Testers on hand | |			
| 3 | Testers will select the "Build Mode" play option | Testers are taken to the "Build Mode" menu screen | |			
| 4 | Testers will attempt to connect to the database | Testers will connect to the database | |			

## Overall Test Status:
Testing is being done in the QA Environment. Currently, testing is being done to ensure that players will connect to each other when selecting "Build Mode." Once testing is complete in the QA Environment, testing will be done in the Staging Environment with Blackbox Testers.

## Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 10/09/2018 | | Only a few Testers could connect to the database |			
| 2 | 10/13/2018 | | Testers could not connect to the database |			
| 3 | 10/14/2018 | | Only a few Testers could connect to the database |	
| 4 | 10/18/2018 | | Testers successfully connected to the database, but could not connect to each other |
| 5 | 11/02/2018 | | Testers successfully connected to the database and were placed in the same lobby |

## Test Details

#### Test Case ID:
03

#### Test Case Name:
Menu Driver Requirements

#### Component:
Menu Driver that is in charge of all of *PLEX*'s menu screens

#### Test Game Designer:
Jade

#### Creation Date:
12/2008

#### Modified By:
Jalen Mojica

#### Modified Date:
10/09/2018

#### Requirements Covered:
* Loading the appropriate menu when asked
* Keeping track of where the selector is

#### Test Description/Purpose:
* To ensure that the game will always bring up the correct menu at the correct time

#### Pre-Test Conditions:
* A computer/console to run *PLEX* on
* At least one tester (can be developer)
* All needed menus added into *PLEX*
* A way to open up menus in *PLEX*

## Test Steps: 
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | Set up the testing environment | *PLEX* will run on all computers/consoles being used in testing | |			
| 2 | Gather Testers | There will be a sufficient amount of Testers on hand | |			
| 3 | Testers will start the game | Testers will be taken to *PLEX*'s main menu | |			
| 4 | Testers will choose the "Build Mode" play option | Testers are taken to the "Build Mode" menu screen | |			
| 5 | Testers will choose the "Highscore" menu button during "Build Mode" gameplay | Testers are taken to the "Highscore" menu screen  | |			
| 6 | Testers will choose the "Back" option or an equivalent if available | Testers will be taken back to "Build Mode"'s gameplay | |			
| 7 | Testers will choose the "Back" option or an equivalent if available | Testers will be taken back to *PLEX*'s main menu | |			
| 8 | Testers will choose the "Back" option or an equivalent if available | Testers will be taken back to *PLEX*'s main menu | |			
| 9 | Testers will choose the "Story Mode" play option | Testers will be taken to the "Story Mode" menu screen | |			
| 10 | Testers will select the "New Game" play option | Starting game animations will play. If there are none, Testers will be taken to the "Story Mode"'s gameplay | |
| 11 | Testers will choose the "Back" option or an equivalent if available | Testers will be taken back to the "Story Mode" menu screen | |
| 12 | Testers will choose the "Load Game" or an equivalent option | Testers will be taken to the "Load Game" menu screen | |
| 13 | Testers will choose the "Back" option or an equivalent if available | Testers will be taken back to the "Story Mode" menu screen | |
| 14 | Testers will choose the "Back" option or an equivalent if available | Testers will be taken back to *PLEX*'s main menu screen | |
 

## Overall Test Status:
Testing is being done in the Development Environment to ensure that there are menu transitions. Once that is complete, testing will be moved on to the QA Environment to make sure that the proper menus are displayed. Finally, Blackbox testing will be done in the Staging Environment as a precaution. It is possible that the Blackbox testers will open menus in their own ways which could lead to the wrong menu appearing.

## Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 10/08/2018 | | The "Build Mode" play option is non-functional |			
| 2 | 10/09/2018 | | The "Build Mode" play option is functional. The highscore menu appears when prompted |			
| 3 | 10/12/2018 | | The "Story Mode" play option leads to the "Build Mode" menu |
| 4 | 10/13/2018 | | The "Story Mode" menu appears when "Story Mode is selected, but no other options are functional |
| 5 | 10/17/2018 | | The "New Game" option leads to "Build Mode"'s gameplay |
| 6 | 10/19/2018 | | All menus work correctly. There is no way to get out of the "Load Game" menu without choosing a load file |
| 7 | 10/20/2018 | | All correct menus appear in the correct area with the proper commands |
