# VoteSmart – Online Voting Platform (OOP Project)

## Overview

VoteSmart is a Java application that simulates an **online voting platform** using Object-Oriented Programming (OOP) principles.  
The system models the main processes involved in elections, including managing elections, candidates, voters, constituencies, votes, and fraud reports.

The application allows:

- creating and managing election sessions
- registering candidates and voters
- organizing constituencies and regions
- recording votes
- detecting and storing fraud reports
- generating reports about election results

## Main Classes

- **Alegeri** – represents an election session and stores candidates, voters, votes, constituencies, and fraud reports.
- **Candidat** – models a candidate with information such as name, CNP, and age.
- **Circumscriptie** – represents an electoral constituency containing voters, candidates, and votes.
- **Votant** – models a registered voter with validation for CNP and age.
- **Vot** – represents an individual vote.
- **Regiune** – represents a geographic region.
- **Frauda** – stores information about potential voting fraud.
- **Cases** – implements the commands and functionalities required by the assignment.
- **Eroare** – handles common errors such as missing elections or insufficient command arguments.

## Implementation Details

- The application runs in a loop inside the **App** class and processes commands using a `switch` structure.
- Each component is implemented in separate classes to ensure **modularity and clarity**.
- Data validation is implemented for critical fields such as **CNP and age**.
- Error handling ensures robust execution of commands.
