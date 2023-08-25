## Monday 21 August, 2023
- Learn about Testing and test cases and find ui bugs with their functionality working properly via Parmod sir's test case  sheet.
#### progress
 - Written test cases and tested the appointed test cases of Android and Web Applications


## Tuesday 22 August, 2023
- first aim to go through daily testing of web app and android app
- testing planters app in flocard app staging 
#### progress
 -  Tested the flocard app, planters app and also found some ui bugs in planters app and solve those problems send the code
 -  learned about some basic Testing tecghniques  from https://www.geeksforgeeks.org/software-testing-basics/ this website

## Wednesday 23 August, 2023
### Tasks
- First aim to go through daily testing of web app and android app have to solve the the ui issues mentioned excel sheet
-  issues
   1. Qr code Scanner and cancel button both collapsed in each other
   3. button color issue and space sepration issue in several page of tag tree and tag cluster page

### Progress
- Solved issue
   1. Solved issue Qr code scanner, cancel button sepration,redesigned border and modified using css and bootsrap properties
   2. Solved this issue using changing color of buttons and margin using bootsrap properties of margin bottom and top and alos used little bit of css
   3. Compiled All the solution in Fix6.html file with proper documentation in document
#### Code Link for solved issues 
https://github.com/Danish030/fix/blob/main/New%20fixes%2023-08-23.html

## Thursday 23 August, 2023
### Task
- Fix a bug on notification alert of contacts After Editing your profile - The issue is Select all contact deoesn't work if you have one checked a individuial contact, in this scenario select all option show checked on and in also code also it is checked but individual contacts deosn't
### Progress
 - Understand the working of code with #chkAll attribute select all Checkbox working fine but in the individiual checkbox1, checkbox doesn't have any code
 - i have to resolve this issue with proper js code later on i will upadate the approach i used here

## Friday 23 August, 2023
### Task
1 Mr. Manoj assigned me a ui bug to fix in flip messages
-  the issue is to show the sent message which is hidden under the image and resize image
2 Mr. Manoj assigned me a ui bug in the page https://flocard.app/planters/User/PlanterManagement 
-  the issue is to  change the no data show picture
 ### Progress
- The issue is solved using these css properties mentioned below
  - In the message Div, i used margin-top:-2em; to text show in card below the image
  - image issue solved using setting height and width and border radius here is the css code
  
     <dl>
 <style>
     height :230px; width:230px; border-radius:5px;
    </style>
</dl>

- 2nd issue solved just simply using no data show picture from other page of planters app(just copied)
 <dl>
  <img class="mb-3" src="/planters/assets/svg/illustrations/sorry.svg" alt="Image Description" style="width: 7rem;background:white;border-radius:20%; ">
 </dl>

   

