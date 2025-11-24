# 🏥 Hospital Appointment Scheduler README

## Hospital Appointment Scheduler 

## Overview of the Project
This is a simple, command-line interface (CLI) application for managing hospital appointments. It allows a user to schedule new appointments, view all scheduled appointments, filter appointments by date, and cancel existing appointments. The data is stored in memory as a Python list of dictionaries and is not persisted upon exiting the application. A basic check is included to prevent double-booking the same doctor at the exact same date and time.

## Features
Add Appointment: Book a new appointment by providing the patient name, doctor name, date, time, and reason for the visit. Includes a check for doctor availability (no simultaneous appointments).

View All Appointments: Display a numbered list of all currently scheduled appointments.

View Appointments by Date: Filter and display appointments scheduled for a specific date (YYYY-MM-DD).

Cancel Appointment: Remove a scheduled appointment by its list number.

## Technologies/Tools Used
**Language:** Python 3 (The code is written in standard Python 3 and uses basic data structures and functions).

**Environment:** Any standard command-line environment or integrated development environment (IDE) that can run Python scripts.

## Steps to Install & Run the Project
**Prerequisite:** Ensure you have Python 3 installed on your system.

**Save the Code:** Save the provided code into a file named scheduler.py.

**Open Terminal/Command Prompt:** Navigate to the directory where you saved scheduler.py.

**Run the Script:** Execute the file using the Python interpreter:

Bash

python scheduler.py
Use the Menu: The application will start and present a menu. Follow the on-screen prompts to interact with the scheduler.

## Instructions for Testing
Follow the steps below to test the main functionalities of the scheduler:

**Add an Appointment (Option 1):**

*Choose option 1.*

Enter details, e.g., Patient: John Doe, Doctor: Smith, Date: 2025-12-01, Time: 10:00, Reason: Checkup.

Verify the success message.

Add a Conflicting Appointment (Option 1):

Choose option 1 again.

Try to book another appointment for Dr. Smith on 2025-12-01 at 10:00.

Verify the message: "This doctor already has an appointment at that time."

View All Appointments (Option 2):

*Choose option 2.*

Verify that the appointment(s) you added are listed.

View Appointments by Date (Option 3):

*Choose option 3.*

Enter the date 2025-12-01.

Verify that only appointments on that specific date are listed.

Cancel Appointment (Option 4):

*Choose option 4.*

A list of appointments will appear. Enter the number corresponding to the appointment you want to cancel (e.g., 1).

Verify the cancellation message.

*Exit (Option 5):*

Choose option 5 to exit the program.

## SCREENSHOTS
<img width="1567" height="1222" alt="image" src="https://github.com/user-attachments/assets/1f985f78-1239-488b-ab28-dbf19648f3aa" />
<img width="1501" height="1018" alt="image" src="https://github.com/user-attachments/assets/8ac41930-b25c-4e19-a1fa-ab9e00fa6253" />

