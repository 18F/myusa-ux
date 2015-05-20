#Tldr;

```
Nothing on this page where I would have gone, 'what's this here for, or this doesn't make sense.' It's relevant and presented well.  
–22-P01 (implementer)
```

We're largely on the right track for developers or technical product managers in terms of the structure and content of the Learn More page, although they are asking for more specifics about how MyUSA works before signing up. There are some clear ways forward to support their needs included below. 

We are doing as well by members of partner organizations who are not actively engaged in account management system implementation. It was not immediately clear to them what benefits MyUSA offers, or why they would visit the site. 

**My recommendations** 

- Direct the front page at members of the public interested in what MyUSA does for them 
- Optimize the Learn More page for technical implementers. Add system diagrams.
- Create tertiary FAQ or detail pages with specific URLs that technical implementers can forward to domain experts.
  
  
# About the study

## Background

We ran the first iteration of the front page past members of the UX-COP list who volunteered to test the page. As a result, we

- restructured the front page and added more information about the service
- added explanation pages for agency integrators and users

## Study questions

Does this redesign help better answer the questions of visitors from our partner agencies?

Are we helping people take the next step in deciding whether or not to integrate MyUSA?

## Metrics

Participants can 

- navigate to the correct page to Learn More
- find the sign up button (if they want to sign up)
- explain in their own words
  - the benefits of MyUSA for _them_
  - whom this site is for 

## What we did
 
Five 30-45 minute remote interviews with federal employees from an organization considering implementing MyUSA. 

- over the phone, with screen-sharing
- report based on notes, not transcription

Researcher asked participants to 

- examine the landing page
- find more information about MyUSA
- explain MyUSA's benefits

Participants included 2 project managers, 1 developer, 1 UX expert, 1 security expert


# Themes

## Our partners include two very different groups


**Implementers** are engaged in the details of selecting and then implementing account management systems. This group includes developers and technical product managers.

**Domain experts** are not concerned with the  details of account management systems, but who have some interest in how MyUSA works. This group includes UX researchers and IT/Security people. 

These two groups will come to MyUSA with different levels of knowledge about and interest in account management systems.

**Implementers (three of five participants) could all explain why they were visiting the site**. Domain experts could not. For example:

```
[The page] is good for somebody who already has knowledge of why they'd be here.[...] I'm wondering why I would be here.  As a member of FEMA, I don't know what we're looking at. 
-- 22-P04 (domain expert)
```
When I did not give them a specific reason why they would visit the site, the **domain experts assumed they were visiting as regular users**, not people with a technical interest in how MyUSA works.

```
How would I get here as a user? Why would I be here? What can I do?
-- 22-P05 (domain expert)
```

## Signing up is not the next step

We had an unidentified assumption: that "sign up" makes sense as a call to action for implementers. 

But none of the participants, even those who were very enthusiastic about MyUSA, wanted to sign up after visiting this site. Instead, they asked for more information.

The "next step" 22-P01 would take after looking at the top section is to go to Learn More: 

```
That's what I want to do. I want to learn more how to integrate this into our site.
-- 22-P01 (implementer)
```

Participants didn't want to make an account until they were really sure what they were signing up for

```
What am I signing up for? Why is this important to me? 
-- 22-P02 (implementer), looking at sign-in button on front page
```

```
I'm not sure even what MyUSA is, so I'd look for information [first]
-- 22-P05 (domain expert)
```

:arrow-right: De-emphasize sign up as a call to action. 

:arrow-right: Besides the "Learn More" page, how else might we help implementers learn more about implementing MyUSA? 


## The Learn More page works best as a high level overview for implementers
 

In general, implementers liked the section order and content of the Learn More agency page as a "high level overview" (22-P03). The benefit statements were appealing and relevant. 

```
Somewhere you have to address the security and their privacy. Everything else seems pretty straightforward.  
—22-P02 (implementer)
```

But the pages didn't give them enough specific information to make the decision to make an account. 

```
You have the high level categories covered, it's just the details that I'd be more interested in learning more about.   
— 22-P01 (implementer)
```

### Our value propositions appeal to implementers but not as much to domain experts

#### "Account management" 
##### resonates with implementers

```
"That's great -- that's exactly what we want to do. Robust account management.
— 22-P01 (implementer)
```

```
You can create an account to register for different specific things based on your needs. 
— 22-P03 (implementer)
```
**Hypothesis confirmed** Providing account management is desirable because there are pervasive "help desk issues with password and PIN reset."

**Hypothesis confirmed** Providing account management is desirable because agencies don't want to do it.

Nice phrasing on the benefits to integrators from 22-P01: "Your website connects to MyUSA and leverages its account management capabilities so we can focus on doing other things."

##### but means little to domain experts

```
One account for government -- one account for government WHAT? --- What resources and services?
22-P05 (domain expert)
```

##### The concept of "Single sign on" is more universally recognized and appealing 

Four of five participants (22-P01, 22-P02, 22-P03, 22-P05) mentioned single-sign without being asked about it. 

```
Single-sign on, that's great.
—22-P02 (implementer), looking at the visitor page
```

One participant was not sure whether we provide single sign on, however -- "Do I need a third-party single-sign on service?" he asked.

:explosion: Right now, the words "single sign on" are only on the visitor page. We should mention it more frequently.

### Free is good...

```
Lots of agencies are having difficulties finding a line item for development. 
— 22-P03
```
Once again, MyUSA lets agencies focus on the jobs they they care about. 

### But implementers wanted more specific information about...
 
#### How integration would really work

"I'm thinking about how this may work with us." 
-- 22-P02

- Interested in finding out more about three steps. How difficult or how easy is it is to get this integrated? Would like to get into documentation to see how mature the API is. 22-P01

#### Security measures

1 person asked **whether we do two-factor authentication**. Apparently some of their partners require 2FA.

2 people asked **how passwordless sign on could work**

We can take these questions as indicative of how implementers define "security," but not indicative of how pervasive security concerns are.

```
How do you "make sure I'm the one whose receiving those emails?
-- 22-P02
```

#### Is it really free?

22-P02 didn't see at first the language about code being free, customizable, and easy to use. "What does free, easy to use mean?" he asked. **"I don't know if there's any cost involved. That would need to be upfront too."**


#### Privacy protections for users
```
If I was to complete a registration form here, is that registration form going to go to all federal agencies? If I haven't paid my taxes in ten years, and I don't want the IRS to know, what will happen? 
-- 22-P02
```

```
It doesn't tell me about cookies
Q: cookies?
A: part of privacy policy.
—22-P03
```

<hr>

Privacy is a big concern for FEMA

"At FEMA, we do not want to hold PII because then we're liable for it. We have certain restrictions on what we can and can't do. I was under the impression -- MyUSA will hold the PII.[...] So that a person could sign up with MyUSA and apply for disaster assistance and we wouldn't have to store PII because it would be with you guys." 22-P04

  
#### Some confusion about what information we collect

```
What information do you ask for? because this doesn't really tell me." 
22-P03
```

Two participants expected MyUSA would store much more PII than it does. One expected MyUSA would store name, phone number, current address, DOB, and SSN. Another expected that MyUSA would serve as a "wallet" 
 
22-P03 was confused about whether there is LOA2+ authentication. Are we validating their identity against a credit report? Could people apply for SBA loans with with MyUSA? 

#### How tasks and notifications work

22-P03 and -P01 were not sure what a task or task list was. "How does that relate to account management?" asked 22-P01

What kind of notifications do you offer? 22-P01

#### Who else is using it?

Two out of three participants _really_ wanted the names of specific agencies. Two were mildly interested. None saw the names of partner agencies as irrelevant. 


"One of the things that helps that process -- looking at partner agencies -- in past projects has helped is to **reference approaches that are being used in the federal government already, because that carries weight when you present it to security.** That it's being used by a federal website that gets a lot of traffic." 22-P01

<hr>

"Partner agencies are really important. **[They] impact what peoples say about privacy.**" 22-P02

22-P02 "What's missing from upfront, what agencies do you play with" 

<hr>

This differs from other groups we've interviewed (notably those at HHS). I have two hypotheses to explain this:

1. The concern is specific to disasterassistance.gov because they work with HUD and also have developers from Benefits.gov. 
2. The names of partner agencies are most salient to integration project managers because they affect how security and other teams review potential solutions.

The latter seems more reasonable, and suggests that we should be clear when we talk to federal employees about whether they are (potential) integrators or end users. 


### Domain experts are confused about what MyUSA does

```
MyUSA is one account for government..but what resources and services? [...] I just don't know what MyUSA DOES.  
— 22-P05, 20 minutes into the walkthrough

```
Domain experts had problems articulating the benefits that MyUSA provides in their own words, or in identifying those benefits at all.  

To better inform domain experts, consider

:arrow_right: "Single sign on" is a well-understood term. Use the word "single sign on" throughout the site, not just on Visitors page

:arrow_right: Less text, more graphics

:arrow_right: Include scenarios of likely use that illustrate  *who* would use MyUSA, and what benefits they'd gain 



## How to address the different perspectives of the two groups

### Show, don't tell, UX

Suggestions included
- a step-by-step tutorial page for users
- scenarios
- screenshots

```
Kind of a real-world situation type thing. Kind of like, well, Joe came to MyUSA and this is what he can do. These are the things he sees. 
-- 22-P03
```
We might 

:arrow_right: add links to an FAQ or detail pages

:arrow_right: include screenshots as pointers to what users will see

### High level overview

```
a high level information of how this whole process works. something that gives us a very broad view [...] how all this integrates with my site; how it works and all that.
--22-P01 (implementer)
```
Maybe a system diagram?

22-P03 (implementer) thought this information would be found at Use MyUSA.  
Go to Learn More or About to see what it's about 22-P05


## Per page comments


### Starting page

#### No agreement on most visible element 

- MyUSA logo (22-P01)
- Sign up now and learn more buttons (22-P02)
- "One account for government" (22-P03)
- colors and graphics are "very soothing and inviting" (22-P04)

:question: **Which element should we ensure visitors see first most?**

:arrow_right: One suggestion: de-emphasize sign-up button since implementers and domain experts won't sign up immediately and users will hit the sign up flow in a different context


#### More obvious scroll cues _might_ be needed
22-P04 didn't know if she could scroll down: "It doesn't look like there's stuff there." She only knew to scroll down because she saw the scroll bar on the right

#### Central statement may be working best for people *who are actively considering integration*

22-P01: "one statement that explains it -- that's great.

vs

22-P04, who isn't part of the integration team, thought the top statement "made it sound like [MyUSA is] not benefitting me at all." 22-P04 (domain expert)

### Learn More
### Structure is working

"**The [section] order is aligned with my questions**"   
—22-P01


Small text doesn't have to do with the question text. It seems confusing. 22-P03

A lot of text 22-P05

```
Not sure if I like the staggers. Would prefer to see them all on one side. It makes more sense to me.

It seems like the questions should be on the left side. Answers or other text on the right side. 

Seems like you need a flag someplace. An American flag. 

It just seems too plain for MyUSA. [The logo] if you put that in red it might look better. Either My in blue or USA in red. Looks more American. 

Green is "okay". [It needs to look more America] Most stuff for gov't is red white and blue. The black to me is just kinda dead.

— 22-P03
```
#### Another person really liked it. 

```
I like the simpliciy [of the layout]. I like the graphics. They're not overly done. They're simple but they still indicate what I'm going to be clicking on or going to. I like the variance in the color and the separation of the boxes.
22-P04
```

#### So there you go. Opinions differ on the learn more layout. But it's interesting that two people both mentioned it. 



### Domain experts found the notion of 

```
What am I registering for myself? For my agency? What am I registering? Why would I register? 
22-P04
```

```
MyUSA is one account for government..but what resources and services?

How would I get here as a user? Why would I be here? What can I do?
22-P05
```




# Customer journey notes

## Researching all the available options
"Exploring methods and approaches for handling account management. This is a really good time for us to learn about new approaches, or what else is involved in account management that we haven't considered. Looks like [passwordless] you have some new methods." 22-P01

22-P04 is not part of the team that's [journey step] researching all the options available. 


## Narrowing down 

...to 2-3 options that they think will be "usable for the end user" 22-P01

"Is the information secure? Is our data really that safe with the government? You get it all the time. " 22-P01 

Behind the scenes I would also have to think about if I'm allowed this information -- SORN. PII. 22-P02

## Getting approval from security

Security identifies issues; they identify solutions [compliance and checklist culture]

"**Usable for end user but will it pass security?** Once we narrowed it down to a couple flows, we want to present them to security, but we'd like to present a third option, which would be using MyUSA." 22-P01

"working with security groups to find out which methods would be acceptable. We'd rather not get more into that without understanding more about MyUSA." 22-P01

"depends on what they allow us to move ahead with. Whether we can look at both approaches. Always something they identify as an issue, so we'd have to take a look at the flows we have and find ways to change those flows to meet their requirements." 22-P01

## Implementing: Getting into the "nitty gritty"
"A registration form vs what I can actually collect is different. Behind the scenes is when you'd get into the nitty gritty." 22-P02
