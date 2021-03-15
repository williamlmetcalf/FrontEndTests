# Front-end Exercises
This repository contains a number of exercises for Front-End Developer candidates for Medtelligent, Inc.

## Basic Vue Exercise
**This will contain information for a basic Vue exercise**

## Vue Validation Exercise

### Technical Requirements
* You must use [Vuelidate](https://vuelidate.js.org/) to validate your form information
* You must use [Vue Filters](https://vuejs.org/v2/guide/filters.html) to format data
* You can use your own environment if available, otherwise complete this exercise using this [JSFiddle](https://jsfiddle.net/medtelligent_engineering/snb28arq/19/) as a base.

### Exercise Breakdown
In this exercise you will create a basic payment workflow using Vue.js. Your application will contain three steps (explained in detail below).

#### 1. Enter Payment Information
This workflow step will contain a basic form that collects the following information from the user:

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
This workflow step will display the information entered in the previous step for the user to review:
* Display First and Last Name together as one field called "name"
* Show email as a mailto link
* Show the amount formatted as valid currency ($#,###.##)

The UI will have two buttons
* A button labeled "Back" that will return the user to the previous step
* A button labeled "Submit Payment" which will take the user to the next step

#### 3. Confirmation
In this workflow step you will simply display a message to the user that their payment has been submitted successfully.
