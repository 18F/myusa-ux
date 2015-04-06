# Sign in flow
#### Hallway testing in SFFB

## Background
Based on earlier user research and secondary research on federated identity systems, we believe that:

1. Single sign on would solve many existing security and usability problems in account management
2. However, there is widespread distrust of commercial single sign on systems over the sharing personal data and tracking online behavior 
3. It is unclear whether that distrust will be mitigated by informing people about what data is being requested and giving them control over it
4. However, we believe that doing so is the right thing to do. 

**The permissions screen is the primary site of informed consent for and practical control over data sharing. So we want to make sure people can use it for those purposes.** 

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
This is a comparative evaluation of reactions to three different permissions screen pages. 

Big changes include:

1. Content: Top header 
2. Content: Page description
3. Control UI: toggles vs checkboxes
4. Layout: size/placement of help text


### Goals and hypotheses

Goals | Questions | Hypothesis
:------------ | :-------------| :-------------
Help select a design direction for the permissions page | Does making the help text more visually prominent help users notice that they can control what they are sharing? | Yes
 | Do users find it easier to turn sharing on/off with a toggle selector or a checkbox? | Toggle
Check whether our new content for the page resolves the comprehension problems with the old one | Are people reading the body text? | No.
 | Does the content in the body text explain what we're doing? | Maybe. 
 | Does reading that content affect their decision | No (as per Gov.UK and academic research)
Test whether we've fixed email copy problems | Is one link less confusing than two links? | Yes

### Find participants 
#### Desired profile
Federal employees, _not contractors or general public_

#### Recruiting
Impromptu.

### Conduct interviews
#### Activities
Walk through sign-in flow using Invision mockup (5-10 minutes)
##### Task 1: Make an account
##### Task 2: Sign in to another account 

### Analysis
### Reporting
## When are we going to do it?
* Sprint 24: planning
* Sprint 25 (Thursday): testing
* Sprint 25 (Friday): wrap-up
