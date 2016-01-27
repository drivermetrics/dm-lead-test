# DriverMetrics Lead Developer Code Test

The aim of this code test is to demonstrate your ability to follow design specs and write clean well-architected Rails and React code. The task should take around 3-4h to complete and if it ends up taking any longer than this it is recommended that you should stop and submit what you have completed so far.

### The Task: A Simple Driver Database App

You are required to build a simple Rails and React app to allow for viewing of a database of drivers.

You have been provided a base Rails repository along with designs and spec for the app.

### User Interface

The designs provided for the app are as follows. Please aim to get as close to the designs as possible.

*List Drivers*

![Drivers List Screenshot](/readme/driver-list.png?raw=true "Drivers List Screenshot")

*Driver Detail*

![Driver Detail Screenshot](/readme/driver-detail.png?raw=true "Driver Detail Screenshot")

### Basic App Functionality

The app should perform the following:

* Provide a Master/Detail view of drivers in the database
* List drivers in the master view - this should be scrollable if the number of drivers overflows
* When a user clicks on the driver, the driver's details including `name`, `company name` and `description` should be loaded into the detail view to the right of the screen
* All data should be loaded from the Rails API (more details later)
* When no driver is selected the placeholder text should be shown

### Tech Stack

The frontend interface should be built using React components. The backend and API should be built using Rails. You are encouraged to use third party libraries and Gems that you feel are appropriate.

### Data Structure

The driver database should be structured as follows:

```
Driver
=======
name        string
description text
company     Company
```

```
Company
=======
name     string
drivers  [ Driver ]
```

You should store the data in an SQLite database and create a seeds file for seeding some random driver data.

### REST API

You should design and expose a REST API to allow for CRUD tasks on Drivers and Companies. This API can then be used by the React frontend to fetch and update data.

For this example authorisation and authentication are not required.

### Submission

Please clone this Repo (do not fork so that other candidates can't see your work) and submit your completed project as a zip file.

### Questions

If you have any further questions please feel free to email.

