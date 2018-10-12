# idea for codefundo++

The Life-Saving App

## Synopsis

* A complete web app catering to the needs of both users and the government in order to predict natural disasters and save lives.

## Solution

### Collect and display weather information

* This app uses web-scraping for collecting weather reports from multiple other websites.(Wherever it is legal)

* Also collect information from the government.

* Display the above data.

### Separation of Concern

* Since this is an app used by both governmnet and common people it is best to separate them and deliver according to each of their needs

* Government has separate use cases

* People have separate use cases

#### Use cases of government

* Get alerted by the web app for a possible natural disaster.

* Add/Delete/Modify weather reports.

* The government shall have the authority to send warning e-mails and messages to all people in the city/region affected by natural disaster.

* Government has the option to add/ delete/modify email-ids and phone numbers of all the people in the city/region.

* This data is stored in the web-app and it shall automatically send emails and message to all people stored in the database.

* Add/Delete/Modify safety measures and guidelines to be followed.

* Store emergency contact email-ids and phone numbers

* Share information on Social Media

#### Use case of People

* Check weather forecast.
* Check weather it is safe to go outside.
* Register with the web-app to get notification on natural disaster.
* Get safety measures, tips and guidelines to be followed to remain safe.
* Get emergency contact numbers and email ids in case of natural disaster.
* Share information on Social Media

### Uniqueness of Solution

* It is a *complete* app.

* Some apps show weather forecast, some apps sends emails and messages, but this app combines the best of all existing solutions.

* *Scalable*: Market is very huge and it is relatively simple solution

* Highly *effective* solution as it alerts both the user and the government.

* Easy to maintain and develop.

* Helps users with/ without internet connectivity (Feasible).

* Easy UI for government/ users to post/get necessary information.

* Feature to share on social media: One of the best ways to share information.

### Practices for development

* Follow agile framework (since it is a hackathon:)).
* Divide each of the use-case of both government into features and tasks.
* Assign these tasks to smaller sprints.
* Complete each sprint with unit and integration testing.
* System and acceptance testing at the end.

### Usage and Feasibility

#### With internet connection

* Users can avail each of the usecase specific to them(government, people) by opening the app on a browser.
* Avail emergency numbers and Email-IDs to contact.
* Get notified via email-id, social media.

#### Without internet connection

* The web app sends message through phone so even people in remote areas get notified.
* Avail emergency numbers to contact.
* [Further development] Notified by government via radio.

## Datasets

### Regions

* Follows this order: Countries, States, Cities.

* Narrows down to particular regions affected by the disaster.

### Weather reports

* Obtained from government.

* Obtained through web scraping(Where it is legal).

### User data

* Name provided by government/person.

* E-mail ID provided by government/person.
* Phone number provided by government/person

## Project Scope

* Can be used by government and people everywhere.
* Since it is cost-effective solution, it can be developed easily and quickly.
* Open Source development.

## Technologies Used

* Python

* Flask

* SQL

* HTML

* Bootstrap

* CSS

* JavaScript

* PHP
