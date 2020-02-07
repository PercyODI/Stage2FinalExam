# GrillBer Project Requirements

## What is GrillBer (A Refresher)

GrillBer is exactly like it sounds: Uber for grills! Let me set the scene. You live in a dense urban environment, in a studio apartment on the 20th floor of an apartment building, but you want to put on a cookout! You don't have the space or the budget to buy a high quality grill, but your local park doesn't provide public access grills for your cookout. What do you do?

That's where GrillBer comes in! GrillBer is a rental and delivery service for grills! Grill renters can put up the specs and descriptions for their grills, and users can rent them for specific amounts of time! The grill owner will drop off the grill at the designated time and location, and then pick it back up when the user is finished!

## Requirements

- The GrillBer front-end must be visually pleasing intuitive to use
- Pages must be dynamic
    - Load data via Ajax from the back-end
- Required functionality
    - Ability to see list of available grills
    - Ability to add a grill
    - Ability to rent a grill
    - Ability to add a user
    - Ability to search grills via filters
        - Grill Brand
        - Grill Model
        - City
        - Cost per Hour
        - Grill rating (1 - 5)
    - Ability remove a grill from list
    - Ability to view more details about grill
        - Brand, Model, City, Cost/Hour, Delivery Cost, Grill Rating, Grill Owner, 
- Required information
    - FAQ with at least three questions and their answers
    - How and Why section
    - About Us (Us being you, the team building GrillBer)
- Back-end must be a working REST API
- Data must be persisted via file
- Be prepared to get requirement changes as the project progresses


## Day One Advice

- Create GitHub repo
    - One repo with both Front and Back end (see Stage2.PieAuction for an example)
    - Add all team members as collaborators on repo
- Create initial applications
    - Folder for front-end with .html, .js, and .cs files
    - ASP.NET WebAPI project for back-end
- Create issues for work that needs to be done
    - Assign users to issues (issues can be assigned on the right side of the issue)
    - Split into pairs to help distribute the workload
- Create initial ERD for models
- Create README.md at root of repo
    - Include description of application and instructions on running app
    
## February 7 Update

Notes from stakeholders:

- Great work on starting a list of issues that can be worked through!
    - The product teams are a little confused by the issues. They don't state what is required to "finish" an issue, it just has a title.
        - https://www.productplan.com/glossary/acceptance-criteria/
        - Consider adding user stories so we understand why this issue is needed
        - Consider adding acceptance criteria so we understand what needs to happen to accept the issue
- The back-end is off to a good start! Excellent work getting the ERD put together!
- Stakeholders are meeting with investors next Friday (Feb 14). They have asked for a front-end that they can show to the investors
    - The front-end must be working and dynamic
    - The front-end can use fake data if the back-end doesn't support a process or entity yet
    - The front-end must be bug free and not throw errors so it can be demo'd cleanly
