# EV Charging Stations App 
# Table of contents
1. [Introduction ](#kt0)
2. [WorkFlow of the Project](#kt1)
3. [Advantages/Limitations of the App](#kt2)
4. [Proposed System ](#kt3)
5. [System Requirement ](#kt4)
6. [Getting Started](#kt5)
7. [References](#kt6)

<div id='kt0'>

## Introduction 
In the recent decade we have witnessed monumental advancements in electric vehicles and the charging technology. Along with helping cut down on emissions, electric vehicles also have a better power delivery and prove to be far more efficient as they are able to employ regenerative braking to recharge their batteries while on the move.
Despite their many advantages, electric vehicles still fall short when it comes to aspects such as finding charging stations. 

Unlike people driving conventional cars, EV owners can’t have their vehicles refueled at any fuel station. Drivers with electric cars have to keep their car charged well in advance before departing. 
The need for developing infrastructure such as charging stations is undeniable.

Developed using Flutter, this EV Charging Station app has been developed to help EV drivers locate available charging stations near them. After locating a charging station, users can also book a slot at the station to charge their vehicle.
EV owners can also use this system to plan their trips more efficiently. Users simply need to specify the source and destination. Based on these two parameters, this system prepares a roadmap with all available charging stations along the journey.

<div id='kt1'>

## WorkFlow of the Project

In this system, the User is able to manage All his EVs inside the app plus he has search/book a slot in advance in the charging station. The User can also search an EV station based on nearby, city or kilometers. 

The System also provides a Roadmap if you enter source & destination with the charging stations on the way according to the kilometers entered.
Admin will manage all the stations and slots.

<div id='kt2'>

## Advantages/Limitations of the App

### Advantages 

*	Finding Charging stations is easy with multiple Filters.
*	Roadmap is provided in the system
*	Charging slot can be booked in advance.

### Limitations

*	Wrong inputs will affect the project outputs.

*	Internet Connection is mandatory

* The android mobile user will not be able to insert or view details if the server goes down. Thus, there is disadvantage of single point failure.

*	No logs on how much is charges on the app

*	It’s a Common Charging station not as per vehicle.


<div id='kt3'>

## Proposed System

The system comprises of 2 major modules with their sub-modules as follows: 

### Admin:
*	Login: 

	Admin can login using id and password.

*	Manage Stations:

	Add/update/delete/view Stations

	Enable/Disable

	Manage Slots - Add/Update/Delete/View

	Slot price

*	View Bookings:

	View registered users

	Cancel booking if station is broken etc	

### User:
*	Register:

    User can register using personal details. 

*	Login:

	User can login in his personal account using id and password.

*	Profile:

 	View and update

*	Change Password:

	can change the password within app

*	Manage EV Vehicles:

	Add/Update/Delete/View

*	Find Stations:

	filter by nearby/city/kms

	choose station

	choose slot

	select date/time

	Payment (Dummy)

*	View Bookings:

	Road Map

    Choose source/destination and kilometres and the system will make a roadmap with charging stations on your journey.

	filter by date

	Cancel under a particular duration

<div id='kt4'>

## System Requirements 

##	Hardware Requirement

i.	Laptop or PC

•	MacOS Sierra and above (If Mac setup is required)

•	Windows 7 or higher

•	I3 processor system or higher

•	4 GB RAM or higher

•	100 GB ROM or higher


ii.	Android Phone (6.0 and above)

iii.	iPhone (iOS 9 and above) (If iOS version needs to be checked)

##	Software Requirement

•	[Android Studio with Flutter Plugin](https://link-url-here.org)

• [Flutter SDK Download](https://docs.flutter.dev/get-started/install)

•	XCode (Latest version) (If iOS version needs to be checked on Mac)

<div id='kt5'>

## Getting Started

1. Fork& Clone the repository
2. Open repository in Android studio
3. Run command 'flutter pub get' at root of the structure
4. Create a New branch by the Command git checkout -b "branchname"
5. Code in! and add your code with git add. 
6. Commit the code with git commit -m  "anytext"
7. Push the code with git push origin "branchname"

<div id='kt6'>

## References

-	https://developer.android.com/
-	https://stackoverflow.com/
-	https://www.tutorialspoint.com/index.htm
-	https://medium.com/ 
