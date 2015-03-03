# Testing MyUSA with government employees

## What we did
+ Document how federal employees manage user account information 
+ Evaluate two different design directions using a scenario-based demo 

45 minute semi-structured interviews at participants’ workstations

6 federal employees
+ 4 HHS
+ 2 GSA
Video or audiorecorded (with permission), transcribed, and analyzed

## Findings
### Current sign-on practices

#### Managing account data is hard work
![graphic describing differences between PIV card model and Google sign-on.](https://github.com/18F/myusa-ux/blob/master/images/Screen%20Shot%202015-03-02%20at%201.59.38%20PM.png)
PIV cards are attached a person; people using them feel like there is no intermediary between them and the site they're trying to access. Google OAuth makes it clear that the user is going through a third-party

Despite those tools, many online services still require **unique user accounts**.

**Each account has different associated usernames, passwords, and change schedules

> All participants had more than 10 different accounts to manage. Two had more than 20. 

> One participant estimated that he changed a password at least once a week.

So government employees create **personal workarounds**

> “If I left the paper at the office I wouldn’t have it available. And also because you have to change the passwords every few months it was easier to have something you can update in realtime.”

> Participant 4, GSA, *stores usernames and password hints in Google Docs spreadsheet* 

**Every participant interviewed had a different workaround**

**Email was the preferred tool.**
>Half of the participants used email to keep track of government account information.

**Individual workarounds vary in security**
+ Password-protected thumbdrive with account info in plaintext on Word doc
+ Website names saved as contacts in address book, and usernames and passwords stored as fields
+ Usernames and passwords saved as hints in Excel spreadsheet and Word doc
+ Account info written down in paper notebook, kept by desk in secured office
+ Usernames and passwords stored in drafts in email

>“My travel app requires five separate pieces of information. What else do they expect me to do?”

>Participant 2, HHS, *stores usernames and passwords as drafts in email*

### Reactions to federated identity schemes
While government employees want single sign-on, they have qualms about commercial providers
 
#### Are government employees interested in using a single sign-on across government websites? #497 
The short answer: yes (given that we interviewed six people). 

However, there was **intense wariness** about the single sign on options presented
+ Google
+ Verizon
+ Paypal
+ ID.me

In general, mistrust of commercial providers' motivations colored responses: 

![what we are saying does not match what participants are hearing. We say "Allow Paypal to verify 
your identity so that you can use this government service" and they hear: "Share information about your finances with the government"](https://github.com/18F/myusa-ux/blob/master/images/Screen%20Shot%202015-03-02%20at%202.45.58%20PM.png?raw=true)

#### How do government employees react to signing in with companies that are associated with a specific business function (such as Verizon or Paypal)? #522 

Reactions were not positive, including: 

+ **Uncertainty**
> I don’t know who’s taking the information and using it.
> Participant 1, HHS

+ **Distrust**
> Why would the government be sending personal information on its employees to [Google] for advertising purposes?

> Participant 2, HHS (*No such exchange of information is happening or was communicated!*)

#### How do government employees react to signing in using social network logins (e.g. Google)? #521 

2 of 6 were concerned about mixing work and home accounts accidentally

> I just like to keep work and personal life separate

> Participant 3, HHS

### Security and trust

#### Do users trust that MyUSA provides secure access to government websites? #498 

Signing in with a government account can seem more secure than a social network login

> Q: What would happen if you signed in with Yahoo?

> A: In my mind it would make it insecure. That if there’s a compromise on the Yahoo! side it would trickle down. Which wouldn’t be the end of the world, because it’s not (.) there’s nothing private in here. And I would also think it’s weird that a government website is using my personal email. Just because it seems insecure.

> Participant 2, HHS

#### Do users believe that MyUSA handles their personal information appropriately? #499
See above. 

#### Do users trust MyUSA as an authentic government service #65 
Yes, though a few expected more of the warning text that usually shows up for them when they access work-related sites. 

P02 expected a “seal” or a “warning” to assure himself that this is a legitimate government website. “Clunky” official websites he uses seem “locked down.” Salesforce, for example, “looks modern” and so seems less secure. 

#### Are users willing to provide additional info during application authorization? #55
*Maybe.* Asking for information during authorization makes for more work -- more evaluation of what the consequences might be and whether the requester is trusthworthy.

> It sounds like you have to manage [MyUSA] — what it’s going to do. I guess it’s reassuring that it [the data] belongs to me, but at the same time I don’t know who’s taking the information and using it and it looks like you’re giving permission to pass on this information to certain things.”

> P01, HHS

#### How do users respond to auth mechanisms that don't use passwords?
With worry.
1) Making a password signals that one is creating an account. Without a password, some participants did not realize they were actually making an account. Being signed into the application after clicking a link surprised them.

![screenshot from the demo we tested](https://github.com/18F/myusa-ux/blob/master/images/Screen%20Shot%202014-12-19%20at%202.54.49%20PM.png?raw=true)

> “I don’t know if I’m expected to have a password already, so I don’t know if this is signing up or logging in.”

> P04, GSA

2) Passwords signal security. See below.

> "How can you possibly go from domain address"...to login? "Not enough authentication of me to be logged in. It's hard to imagine that just my email is enough. It gets me nervous. Anyone could know my email"

> Participant 06, GSA, missed that his email account itself is password-protected 

Participant 06 also highlighted an important case -- people with children who share their home computers and don't want to stay automatically signed into sensitive federal services.

### Authorization 
*Most participants saw no trouble with authorization, but did not understand their data sharing options*

Specifically, they did not understand:
+ That permission is optional
+ That information is by default opted out
+ That sign-on providers can’t draw information from other government sites, even if users are government employees

#### Can users create an account? #490 
Yes

+ No one had problems navigating to and from email
+ Only a few, minor hesitations in finding the first “connect” button 
+ Participants could correctly identify sign in status

#### Are users able to authorize their first application through MyUSA without significant difficulties? #500 
Without difficulties that would prevent them from completing the task, but with significant qualms about the privacy of their data.  

#### Are users able to authorize and login to another MyUSA-enabled application if they already have an account? #494
Seems like it, though the swift pass-through was off-putting for some 
