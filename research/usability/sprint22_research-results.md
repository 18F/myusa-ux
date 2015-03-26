# Midas + MyUSA in-house usability tests

## Sign-in and Account management 

**March 23, 2015 | @esgoodman** 

## tldr;

### Hypotheses tested
The app authorization screen is a sticking point in onboarding - TRUE!

Transitioning to personal email and back does not cause problems - TRUE!

Users are having trouble configuring 2FA in the account management site - ONLY KIND OF TRUE

## Methods
### Participants
  * 3 developers
  * 2 content/communications
  
### Tasks/Questions 
See [research plan](sprint22_research-plan.md) for script 

1) Sign up for a MyUSA account at Midas-dev

* Use either Google or email/address
* Do _not_ authorize MyUSA to share your last name with Midas

2) After logging in, go to alpha.my.usa.gov

* Change your last name
* Add 2FA
* Optional: Change notification preferences
 
3) Any other suggestions?

## General feedback
### Visual design is appealing
P01: *Site looks good and behaves pretty well.*

P05: *Site's really clean -- except for account settings. This is definitely a workable template to grow things further.*  

P04: The site is *really really pretty* 

### We need to better educate visitors

#### About why we are asking for information in the profile site
P04: _**I need more purpose around this dashboard, more call to action** when I'm first logging into it, to get me to engage with it._

#### About why the features of MyUSA are important
P05: _You're missing a lot of education about what single sign-on is and what it means and what 2FA is and what it means._ 

P03: _I think that this is labelled MyUSA and has to do with the government might raise some eyebrows and make them more conscious of signing in in other ways. It's **worth being explicit about storing information and who can obtain it.**_

:heavy_exclamation_mark: **Suggestion** Look at onboarding technique of Intercom.io (P04)

#### For developers
:heavy_exclamation_mark: **Suggestion** Having some examples of applications would be really helpful here [for developers]. (P03) 

## Sign in at Midas

Most participants immediately found the sign-up link. One took a few seconds. 

### Choice 1: LinkedIn or MyUSA?
#### LinkedIn prompts some concern
P03: _**I'm wondering why LinkedIn is first if it's a government website.** Typically when I see pages that allow social sign-in I see more choices than LinkedIn. **That makes me think that this is a page for people who are trying to network or that is corporate.**_

P05: _**I don't really like linking things.** It's just more aggregate data -- unless I know what it's being used for, I'm suspicious of that. **I don't like knowing that LinkedIn knows where I go.**_

P02: _If there were other services, I'd always choose MyUSA. **LinkedIn seems to spam me more than help me. I get a lot of notifications about things.**_

#### But familiarity can breed comfort
P01: My **first thought would be to click on LinkedIn** because I don't know what MyUSA is

:heavy_exclamation_mark: **Suggestion** _**A little shared icon** that isn't obtrusive that would signal the common sign-on identity across websites -- maybe a little tag along the side?_ (P05)

#### Minor usability problems

##### Email/password forms look like they apply to both of the top two options 
This is especially a problem because other studies have shown non-technical people are prone to entering IdP unames and pwords in those fields.

:heavy_exclamation_mark: **Simple design fix** Make a big line between the OAuth options and the site account option, or number them

### Choice 2: MyUSA: Google or email?

Everyone was familiar with the options. Google explicitly gives people the choice to select a personal or work account. 

#### Google also prompts concern
P01: _I'm not sure I want to connect with Google.  **The Google+ sign caught in my mind. It's a social network.** I don't want those worlds [personal Google Plus and a government site] connected._

P03: _**Connect with Google raises some privacy concerns.** I try not to connect things with Google, I try to connect with my email._ 

:heavy_exclamation_mark: **CONTENT suggestion** _Be very explicit about how the information is being stored and how it's NOT being used to construct this massive profile of you is helpful. Mitigating risk of people thinking the government is looming over them._ (P03) 

:heavy_exclamation_mark: **CONTENT suggestion** Tell people in advance what kind of data MyUSA will request from Google (P05)

#### Minor problems
##### Redundant-looking auth screens
If you sign in with Google, the permission screen reiterates the same choices as the Google auth screen -- except this time you get a choice. It's not precisely redundant but it _looks_ redundant.

:heavy_exclamation_mark: **Simple fix** Don't include a sign-in with Google choice in MyUSA...though that makes extra work for people who like using Google

### Transition to email client and back

None of the participants had any real concerns or difficulties. 

#### Minor problems

##### Having redundant links is confusing 
P01 was "confused" by the two links and thought he might have made a mistake by clicking the first one. 

**Simple content fix** Remove one link
 
### MyUSA auth screen: editing permissions
All of the participants were eventually able to edit data in the auth screen. Two participants had no problems. Three hesitated or made errors.

#### Participants were not able to edit data without prompting

##### None of the participants realized at first that they could control what data is being shared
The root cause of all the problems appears to be the unfamiliarity of the "edit data" interaction. Most OAuth services do not grant item-by-item control over what is shared. Participants were very positive about having that option, but didn't where or if to look for the controls. 

P01: _I'm a little bit confused. I don't really understand what [requesting permission to] means?_

##### Many participants did not realize that the "headlines" are collapsed sections
Which means that they don't realize they can change what data is being shared. 
P04: *Had you not asked me to do that, I would not have thought [changing my name in the auth screen] WAS an option*

Two participants assumed at first that they needed to return to the profile to edit data

P01 assumed that the headlines were either/or options

This supports findings from the [comparative concept evaluation](link goes here!) we did with GSA/HHS employees back in January

:heavy_exclamation_mark: **Simple fix** make headings open by default

##### Assumption of no important functionality inside the collapsed sections
P02: *Usually you click the chevron arrow to get more information about WHY they need to know that information.*

##### Once collapsed sections were open, participants didn't realize they could uncheck the boxes
P05: *I don't know what the check marks are for. What would it mean if I [unclicked] it? Seems like there should be a button to block all access if so.*
**Simple fix** Make the checkboxes more visually prominent

#### Participants are uncertain what access they are granting
Uncertainty about what MyUSA is asking for sparked anxiety ina few participants.  

##### What data will be shared?
P03: _**I don't even know what my basic information would be** in my government account, besides my email and my name._
P01: _**MyUSA data -- I don't know what that means.**_

##### What will MyUSA do with that data?
P01: _**I didn't understand what it was requesting permission for.** That was the only time I was like "this is not like the other things I've done before". **I felt a little lost** in what I was trying to do._
P01: _With a social network, it would be asking for permission to tweet on my behalf. **It's a little bit worrying.**_
  
#### Seeing permissions can be reassuring
P02: *Based on my interaction with MyUSA, that tells me that these services need to tell me what information they're going to use and each service -- that's not a shared set of permissions across all these services. If I'm sharing with the IRS all of my tax information, I know that the information that I share with them won't be available to every user on Midas. **I don't necessarily trust that other third parties accessing the data I'm giving to the govenrment won't share that data around. And it's probably better to assume they will share it around.** Or use it for profit.*

## Visit alpha.my.usa.gov
### Existing landing page
While evaluating the landing page was not a planned part of the test, participants inevitably had opinions about it. 
#### Too little explanation of MyUSA's purpose
We knew this already from the [landing page content evaluation](link here!). These findings reiterate it. 

P01: _**What am I going to do with this? What's my purpose here?**_

P05: *MyUSA is code for single-sign on. [...] **I think of it as a portal.** That's partly because of the really pretty image behind. Like, here's the expanse of things you can do.*

### Edit profile data

P02 likes that the placeholder doesn't go away when you click into the field.

#### What's this information for?
Two people wondered why the government needed all this information about them. 

#### Question: How do we keep profiles up-to-date in the long term? 
P03: People fill these things out and never update them. how do you get people to come back and update them as the parameters change [like marriage and kids] which might affect the applications.
 
##### Is the save button for profile data visible enough?
Every participant found the correct page and field quickly. However, one person did not hit the save button the first time around.

### Set up 2FA 

#### Two-factor authentication is hard to find
##### The correct screen is not obvious
Two people had difficulty locating the controls for 2FA.

* P01 first checks profile (Phone), then additional information, then notifications, and only then account settings.
* P02 first checks Additional information, then account settings. 

#### Minor problems
##### Once on the correct screen, people first see the delete functionality
Two people immediately found the 2FA controls on the screen. The other 3 got distracted by the big red "delete" button. 

P05: _**This page seems really busy.** There's a lot of different things going -- red and yellow and blue. It doesn't seem very clean._

#### Inconsistent labelling of 2FA functionality 
One person found it confusing that the 2FA functionality is described as "Account recovery" _and- "Authentication" (P05). 

The issue to decide is, **Which one should it be?** 

But everyone successfully completed the task, suggesting that the inconsistent labelling is a minor problem. 

:heavy_exclamation_mark: **Suggestion:** do we need some microcontent (P05) on 2FA?

#### Bugs
##### Edited profile data is not being changed in Midas
##### "Skip this step" button shouldn't appear if you're not creating a new account

## Check what applications are authorized to use this information

There's no clear overall trends here. Each person seemed to have a different concern.

### The navigation bar may be confusing 
All the options except "My Applications" have a subitem, which made P01 think "My Applications" was empty. However, P02 found it "really clear" that "My Applications" was the place to go. 

### "Permissions" doesn't actually control anything 
P05 was surprised that he couldn't change data sharing permissions in the "permissions section" 

P05: **"Permissions" means something I get to choose or configure live.** 

:question: **Question: Should we allow users to change permissions in the profile section?** As per [privacy-by-design principles](https://www.privacybydesign.ca/index.php/about-pbd/7-foundational-principles/), it seems like we should.

### Create application button distracts from core functions

P02: **I don't know why I'd ever create an application, and the color makes it seem like it's very important for me to do that.**

### Registering an application was easy for expert developers
Our registration functionality is consistent with other services, such as Facebook's. Two participants walked through it and found it familiar and easy.  

## Change how MyUSA contacts you

### Notifications was not an obvious place for per-application controls

P05 at first wasn't sure where to change his contact settings for Midas -- "I'd think that I'd have it in [Applications]" Manage notifications is general. 

### Knowing that you have control is important

P05: [on/off button] That's so cool. I love that. I click it, and you can see that the computer is doing something, so **I know that this setting did something.**

P02: I kind of wonder what I'm going to get notified about. I guess applications could be authorized -- that seems kind of handy. **I like that from a CAN SPAM perspective.** 


# Big themes for design inspiration

## Having control is a welcome surprise

I've now talked to about 24 people (mostly within the gov't) about what MyUSA does and how it works. 100% were surprised by the amount of control we give users over  -- even though the authorization screen had major usability problems. 

:question: **Because having control is surprising, what kind of education/onboarding would help inform users of their options?**  

## Users are making snap decisions based on very little information

LinkedIn or MyUSA? Email address or Google Auth?

Users are making trust decisions on very little information. Participants often read a lot into small signals, as with the participant who got a little nervous about the presence of a G+ icon. 

:question: **How do we help people make decisions quickly..but confidently?**  

## Assume user distrust
There's a lot of distrust of the behavior and motives of commercial providers as well as government.

P02: _**I don't necessarily trust that other third parties accessing the data I'm giving to the government won't share that data around. And it's probably better to assume they will share it around.** Or use it for profit._

:question: **How do we make sure MyUSA is behaving in a trustworthy way?**
:question: **How do we communicate that we are trustworthy to distrustful users?**
