# Sign in flow
#### Hallway testing in SFFB


:arrow_forward: [Background](#background)

:arrow_forward: [Detailed results](#analysis)

### Summary
Big changes included:

1. Content: Top header 
2. Content: Page description
3. Control UI: toggles vs checkboxes
4. Layout: size/placement of help text

Goals | Questions | Hypothesis | Results
:------------ | :-------------| :------------- |:-------------
Help select a design direction for the permissions page | Does making the help text more visually prominent help users notice that they can control what they are sharing? | Yes
 | Do users find it easier to turn sharing on/off with a toggle selector or a checkbox? | Toggle
Check whether our new content for the page resolves the comprehension problems with the old one | Are people reading the body text? | No.
 | Does the content in the body text explain what we're doing? | Maybe. 
 | Does reading that content affect their decision | No (as per Gov.UK and academic research)
Test whether we've fixed email copy problems | Is one link less confusing than two links? | Yes

## Background
Based on earlier user research and secondary research on federated identity systems, we believe that:

1. Single sign on would solve many existing security and usability problems in account management
2. However, there is widespread distrust of commercial single sign on systems over the sharing personal data and tracking online behavior 
3. It is unclear whether that distrust will be mitigated by informing people about what data is being requested and giving them control over it
4. However, we believe that doing so is the right thing to do. 

:boom: **The permissions screen is the primary site of informed consent for and practical control over data sharing. So we want to make sure people can use it for those purposes.** 

We now have clearance to do hallway testing at the San Francisco Federal Building (aka SFFB). The SFFB hosts a number of different agencies whose employees will have varying tech levels, education, and so on. I want to take advantage of this opportunity and do a round for Sprint 25. This also will give us a chance to road-test @mkhandekar's major revisions of the permissons screen with a wide variety of people (albeit all federal employees) before showing them to small business people.

Earlier research with the permissions screens surfaced these problems with the permissions page:

* Participants didn't notice that they could control what MyUSA sent to the app
* Participants didn't notice that they could edit the information being sent
* Participants found the introduction to the page and the reasons for requesting data confusing

Additionally, we found that having two links in the confirmation email was confusing. 

## Goals
The goals for this activity are:

1. Help select a design direction for the permissions page
2. Check whether our new content for the page resolves the comprehension problems with the old one
3. Check whether the revisions to the email template make it easier to follow

## What are we going to do?
This is a comparative evaluation of reactions to two different permissions screen pages. We are testing two different strategies.

### Explanation-first 
Makes the reasons for the request more visible
![MyUSA permission screen mockup version 1](https://cloud.githubusercontent.com/assets/1598889/7028778/262a9f6c-dd26-11e4-90a9-7f37f29cf935.png)

### Decision-first
Makes the controls for sharing information more visible

![MyUSA permission screen mockup version 2](https://cloud.githubusercontent.com/assets/10067318/7057037/3fdae86e-de06-11e4-911b-c7203e938c27.png)

## What we did

### Find participants 
#### Desired profile
Federal employees, _not contractors or general public_

#### Recruiting
Intercept between hours of 11am - 2pm in the lobby hallway of SFFB

### Conduct interviews
#### Activities
Walk through sign-in flow using Invision mockup (5-10 minutes)
##### Task 1: Make an account
##### Task 2: Sign in to another account 

### Analysis
This is just going to be a table with all the data because I don't think we have enough data to really make it worth abstracting

 | Explanation-first | Decision-first |
:----------- | :----------- | :----------- |
*Initial screen* |-no problems |-no problems |
*Enter email* |- no problems | - no problems|
*Almost there* |-no problems |- seems like phishing. "I'm doubting if this is real or not"|
*Email* |- no problems |- "doubtful it's from the gov't," would ignore it unless told to use it by supervisor |
*Permission screen* |- didn't know to scroll down, but understands that she can click| - what does this mean? share with whom? "sensitive" to sharing personal information, would probably hit cancel|
*Help text* |- thinks that "your information will be shared with a database"| when told to click link, found the extra text "reassuring"|

#### Overall
- "not bad"
- "This feels like 40 pages of clicks"...it's "teasing," like those websites that keep you clicking

### Reporting
## When are we going to do it?
* Sprint 24: planning
* Sprint 25 (Thursday): testing
* Sprint 25 (Friday): more testing
