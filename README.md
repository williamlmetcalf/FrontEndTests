# FrontEndTests
This repository contains a number of exercises for Front-End Developer candidates for Medtelligent, Inc.

## Basic Vue Exercise

## Vue Validation (with Vuelidate) Exercise

### Create a Payment Workflow
In this exercise you will create a basic payment workflow using Vue.js. You will be using [Vuelidate](https://vuelidate.js.org/) to validate your form information, and [Vue Filters](https://vuejs.org/v2/guide/filters.html) Your application will contain three steps:

#### 1. Enter Payment Information
In this workflow step you will accept the following information from the user:

* First Name
  * Required
  * Max length of 20 characters
* Last Name
  * Required
  * Max length of 20 characters
* Email
  * Optional
  * Must be valid email formatting
* Amount
  * Required
  * Must be a positive decimal number

The UI will have a button labeled "Review Payment Details" which will take you to the next step.

#### 2. Review Payment Information
In this workflow step you will display the information entered in the previous step for the user to review.
* Display First and Last Name together as one field called "name"
* Show email as a mailto link
* Show the amount formatted as valid currency ($#,###.##)

The UI will have two buttons
* A Back button that will return the user to the previous step
* A submit button which will take the user to the next step

#### 3. Confirmation
In this workflow step you will simply display a message to the user that their payment has been submitted successfully.
