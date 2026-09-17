## Overview of tasks
MY PDB NAME: LO_PDB_28201
USERNAME: LOKO_PLSQLAUCA_28201

## Task 1: Creation of a New PDB
I created the required PDB:
`LO_PDB_28201`
The PDB was successfully opened and verified in `READ WRITE` mode.
The required user was also verified inside the PDB:
`LOKO_PLSQLAUCA_28201`
## Task 2: Creation and Deletion a Temporary PDB
I created the temporary PDB:
`LO_TO_DELETE_PDB_28201`
I verified that the PDB existed, then deleted it and verified that it was no longer present.
## Task 3: Oracle Enterprise Manager (O.E.M)
I accessed Oracle Enterprise Manager and opened the dashboard for my PDB.
The dashboard displayed Oracle database information including status, resources, SQL monitoring, performance, and recent incidents.
## Task 4: My Work Documentation
All practical work and supporting screenshots are documented in this public GitHub repository.

## ORACLE environment used
I used SQL*plus command for task 1 & 2 and O.E.M (Oracle Enterprise Management) for the task 3

## Challenges faced
During the practical work, I encountered an insufficient privileges error when initially attempting to open the PDB using the SYSTEM account. I resolved this by connecting with SYS as SYSDBA.
I also encountered an issue with the OEM container connection because the PDB did not initially have an HTTPS port configured. I configured an EM Express HTTPS port for the PDB and successfully accessed the OEM dashboard.

## Integrity Statement 
I didn't use ChatGPT or any ai but I use SQL book like Oracle PL/SQL Programming BY Bill Pribyl and steven Feuerstein to understand the work because I'm new in this environment and video for YouTube to be familiar with GitHub .
