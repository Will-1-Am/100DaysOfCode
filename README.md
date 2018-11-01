# 100DaysOfCode

### R1Day020 Thursday, 01 November 2018
Day 20 Round 1 #100DaysOfCode and despite embracing Apple documentation unconditionally, the moment feels distant when it will reciprocate.  #LondonAppBrewer is an inspiration and one can't help but appreciate the trials and tribulations developers endure.

Added category feature to ToDoey App making use of a linked one-to-many "category" entity to the "item" entity.  Extensions were covered in the same module, and serve to separate bits of code that would otherwise crowd the main ViewController.  Using "didSet" to specify what happens when a variable is set with a new value.  CRUD using a context and committing the current context state to a persistent container using context.save.  Accessing a singleton to use its delegate property to tap into a persistent container - a lazy variable.

Attended #freeCodeCamp Meetup - and learn about coffee & code sessions that the group hosts.

Looking forward to an introduction to Realm with #LondonAppBrewer.

### R1Day019 Wednesday, 31 October 2018
Happy Hallowe'en! Completely finished reviewing AWS Well-Architected Questions, Answers and Best Practices today Day 19 of #100DaysOfCode.  

Tidied up this file so that the latest entry is at the top which should make it easier to edit and read.

nspredicate cheatsheet
https://academy.realm.io/posts/nspredicate-cheatsheet/

nspredicate
https://nshipster.com/nspredicate/

### R1Day018 Tuesday, 30 October 2018
Day 18 R1 #100DaysOfCode began with a review of AWS Well-Architected Questions, Answers and Best Practices.  And now for some Swift coding with #LondonAppBrewer.  

Implemented SQL lite database using the CoreData Framework in the ToDoey app.  Looked at Create Read Update & Destroy (CRUD) techniques w.r.t. SQL lite data base.  Installed Datum Free for the ability to view the data file and manipulate it.

How cool is that?!  You can now side-load apps with WiFi!  No more cables. Wa Hoo! @LondonAppBrewer #100DaysOfCode  First connect the iPhone & computer with the lightning cable. Then in Simulator menu go to Hardware > Device > Manage Devices... then Tick Connect via Network.  Do disconnect the cable from the iPhone and commence side-loading.


### R1Day017 Monday, 29 October 2018
Day 17 begins and while I did a review of singletons and UserDefaults yesterday, the day will not be counted as one of the #100DaysofCode - Pumpkins had to be carved...🎃 @LondonAppBrewer #freeCodeCamp

Swift development tutorial https://developer.apple.com/library/archive/referencelibrary/GettingStarted/DevelopiOSAppsSwift/

Apple developer archive
https://developer.apple.com/library/archive/navigation/

//Ternary operator ==>
//value = condition ? valueIfTrue : valueIfFalse

ToDoey[1748:336062] [User Defaults] Attempt to set a non-property-list object (
    "ToDoey.Item",
    "ToDoey.Item",
    "ToDoey.Item",
    "ToDoey.Item"
) as an NSUserDefaults/CFPreferences value for key TodoListArray

'NSInvalidArgumentException', reason: 'Attempt to insert non-property list object (
    "ToDoey.Item",
    "ToDoey.Item",
    "ToDoey.Item",
    "ToDoey.Item"
) for key TodoListArray'
The above crash data is an indicator that we have reached the limits of the plist as the itemArray object is now a custom array and is no longer compatible with the plist.  Additionally, there could potentially be performance implications owing to the array size and general size of the plist.

Implemented NSCoder to encode and decode data to a custom plist "database".  Until now, the following methods of data storage and retrieval:  an external database (Firebase) in the Flash Chat app; the UserDefaults plist in the ToDoey app; and a custom plist has now been defined in ToDoey.

Reviewed AWS Well-Architected Framework
https://d1.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf


### R1Day016 Saturday, 27 October 2018
Learned more about UserDefaults and Singletons with @LondonAppBrewer on Day 16 R1 #100DaysOfCode
https://developer.apple.com/documentation/foundation/userdefaults
https://stackoverflow.com/questions/137975/what-is-so-bad-about-singletons


### R1Day015 Friday, 26 October 2018
Day 15 R1 began with a bit of JSON parsing for embellishment to the Clima App #LondonAppBrewer. #100DaysOfCode

Completed Chapter 3 of Learn Enough Command Line to be Dangerous - history, curl, bang & double bang, top, grep, less, head, tail... really useful commands. https://www.learnenough.com/command-line-tutorial#aside-technical_sophistication

Continued with the ToDoey App and implemented data persistence using UserDefaults method allowing user data added in app to be available when app is restarted.  Also created a new Playground for experimenting with UserDefaults.


### R1Day014 Thursday, 25 October 2018
#100DaysofCode rocks on day 14 R1 with swift coding and @LondonAppBrewer.

Idea to add wind direction to the clima app.

Why "override func"? Overriding declaration requires an 'override' keyword.  - Answer: https://docs.swift.org/swift-book/LanguageGuide/Inheritance.html#//apple_ref/doc/uid/TP40014097-CH17-ID196

ToDoey App - Todo list complete with datasource and delegate methods.  &  Add new item functionality complete - custom items can be added to array through an alert text field.  Uploaded project to github repository.


### R1Day013 Wednesday, 24 October 2018
The barebones of the third #freeCodeCamp project is now on code pen on day 13 R1 of
#100DaysOfCode.  Looking forward to fleshing out this Product Landing Page. https://codepen.io/will-1-am-the-Iceman/full/BqqMqy

Completed Chapter 2 of Learn Enough Command Line to be Dangerous - more a review but it is always nice to refresh. https://www.learnenough.com/command-line-tutorial#aside-technical_sophistication

Started ToDoList App with #LondonAppBrewer #100DaysOfCode


### R1Day012 Tuesday, 23 October 2018
Time to make a start on my third #freeCodeCamp project on this the 12th day of
#100DaysOfCode R1.

Flavio Copes has a great blog and I found this piece on HTTP Status Codes https://flaviocopes.com/http-status-codes/

Had a look at Brian Advent's website https://www.brianadvent.com/ which looks very interesting for iOS development.

Found a piece on #pragma mark on stackoverflow.com https://stackoverflow.com/questions/35963128/swift-understanding-mark

"The // MARK: and // MARK: - syntax in Swift functions identically to the #pragma mark and #pragma mark - syntax in Objective-C.

When using this syntax (plus // TODO: and // FIXME:), you can get some extra information to show up in the quick jump bar."

Wrote two entries for the git knowledgebase in the #freeCodeCamp.  git config and git rm commands are no in full effect.  #Hacktoberfest2018

How to update a git hub fork - Great step-by-step article https://github.com/KirstieJane/STEMMRoleModels/wiki/Syncing-your-fork-to-the-original-repository-via-the-browser


### R1Day011 Monday, 22 October 2018
R1 Day 11 Another day of golden opportunity begins with finding a resolution for the error in my new Swift app - "Reading from public effective user settings." #100DaysOfCode #LondonAppBrewer

First camera app now working! Thank you @brianadventcode for your awesome tutorials - and some tweeking... @LondonAppBrewer #100DaysOfCode

Learned that it can help to specify the data type of a constant when it is an optional in Swift.

Finished Day 11 with a shabang and a rewrite of an article about Bash in support of #Hacktoberfest2018 #100DaysOfCode  Roll on day 12.


### R1Day010 Sunday, 21 October 2018
R1 Day 10 Spent part of the day trying to implement the front camera in an iOS app.  #100DaysOfCode

One of the first issues with my new camera app was reported with the followng message.
"uncaught exception 'NSUnknownKeyException', reason: '[<xxxxx.ViewController 0x13bd0ba60> setValue:forUndefinedKey:]: this class is not key value coding-compliant for the key cameraOut.'"
Resolved by updating  the name of the imageView in Connections inspector.  

The following error in my camera app needs to be looked.
"Reading from public effective user settings."  - I suspect this is something to due with getting permission to use the camera.


### R1Day009 Saturday, 20 October 2018
Just in case you thought I was slackin', it is R1 Day 9 and I have been at it, hopefully fulfilling some of my  #Hacktoberfest2018 obligations by submitting my first ever real PR by doing some writing for MailHog https://github.com/mailhog/MailHog !  #freeCodeCamp #100DaysOfCode  


### R1Day008 Friday, 19 October 2018
Day 8 begins with getting more familiar with git.  The @LondonAppBrewer y's "Git, GitHub and Version Control" module is presented really well.  Check it out if you're into that sort of thing. #100DaysOfCode #freeCodeCamp

Git has got a new fan!  Browser, CLI and Xcode gitting is awesome.  Thank you @yu_angela & #LondonAppBrewer.  #100DaysOfCode


### R1Day007 Thursday, 18 October 2018
What better way to start R1 Day 7 than to register for Hacktoberfest 2018?! https://medium.freecodecamp.org/hacktoberfest-2018-how-you-can-get-your-free-shirt-even-if-youre-new-to-coding-96080dd0b01b  #100DaysOfCode @github @digitalocean #freeCodeCamp

https://codeweek.eu/

The issue with the Flash Chat project and the ChameleonFramework could be related to an installation corruption issue as a fellow student pointed out that a color reference has been renamed in the latest version of ChameleonFramework.  Will look at reinstalling the pod.

Now "Enumeration value 'kCGColorSpaceModelXYZ' not handled in switch" but this is not affecting the Flash Chat App for now.


### R1Day006 Wednesday, 17 October 2018
R1 Day 6 in full-swing. I totally underestimated the coolness of CSS and expect I have much more to discover check this out https://medium.com/9elements/css-border-radius-can-do-that-d46df1d013ae - thank you @tom_raley! #100DaysOfCode.  And there is this little tool... https://9elements.github.io/fancy-border-radius/#57.31.82.64--395.395

Also a very entertaining, and enlightening, read I discovered courtesy of @yu_angela - Learn Enough Command Line to Be Dangerous by Michael Hartl. @LondonAppBrewer https://www.learnenough.com/command-line-tutorial#aside-technical_sophistication

Working on the Flash Chat project @LondonAppBrewer which uses @Firebase - another great tool... It is important to remember to change your read/write permissions and publish the changes for testing... #100DaysOfCode

Flash Chat project completed @LondonAppBrewer.  Looking forward to lecture 201! #100DaysOfCode


### R1Day005 Tuesday, 16 October 2018

“specificity” - The CSS block with the most specific selector reigns when more than one CSS block selects the same element, and all try to set the same property.  Thank you, @pauldwaite! see https://stackoverflow.com/questions/11529495/importance-of-css-stylesheet-hierarchy

Submitted Survey Form project #freeCodeCamp https://codepen.io/will-1-am-the-Iceman/full/ePZVKE … #100DaysofCode

Finished R1Day5 with a bit of Swift coding an animation and tap gestures with @LondonAppBrewer #100DaysOfCode

Need to review how to construct Swift Closures.


### R1Day004 Monday, 15 October 2018
#100DaysOfCode R1Day4 has begun with answering questions about iOS coding and the Flash Chat app @udemy & @LondonAppBrewer. Now its over to  #freeCodeCamp and tidy my Survey Form project for my portfolio.

While optimising my #html5 for aesthetics, I needed a way to "see" where my elements started and finished.  Intuition led me to set the "border" attribute in css for the element(s) in question - so simple and so illuminating.  When you are finished you just delete the attributes.

A great little article "All about floats" https://css-tricks.com/all-about-floats/ … helped to clarify the use of this wonderful attribute.  #freeCodeCamp  And now my button isn't bounding all over the shop...


### R1Day003 Sunday, 14 October 2018

#100DaysOfCode R1Day3 has begun with a great read of Michael Abelar's book entitled “HTML for Novices by Novices”.  A very easy read if you are familiar with #html5 and even if you are not!  #freeCodeCamp


### R1Day002 Saturday, 13 October 2018
It is Saturday and #100DaysOfCode round 1 day 2 starts (only 98 to go)!  Time to tackle the #freeCodeCamp Survey Form Challenge, have a look at my Chat View Controller with @yu_angela and the #LondonAppBrewery.

TextWrangler is awesome and has been replaced by @bbedit 12.  Thank you @KroonenburgRyan for introducing me to this awesome tool.

Ok, so finally the Survey Form Challenge is nearly complete with the submit button needing a tidy. Considering that I managed to stay out of the dog house by getting some chores done, it was a productive day.


My new repo
### R1Day001 Friday, 12 October 2018
I am officially starting #100DaysOfCode after investing 200 practical hours studying for Amazon Web Services Certified Architect exams with ACloudGuru, currently engaged in iOS Devolpment training with London App Brewery, and have taken on the freeCodeCamp.org challenges.  Then I found out about Mr Kallaway and thought what a great idea!  So, let's make this even more official.
