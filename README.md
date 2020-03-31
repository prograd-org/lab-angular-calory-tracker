![Image description](https://i1.faceprep.in/ProGrad/face-logo-resized.png)

# ProGrad Lab | Calory Tracker

## Introduction

At this point in the course, some of us may be reminiscing about times before the course, when we used to work out, and we were fit and in shape.  Surprising as it may be, spending many hours each day sitting in front of the computer is not an effective way to attain, and maintain, a rock-hard physique.  

Our solution: A Nutrition App. 

And it's your job to build it. 

In the starter code, we've provided a list of foods in the form of a TypeScript array of objects. This has already been imported into the foods-list component provided to you.

## Learning Goals

After this lesson, you will be able to:

- Create a static Angular application with Angular CLI.
- Build an Angular application with one component.
- You must use at least 1 of each of the following:
  - `component`
  - `pipe`
  - `ngFor`
  - `ngIf`
  - `ngModel`

## Requirements

- Fork this repo.
- Clone this repo.

## Submission

Upon completion, run the following commands:

```bash
$ git add .
$ git commit -m "done"
$ git push origin master
```

Navigate to your repo and create a pull request from your master branch to the original repository's master branch.

In the pull request name, add your Prograd id, name, and last name separated by a dash "-".

## Deliverables

You need to generate the starter code and fill it with the necessary code to satisfy the requirements described below.

## Introduction

In this lesson we are going to work with Angular for the first time. The goal here is to work on a small projects where you can practice the concepts we've learned thus far.

## Starter Code

To generate the starter code, follow the steps given below

- To create a new application,
    - Open your ubuntu or cmd terminal and execute the following command
      - ```ng new app-name```
      - for example, ng new super-wars
    - To create a new component, execute the command 
      - ``` ng generate component component-name```
      - example, ng generate component contacts
      
## How to run

- To run the project go to your ubuntu terminal or VScode editor
    - open the ubuntu or cmd terminal or inside the vscode editor
    - run the command following command
    - ```ng serve --open or ng serve -o```
    

## PROGRESSION 1 | Display Foods

In the `app-food-list` component, display a list of the foods. This should include the food's image, its name, and its calorie count.

Notice, we've already imported an array of objects containing food into the component.

**Make sure the image's src property is properly bound** so that any time the value is changed in the Typescript class, the change is reflected in the DOM.  

## PROGRESSION 2 | Search Foods

Create an input box to search through the foods by name.

You're going to need to generate a custom *pipe* to do this. Reference the example from the lesson on pipes, as it will be very similar.

## PROGRESSION 3 | Add New Foods

Create a button to add new foods.

When a user clicks the button, a form will appear with fields for a name, number of calories, and an image.

When the user clicks submit, the food will be added to the list.

The form should disappear when the user clicks the submit button.  

## PROGRESSION 4 | Today's Foods List

Create a button next to each item. When a user clicks the button, the corresponding food should be added to a special list of foods which are "today's foods".

Somewhere on the page, display a list of today's foods, with a total calorie count.

## BONUS | Quantities

In addition to the "Add to today's list" button, create an input for quantity. Whenever a user enters a number into the input, you should add that many of the item to their list.

The default quanitity should be 1.

**SUPER BONUS**

If the user has added more than 1 item of the same type to their list, don't display it twice. Instead, display the item's name, and the number of times it has been added.

For instance:

- `Banana x2`
- `Salmon x5`
- `Cake`
