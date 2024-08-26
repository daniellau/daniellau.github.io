---
layout: post
title: "Alaska Mobile App"
date: 2024-02-28
category: "Heuristic Evaluation | Design"
description: 
image: /assets/images/alaska/cover.png
author: Daniel Lau
tags: 
  - UX Research
  - Heuristic Evaluation
  - UX Design
---
The purpose of this project is to evaluate the experience of booking a flight on the Alaska Airlines mobile app. Each section of the app will be grouped into workflows.

UX principles will be used to analyze the issues with the experience and how it can be improved. The UX principles utilized in this analysis will be Nielsen’s 10 Heuristic Principles.

## Current Experience
### Search
![Alaska Airlines mobile search](/assets/images/alaska/search.png)
1. On the first screen, you’re given search fields to create an appropriate search experience. This violates Nielsen’s flexibility and efficiency of use principle because every form field must be clicked in order to fill out the entire form. I would initiate a lump together input screens in one workflow without having to click on each individual form field.
2. When typing into the from and to fields, an autofill block shows up underneath the field. This violates
Nielsen’s error prevention principle because the autocomplete fields are very thin and could cause users misclicking. I would design this on a separate screen so there’s more real estate to click.
3. Flexible dates can be selected with this field that looks like a radio button. This violates Nielsen’s consistency and standards and flexibility and efficiency of use principles because radio buttons are not the same as checkboxes and the search results page already allows for you to choose flexible dates, making this radio button redundant. I would remove flexible dates and use other UI elements to toggle search criteria.

### Flight & Seat Selection
![Alaska Airlines mobile flight & seat selection](/assets/images/alaska/select.png)
1. This screen is shown after you click search flights. This violates Nielsen’s aesthetic and minimalist design principle due to the long page, a user can’t see enough information to make an informed decision. They are forced to scroll. I would move returning flight tickets to a new page to save space.
2. Users are allowed to choose seats once tickets are selected. This violates Nielsen’s flexibility and efficiency of use and error prevention principles because users can click on seats that saver tickets aren’t allowed to reserve. I would highlight seats they are allowed to reserve.
3. Saver tickets created difficulty in the user experience in particular. You’re allowed to select one saver departure ticket and one saver return ticket, but you can’t mix and match saver tickets with any other tickets. This violates Nielsen’s error prevention principle. I would prevent the user from selecting other tickets if they select saver in one screen.

### Inputting Passenger Information
![Alaska Airlines mobile inputting passenger information](/assets/images/alaska/input.png)
1. Whether you login or go to guest checkout, you end up on the passenger information screen. This violates Nielsen’s flexibility and efficiency of use principle because every form field must be clicked in order to fill out the entire form. I would minimize the scrolling by making fields that don’t stack.
2. This screen appears after the passenger information screen. This violates Nielsen’s flexibility and efficiency of use principle because every form field must be clicked in order to fill out the entire form. I would minimize the scrolling by making fields that don’t stack.
3. This screen appears after the contact screen. This violates Nielsen’s flexibility and efficiency of use principle because this summary should be the first screen that appears when you log in. How often does customer information change between flights? I would also have passenger information and checkout AFTER seat selection.

## Reimagined Experience
### Search Redesign
![Alaska Airlines mobile search redesign - destination search](/assets/images/alaska/search-destination.png)
1. I designed this to give users the ability to toggle between round-trip and one-way. It helps with flexibility and efficiency of use.
2. Creating a new page for location gives plenty of space to properly search for the location and also plenty of vertical space to click on the autocomplete. This helps with error prevention.
3. The list automatically reduces in size based on what is searched, making it easier for user’s cognitive load. This helps with flexibility and efficiency of use.
4. I removed the radio button looking UI elements and replaced them with easy to understand on/off switches. This helps with consistency and standards.

![Alaska Airlines mobile search redesign - dates selection](/assets/images/alaska/search-dates.png)
1. The travel dates selection screen appears after the location selection. This helps with flexibility and efficiency of use.
2. The user selects departing and returning date on the same screen, avoiding the experience of having to click individual form fields for each. This helps with flexibility and efficiency of use.
3. All fields are filled out after user goes through the entire workflow (departing location → return location → departure date → return date). This does not require clicking on each and every form field, creating a seamless workflow. This helps with flexibility and efficiency of use.

### Flight & Seat Selection Redesign
![Alaska Airlines mobile search redesign - flight selection](/assets/images/alaska/select-flight.png)
1. Users can toggle dates on the very top for flexible dates. This will help with reducing the redundancy of the flexible dates toggle on the original search page. This helps with consistency and standards.
2. Reducing the card sizes and color coordinating the ticket types allow users to see all the information on the screen without having to scroll. This helps with aesthetic and minimalist design.
3. The resetting search feature gives the user an emergency exit from this screen. They can change their search parameters if these options don’t meet their needs. This helps with user control and freedom.
4. If a Main ticket is selected in the Departure Flight screen, Saver tickets in the Return Flight screen are no longer clickable and faded out. This helps with error prevention.

![Alaska Airlines mobile search redesign - seat selection](/assets/images/alaska/select-seat.png)
1. After selecting the flights, user immediately sees the tickets they chose and the subtotal. This helps with recognition rather than recall.
2. Giving the users options to either emergency exit from this section in case they made a mistake or to continue to selecting seats next. This helps with user control and freedom.
3. If the user selects selects a Saver fare, Main and First Class seats are not clickable. This helps with error prevention.
4. If the user selects selects a Saver fare, Saver seats are highlighted by green if they are available. This helps with error prevention.

### Passenger Information Redesign
![Alaska Airlines mobile search redesign - inputting passenger information](/assets/images/alaska/input-passenger.png)
1. Sign in or checking out as guest allows users to continue purchasing a ticket. Signing in means that the user already has an account. Continuing as a guest means the user needs to enter their information manually. This helps with user control and freedom.
2. If the user signs in, the passenger summary page is immediately shown. If the user wants to change any of the information, they can click the Edit button. If not, they can continue directly to payment. This helps with flexibility and efficiency of use.
3. The modify flight button allows users to emergency exit in case they made a mistake. This helps with user control and freedom.