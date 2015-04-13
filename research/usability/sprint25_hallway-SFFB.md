# Sign in flow : Hallway testing

:arrow_forward: [Background](#background)

:arrow_forward: [Raw notes](#data)


### Summary

We varied

1. Content: Top header 
2. Content: Page description
3. Control UI: toggles vs checkboxes
4. Layout: size/placement of help text

#### Quick context 

Goals | Questions | Hypothesis | Results
:------------ | :-------------| :------------- |:-------------
Help select a design direction for the permissions page | Does making the help text more visually prominent help users notice that they can control what they are sharing? | Yes | No. What helps is making the controls more prominent.
 | Do users find it easier to turn sharing on/off with a toggle selector or a checkbox? | Toggle | It's a draw, with toggles easier by a hair. Certainly people noticed the toggles faster.
Check whether our new content for the page resolves the comprehension problems with the old one | Are people reading the body text? | No | No.
 | Does the content in the body text explain what we're doing? | Maybe | No. It's too unspecific about <p> (a) what MyUSA is. <p> (b) where the information is coming from. <p> (c) who is receiving the information |
 | Does reading that content affect their decision | No (as per Gov.UK and academic research) | No because <p> (a) because some people had already made their decision and <p> (b) some found the content too unspecific to be informative 
Test whether we've fixed email copy problems | Is one link less confusing than two links? | Yes | Yes - no one mentioned it as an issue |

#### Themes
##### Disclosure dispositions
Based on our research up to this date, it seems like we might want to design content around how people make decisions to share/not share information. There's a bunch of academic research suggesting that decisions about information sharing during single sign-on are based on prior experiences and predispositions, not so much the information offered by the service in the moment. 

It may make sense to segment the audience for MyUSA into three different categories:
* **Privacy protectors** people who minimized the amount of information they shared, which sometimes meant asking to cancel the entire transaction and sometimes meant asking if it was possible to share no information at all. Some privacy protectors read the text very carefully; others wanted to hit cancel at the first moment of suspicion.

:speech_balloon: For example, one participant's response to the toggles was: _"Can I opt out?."_ Her first impulse was to hit "cancel." After reading the help text, she'd still hit "cancel." For her, the information is "not specific -- share information to whom? from this website? to other agencies?" 

* **Rule followers** people who would use MyUSA if their employer (the US gov't) asked them to, even if it made them a little uncomfortable.

Another participant told me that he didn't read top text at first before deciding whether or not to share. He'd just hit "allow" because he'd been sent there by Benefeds. 

:speech_balloon: _"I'm on this page, that's what I'm here to do."_

* **Convenience optimizers** people who wanted to minimize the work of sign-in, even if that meant taking actions that made them a little uncomfortable. That would be the one participant who volunteered that she didn't want per-item permissions at all. Another person said, 

:speech_balloon: _""This feels like 40 pages of clicks"...it's "teasing," like those websites that keep you clicking."_

The following themes explain why I think those divisions make sense.   

##### More information is not always reassuring
For one participant, seeing the help text was "reassuring". For another, it "opened up a whole can of worms," suggesting new questions and suspicions he hadn't previously had. Questions included:
* Why does Benefeds want to email me?
* How often will Benefeds email me?

###### Fears of junk mail
![screen shot 2015-04-13 at 2 51 40 pm](https://cloud.githubusercontent.com/assets/10067318/7126248/ae8fb5d4-e1ec-11e4-965e-3afb45c19f86.png)

Participants in both conditions were suspicious about being contacted. One said that leaving the "Share email" option on would mean 

:speech_balloon: _"I will probably get a lot of junk mail. I don't see why they'd contact me."_

###### Suspicions about "sharing"
Participants in both conditions were taken aback by the word "sharing"
After clicking the "how does this help me?" link, one said:

:speech_balloon: _"After reading the help text, my first impulse is to hit 'cancel.' " The information is "not specific: share information to whom? from this website? to other agencies?"_

![screen shot 2015-04-13 at 3 00 15 pm](https://cloud.githubusercontent.com/assets/10067318/7126483/7127f808-e1ee-11e4-81f1-c6bae5b27dc9.png)

Another said, about the intro text on the toggles permission page, _"what does this mean? share with whom?"_

##### Basic usability
###### :white_check_mark: Email copy problems are resolved
None of the participants had questions about how to go to the email inbox and which link to click

###### :white_check_mark: Making data controls visible solves initial usability problems
All of the participants could turn sharing on and off for specific items

###### :boom: Reduce scrolling on laptop screens
Two of the five checkbox-condition participants either didn't know to scroll down or didn't realize what the page was for until scrolling down.

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

<img src="https://cloud.githubusercontent.com/assets/1598889/7028778/262a9f6c-dd26-11e4-90a9-7f37f29cf935.png" width=300px>

### Decision-first
Makes the controls for sharing information more visible

<img src="https://cloud.githubusercontent.com/assets/10067318/7057037/3fdae86e-de06-11e4-911b-c7203e938c27.png" width=300px>

## What we did

### Find participants 
#### Desired profile
Federal employees, _not contractors or general public_

#### Recruiting
Intercept between hours of 11am - 2pm in the lobby hallway of SFFB (e.g. lunch rush). This is working...okay. 

### Conduct interviews
#### Tasks
Walk through sign-in flow using Invision mockup (5 minutes)

1. Find sign in button
2. Get to email
3. Edit permissions
4. Explain what help text means

### Data
This is just going to be a table with all the data because I don't think we have enough data to really make it worth abstracting

#### Overall
- "not bad"
- "This feels like 40 pages of clicks"...it's "teasing," like those websites that keep you clicking

#### Per page
...after the third person I stopped asking questions about anything but the permissions screen because it seemed like the initial screens were, broadly speaking, acceptable. 

 | Explanation-first (checkbox) | Decision-first (toggles) |
:----------- | :----------- | :----------- |
**Initial screen** | 1. no problems <p> 2. can't find sign button <p> 3. no problems <p> 4. n/a <p> 5. n/a | 1. no problems <p> 2. no problems <p> 3. n/a <p> 4. n/a |
**Enter email** | 1. no problems <p> 2. no data <p> 3. no problems <p> 4. n/a <p> 5. n/a | 1. no problems <p> 2. no problems <p> 3. n/a <p> 4. n/a |
**Almost there** | 1. no problems <p> 2. no problems <p> 3. no problems <p> 4. n/a <p> 5. n/a | 1. seems like phishing. "I'm doubting if this is real or not" <p> 2. no problems <p> 3. n/a <p> 4. n/a |
**Email** | 1. no problems <p> 2. no problems <p> 3. wasn't sure what MyUSA is -- is it related to my benefits? <p> 4. I would delete this email. <p> 5. n/a | 1. "doubtful it's from the gov't," would ignore it unless told to use it by supervisor <p> 2. no problems <p> 3. n/a <p> 4. n/a |
**Permission screen** | 1. didn't know to scroll down, but understands that she can click <p> 2. just wants to click through; doesn't want per-item permissions <p> 3. wasn't sure what was happening -- is this another email thing? <p> 4. What is MyUSA? [Wouldn't read the top intro text]. Thinks the text is too generic. "Nothing means anything." Wants something like: "MyUSA is a program of...that helps me because...". She wouldn't ever turn off one item if she'd already decided to participate -- "it's all or nothing" [privacy sensitive] <p> 5. top text is "standard stuff". Doesn't see what the checkboxes do at first -- only notices them after he scrolls down the page. Then he has no problem unchecking one. He'd then check allow, since he's a federal employee it's fine. | 1. what does this mean? share with whom? "sensitive" to sharing personal information, would probably hit cancel <p> 2. no problems turning off name <p> 3. Didn't read top text at first before deciding whether or not to share. He'd just hit "allow" -- "I'm on this page, that's what I'm here to do." No problems turning last name off. "Sharing" means what we're going to TELL Benefeds. <p> 4. Not sure what yes/no means. To share information? Scrolls down and realizes that she would be allowing us to share information. Can I opt out? [no problems with toggle]. First impulse is to hit "cancel." After reading the help text, she'd still hit "cancel." The information is "not specific -- share information to whom? from this website? to other agencies?" |
**Help text**| 1. thinks that "your information will be shared with a database" <p> 3. not sure what "contact" means -- "what kind of info will it send me?" or what it will do with the information being shared [didn't see explanatory text?] <p> 4. Wants more specific info: e.g. "Benefeds will contact me for..." <p> "Sharing my email" means they'll contact me if they have something to ask me. "Personalize" means "give the email a more personal feeling." | 1. when told to click link, found the extra text "reassuring" <p> 2. "doesn't know" what help text for names means; email help text means "keep me up to date" <p> 3. Help text "opens a can of worms." Weekly mailings? How much mail am I going to get? <p> 4. No problems finding link. Email means "I will probably get a lot of junk mail. I don't see why they'd contact me." Personalize: "I don't understand. I don't see how it will personalize email. Maybe send me customized stuff?"|

## When are we going to do it?
* Sprint 24: planning
* Sprint 25 (Thursday): testing
* Sprint 25 (Friday): more testing
