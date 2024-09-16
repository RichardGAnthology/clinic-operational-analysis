# Clinic Operational Analysis
_Operational analysis of simulated patient-clinic processes._ 

Welcome to my project on analyzing patient wait times and service efficiency at a clinic! This was a hands-on exercise in diving into operational data and uncovering actionable insights to improve patient experience and clinic workflow.

## What's This Project About?

Ever wondered what goes on behind the scenes at a clinic? How long do patients really wait? Does the time of day affect how long they spend with the doctor? This project aims to answer those questions by analyzing patient appointment data. Using Tableau, I've put together some visualizations that shine a light on when and why wait times spike, and how service times vary throughout the day.

## The Data

I worked with a dataset that simulates patient check-ins, appointment times, and how long they spent with the doctor. The dataset includes columns like:

    Appointment Time: When the patient was scheduled to see the doctor.
    Wait Time: How long the patient had to wait before seeing the doctor.
    Service Time: The time spent in consultation.
    Total Time Spent: From arrival to departure.

It's a small but mighty dataset that helps illustrate some interesting trends.

## What Did I Find?

Here are a few key takeaways from the analysis:

    Early Bird Spike: There's a noticeable peak in both wait times and service times during the early morning hours. This could be due to a backlog from the first rush of patients.
    Midday Dip: Things seem to calm down a bit as the morning progresses, with reduced wait times. Maybe the staff gets into the groove by then!
    End-of-Day Crunch: Towards the end of the morning shift, we see an uptick in wait times again, possibly as the clinic prepares for the midday break or shift change.

I've highlighted these insights in the Tableau dashboard, which you can check out below.

## The Visualizations

I used Tableau to create a dashboard that brings these insights to life. Here’s what's included:

    Bar Chart: Comparing service time, wait time, and total time spent relative to appointment times.
![image](https://github.com/user-attachments/assets/e93665e8-743c-4efa-98e9-f3268a51b7d2)

    Line Chart: Showing how wait times fluctuate throughout the day.

Each visualization comes with annotations to make it easier to spot the trends. You can play around with the filters to explore different times of the day.

Process Mapping

To understand the operational flow of the clinic, I also created process maps using Diagrams.net. These maps helped in visualizing the patient journey and identifying potential bottlenecks in the process:

    Current State Process Map: Outlines the existing patient flow from check-in to departure. This helped identify where the longest delays were occurring.
![image](https://github.com/user-attachments/assets/bc45b6a7-7a50-49d0-abe8-a4d51f3e1540)

    Future State Process Map: Suggested an optimized patient flow based on the insights gathered from the data analysis. This map aims to reduce wait times and streamline the consultation process.

These process maps provide a more holistic view of the clinic's operations and highlight opportunities for improvement.

## Check Out the Dashboard

You can view the interactive Tableau dashboard here: https://public.tableau.com/app/profile/richard.g2349/viz/RichardGTestReport/PatientTimeDashboard.

## How to Use This Repo

    Data: You’ll find the dataset I used in the data/ folder. Feel free to explore it or use it for your own analysis.
    Visualizations: The Tableau workbook and some screenshots are in the visualizations/ folder. You can open the Tableau file with Tableau Public or Tableau Desktop to see how it was made.
    Docs: Any additional documentation is in the docs/ folder.

## Wrapping Up

This project was a great exercise in digging into data to find stories and patterns. Hopefully, these insights can spark ideas for improving patient flow and making the clinic experience smoother. If you have any thoughts or questions about the project, feel free to reach out!
