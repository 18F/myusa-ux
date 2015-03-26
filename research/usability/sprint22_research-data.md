# Consolidated feedback - Sprint 22 research
[see actual report]()

## Sign in at Midas

P01, P02 immediately found the sign-up link.

P05 takes a minute 

### Choice 1: LinkedIn or MyUSA?

P03: I'm wondering why LinkedIn is first if it's a government website. Typically when I see pages that allow social sign-in I see more choices than LinkedIn. **That makes me think that this is a page for people who are trying to network or that is corporate.**

P05: **I don't really like linking things.** It's just more aggregate data -- unless I know what it's being used for, I'm suspicious of that. I don't like knowing that LinkedIn knows where I go. 

P01: **First thought would be to click on LinkedIn** bc I don't know what MyUSA is

P01: not sure about why email address there

P02: But if I didn't have a MyUSA account and didn't want to create another account I probably would. I have a LinkedIn account that I'm trying not to use to sign up for anything anymore. If there were other services, I'd always choose MyUSA. LinkedIn seems to spam me more than help me. I get a lot of notifications about things. 

P05: I don't know if I need to click on the button or sign in. The bottom seems like the form that applies to the two top buttons instead of the third option.

**[PROBLEM: Email/password forms look like they apply to both of the top two options. This is especially a problem because other studies have shown non-technical people are prone to entering IdP unames and pwords in those fields]**
**[SIMPLE FIX: Make a big line, or number them]**

### MyUSA popup

P01: I'm not sure I want to connect with Google. I mostly use my personal Google account. Or I connect with email address. I'd prefer that. The Google+ sign caught in my mind. It's a social network. I don't want those worlds connected. 

*Liz: Which worlds?*

P01: My Google Plus account and a government site, or signing up for a government account. 

P01 <Clicks email>

P01: Defaulting to GSA email. 
I like it when various devices remember me for as long as possible.

P01: All makes sense to me.

P03: Connect with Google raises some privacy concerns. I try not to connect things with Google, I try to connect with my email. 

P03: I don't really use any of the other Google features with my work email. Because of FOIA, everything I do on my work computer is connected. 

P03: if the options are MyUSA vs Google vs LinkedIn vs Facebook, its' worth pointing out that -- being very explicit about how the information is being stored and how it's NOT being used to construct this massive profile of you is helpful. Mitigating risk of people thinking the government is looming over them. 

### Email 

P01: I'm confused. Below the access link is the connect to MyUSA link. I'm not sure if they're different. Did I make a mistake?

**[PROBLEM: Having redundant links is confusing]**
**[SIMPLE FIX: Remove one link]**

### Google Auth
P02 signs in with Google. Both accounts show up and he picks one

P05: I'm familiar with the form and these options

P05: why does it want to look at my email address? might be nice to warn people in advance

### MyUSA Auth

**[PROBLEM: If you sign in with Google, the permission screen reiterates the same choices as the Google auth screen -- except this time you get a choice]**
**[SIMPLE FIX: Don't include a sign-in with Google choice in MyUSA...though that screws with GSA folk]**

P03: I don't even know what my basic information would be in my government account, besides my email and my name. But I think it's worth specifying what basic information is to people, because I'm not sure.

P01: MyUSA data -- I don't know what that means.


P01: I'm a little bit confused. I guess -- address? <pauses> I don't really understand what [requesting permission to] means?

P01: Usually I would expect something like -- with a social network, it would be asking for permission to tweet on my behalf. It's a little bit worrying. 

P01: I didn't understand what it was requesting permission for. That was the only time I was like "this is not like the other things I've done before". I felt a little lost in what I was trying to do. 




P01: The two headlines feel like two options, and I have to choose one or the other. 

P04: "Had you not asked me to do that, I would not have thought [changing my name in the auth screen] WAS an option"


P01: <looking at email> I don't understand why I would turn that off. 


P01 knows that clicking checkbox would turn it off. P01: "Very simple" [to have it address you only by your first name] <Does it>


P04, P01 immediately finds and clicks off names. 

It takes P02 a second to figure out how to change his name -- at first he thinks he needs to sign in again with a different credential. He's signed into MyUSA a few times but has never clicked the arrows before.


P02: "Usually you click the chevron arrow to get more information about WHY they need to know that information."

P05 <clicks chevrons> I don't know what the check marks are for. What would it mean if I [unclicked] it? Seems like there should be a button to block all access if so. 



P03: Normally skips phone. Because I don't like to receive calls from people. Well, the gov't wouldn't be calling me


P05: lots of information here! It seems kind of similar to what I had before.


**[PROBLEM: Two headlines feel like two options]**
**[PROBLEM: People are not seeing that the headlines are collapsed menu titles]**
**[SIMPLE FIX: make headings open by default]**
**[SUGGESTION: A BUTTON TO UNCLICK/CLICK ALL]**


P02: every time I sign into Midas I had to read > to figure out what it wanted me to do, but it seemed like something I should read

P04: it's a warning to tell me that what this is going to be requesting permission for -- pretty standard

P03: It looks like Midas dev has filled out one of those application forms and would like to know email address and name. Only information in my profile that Midas would be able to receive is my name and email address.

P03: [to change permissions] My first thought is that I would have to change something in my profile. Then I thought that was silly, so I looked for it in a different way [e.g. the dropdown]

P02: Based on my interaction with MyUSA, that tells me that these services need to tell me what information they're going to use and each service -- that's not a shared set of permissions across all these services. If I'm sharing with the IRS all of my tax information, I know that the information that I share with them won't be available to every user on Midas. I don't necessarily trust that other third parties accessing the data I'm giving to the govenrment won't share that data around. And it's probably better to assume they will share it around. Or use it for profit.

## Midas profile
P02: [Green button tells me] This application is hooked up in some way to MyUSA.Based on the last screen, it's to fill in my name and the email address above and nothing else. Green color tells me that that is working properly. 

P02: I really like that this is so prominent on the front page. A lot of times services bury it. I assume, perhaps wrongly, that more will fill in here if I have more accounts connected. 

P05: [The green badge] means that all the yeses went through and I have this live link to my Google. It goes back to the whole LinkedIn / MyUSA thing at the beginning. If I had said LinkedIn, that would be showing up here besides MyUSA. That's my first thought as a user.  

**[BUG: Permissions chosen during sign-in are not carrying through. Need to test]**

# alpha.my.usa.gov
P01: I was wondering what the whole thing was. Saw that I was already signed in. Pretty cool that it's working.

P01: What am I going to do with this? What's my purpose here?

P02 likes that profile and applications buttons are so centered on splash page, above the folder. Even on an old Mac with a smaller viewport those buttons would be prominent. Communicates that the most useful things are the profile and the applciations that are connected to it. 

P02: If I hadn't already been to Midas and wasn't an 18F person, I'd wonder why I'd make an account on MyUSA. I'm not building a small business or retiring anytime soon. And I didn't even know USA.gov had accounts I might need. 

P05: MyUSA is code for single-sign on. I've now got that. As a user looking at this site, I look at this as a way to do my IRS tax profile or social security. Things that I want to get to -- it's like a funnel that lets me look at all those applications to all those different place. 

P05: I think of it as a portal. That's partly because of the really pretty image behind. Like, here's the expanse of images behind.


## Edit profile data

P01, P02, P05, P04 change last name task correctly and quickly. 

P01, P02 hit the save button. P05 does not. 

P01: I knew I needed to save because I would expect loading sign if it saves automatically

**[SUGGESTION FOR THE FUTURE: enable automatic saving]**

P04: all this information I want fill out, but I'm not entirely sure why yet

P02: strange leading between fields and heads (too small)

P02 likes that the placeholder doesn't go away when you click into the field. 

P03: If I were signing up through something like Midas, I'd be wondering why the government wants all this information right away. If I'm hitting this on some other site -- if the options are signing in with Google or my email or this, I would want a better explanation of what this is.

P03: people fill these things out and never update them. how do you get people to come back and update them as the parameters change [like marraige and kids] which might affect the applciations. On FB its easy because it's your profile. This is a little different. 

**[LONGTERM CONCERN: ONBOARDING AND REBOARDING TO KEEP INFO CURRENT]**

## Find 2FA

**[This is the 2nd person who has made this mistake. I think it's an artifact of the question order. But it's something to flag for a microcontent clarification]**

### Finding the page
P01 first checks profile (Phone), then additional information, then notifications, and only then account settings.

P02 first checks Additional information, then account settings.

P03, P04, P05 finds and enables it immediately.

P01, P02 are able to add a phone number once they find settings. 

P02: Saw confirm deletion and warning block. Was drawn to that first. So I ended up having to look up and then saw 2FA. I noticed the big red button on the bottom first -- I don't want that!

P05: It's a security setting, so I'll guess that it's in account settings. It's something that I choose.

P05: Maybe you want to have a primer on 2FA? Would you like to turn on two-factor? 

P05: first saw "confirm deletion button", and then worked my way backed up the page. 

P05: This page seems really busy. There's a lot of different things going -- red and yellow and blue. It doesn't seem very clean.

### Account recovery page
**[BUG: "Skip this step" button shouldn't appear in this flow. Need another page for when it pops up.]**

P01: That makes sense and I've been through it before. 

P05: I think the fact that it says "Account Recovery" vs "Two Factor" is confusing. This isn't about getting back into my account, it's verifying my account. 

## Applications

P01: Menu bar confusing. Because options have something underneath them except "My Applications," which makes me think it's empty. 

P05: It's interesting that it's not choices. "Permissions" means something I get to choose or configure live. 

P01: I hate these popups personally, because they disrupt everything. Now I don't have any authorized applications. 

P02: really clear to me what to do here -- if I want to revoke a service or understand what they're using, it's very clear to me that this is where I do that.

P02: I don't know why I'd ever create an application, and the color makes it seem like it's very important for me to do that.

### Create application
P04: creating my own application with an API that I can -- huh -- where I can actually put information 

P04: [Making an application] looks like other things that I've used 

P03: I've done this on Facebook. If you were going to create something that used MyUSA as a sign-in -- this is for anyone who would want to use MyUSA's signup as a way to authenticate users. 


## Notifications
P05: [on/off button] That's so cool. I love that. I click it, and you can see that the computer is doing something, so I know that this setting did something.

P05 at first wasn't sure where to change his contact settings for Midas -- "I'd think that I'd have it in [Applications]" Manage notifications is general. 

P02: I kind of wonder what I'm going to get notified about. I guess applications could be authorized -- that seems kind of handy. I like that from a CAN SPAM perspective -- I go to this 

## Additional information
P02: I don't know why additional information is on a separate page, except that it's tidier. Unless it's just very rarely used or needed. 

P02: I also don't know why I'm giving you that information. Maybe if I'm applying for a job or VA benefits.

# General suggestions
P01: Minimizing popups

P01: Everything's been pretty responsive. Site looks good and behaves pretty well.

P05: Site's really clean -- except for account settings. This is definitely a workable template to grow things further.  

P04: the site is "really really pretty" "It's a beautiful dashboard"

P04: "really clean but I need more purpose around this dashboard, more call to action when I'm first logging into it, to get me to engage with it. just another website where I'm entering all my information if I want to use it, but I'm not sure"

P05: You're missing a lot of education about what single sign-on is and what it means and what 2FA is and what it means. 

P05: The user story of how they come to MyUSA is so important, because if they come with very little information we need to give it to them. The people we want to target are the ones that don't necessarily know -- the ones that would be sent there by another site. 

P05 suggest that the benefit statements are "Simple registration and security for using government."

P05: a little shared icon that isn't obtrusive that would signal the common sign-on identity across websites -- maybe a little tag along the side?

P04: Look at onboarding techniques. Intercom.io -- 1, 2, 3 steps: start with this, then this. 

P03: I think also spelling out for developers what they should think about using it for. having some examples of applications would be really helpful here [for developers]. 

P03: people will think it's only for the government. people are really used to signing in through FB and they don't know what it means. That's become the normative behavior. I don't think people realize what data they're giving up because of that. Good and bad for this. I think that this is labelled MyUSA and has to do with the government might raise some eyebrows and make them more conscious of signing in in other ways. Worth being explicit about storing information and who can obtain. 
