# Software-Test-Automation
# CS 320: Software Testing and Automation

This repository includes my contact service code and JUnit tests from Project One, along with my summary and reflections report from Project Two. These projects helped me practice turning requirements into working code and writing tests to check that the program handles both valid and invalid inputs.

## How can I ensure that my code, program, or software is functional and secure?

I start by checking my code against the requirements and testing more than just the inputs that should work. For the contact service, this included checking for null values, invalid phone numbers, and fields that exceeded the allowed length. I also tested adding, updating, and deleting contacts. For security, I would review how the program handles input, protects information, and uses dependencies. Passing tests is helpful, but I still need to review the code for problems the tests might miss.

## How do I interpret user needs and incorporate them into a program?

I break user needs into smaller requirements that I can build and test. For example, the contact ID needed to be unique and could not be changed after creation. That requirement guided both my code and my tests. If something is unclear, I would ask questions before making assumptions about what the user wants.

## How do I approach designing software?

I start by understanding what the program needs to do and breaking it into smaller parts. In this project, the Contact class handled contact information and validation, while ContactService handled managing contacts. Keeping those responsibilities separate made the code easier to follow and test. I build one part at a time, check my work as I go, and review everything against the requirements before submitting.
