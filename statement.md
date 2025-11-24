# Hospital Appointment Scheduler

## Problem Statement

The current process for scheduling, viewing, and managing hospital appointments is often manual, inefficient, and prone to errors such as double-bookings or lost records. Patients and medical staff require a streamlined, accessible system to handle appointments effectively, reduce administrative overhead, and improve overall operational efficiency within a healthcare setting. Without a digital solution, managing patient flow and doctor's schedules becomes a cumbersome task leading to frustration and potential delays in patient care.


## Scope of the Project

This project focuses on developing a command-line interface (CLI) based appointment scheduling system for a hospital setting. The scope includes core functionalities such as adding new appointments, listing all appointments, filtering appointments by date, and canceling existing appointments. The system will primarily manage in-memory data, meaning that all scheduled appointments will be lost once the application is closed. It will not include database integration, user authentication, advanced reporting features, or a graphical user interface (GUI). The primary goal is to provide a functional and intuitive text-based tool for basic appointment management.

## Target Users

The primary target users for this application are:

- Hospital Administrative Staff: Receptionists, secretaries, and clerical workers responsible for booking, managing, and canceling patient appointments.

- Medical Professionals (Doctors/Nurses): Who need to quickly view their daily or upcoming schedules.

- Small Clinics/Practices: That require a simple, cost-effective digital solution for appointment management without the need for complex enterprise systems.

## High-Level Features

- Appointment Creation: Allow users to input and save new appointment details, including patient name, doctor name, date, time, and reason.

- Conflict Detection: Implement a basic mechanism to prevent a doctor from being double-booked at the same time and date.

- Comprehensive Appointment Listing: Provide a way to display all scheduled appointments in an organized, readable format.

- Date-Specific Viewing: Enable users to retrieve and view appointments scheduled for a particular date.

- Appointment Cancellation: Offer the functionality to easily remove an appointment from the schedule.

- Interactive Menu: A user-friendly, text-based menu for navigating and selecting different functionalities within the application.
