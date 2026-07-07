# GEOL/ENST 253: Geospatial Inquiry & GIS
## Prof. Michelle Fame
### Lab #1 – Introduction to GIS & Geospatial Data

---

## Introduction

### Overview
In this lab, we will begin to practice with some of the basic components of ArcGIS Pro. We will be working with a variety of geospatial data types to make a simple map of the Town of Amherst and do some very basic geospatial analyses. The data and maps you generate in this lab may be used again in future labs, so be sure to organize, name, and save everything properly. 

### Learning Goals
* Using the Virtual Computing Lab (VCL) to access ArcGIS Pro 
* Using the F: Drive for file management
* Getting familiar with the ArcGIS Pro interface and basic tools 
* Managing geospatial data with ArcCatalog 
* Adding fields, using the field calculator, and symbolizing vector data
* Introduction to working with rasters and ArcToolbox 

---

## Part 1: Set Up Azure

File management is an essential part of using GIS and is essential to your success in this class. Taking a little extra time to get your file system organized before you dive into a project will save you many headaches down the line. Today, I want to model that behavior. 

Before any of us start on the assignment, let’s make sure everyone is successfully connected to the VCL, the F: drive, and can open ArcGIS Pro. Take notes on what we did to get connected; me, Andy, and your TA will come around and troubleshoot any issues you run into. If things go slowly today, make use of this time to catch up with classmates you already know and get to know folks you have not met before.

**Installation & Connection:**
1. Install the Windows App from the Microsoft Store on your computer to access Azure (the program which hosts our remote desktop system). 
2. Open the app, click **"+"**, and select **Add work or school account**.
3. Use your full email address (`@amherst.edu`) and login as normal.
4. Once the ArcGIS 3.5 Desktop is available, click on the **"..."** icon and select **Connect**.

*(Note: Reference the Windows and Mac setup links provided in class if you need help with step 1).*

**File Management Overview:**
Open a folder and navigate to the class drive. Here is how the drive is structured:
* **Admin:** A folder only Michelle can access.
* **SharedFiles:** Where I will distribute map documents and files for most labs (although this week I did it for you).
* **StudentFolders:** You will find a folder with your username on it that only you and Michelle can access; this will be the folder where you will save all of your work for this class.

**Your Workspace For Today:**
Navigate to `StudentFolders` > `AStudent26` (find your own student ID, this is my stand-in for your personal folder from here on out) > `Labs` > `Lab_1` > `TownofAmherst_v01`

---

## Part 2: ArcGIS Pro Map Interface

Double-click on the folder `TownofAmherst_v01` and open up the ArcGIS Project File named `TownofAmherst_v01.aprx`.

**Logging In:**
1. When ArcGIS is opening up, you will need to login using **Your ArcGIS Organization’s URL**.
