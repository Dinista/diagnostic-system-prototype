# Diagnostic-System-Prototype

## Introduction

This is a portuguese prolog prototype of a medical diagnostic system using SWI-Prolog, having the following functions:

- <b> Patients control module</b>: Inclusion, consultation, alteration and exclusion of patients data in a pacientes.txt file database.
- <b> Diseases local database</b>:  The source code has ten types of diseases which it's storedge at local memory.
- <b> Diagnostic module </b>:
  - Console interation asking wich symptoms the patient have (EX: fever, headache, nausea).
  - Shows the most likely disease of the patient based on his symptoms (compares to the diseases local database).
  The diagnostic is made by considering the percentage of common symptoms, if there is more than one type of disease related to the symptoms reported by the patient, the program shows a list
  of possibles diases and the respective percentage probability.
  - Shows which symptoms of the diagnosed disease the patient presents and what other symptoms the user did not report.
  
<b> First Project of the class Logic and Functional Programming Paradigms. </b>


## How to use

The Pacientes.txt must be in local C disk
      
    C:\Pacientes.txt

Start the program in SWI prolog typing:
  
    init.

## Unit tests

10 unit tests were implemented.
To execute type:

    run_tests.
