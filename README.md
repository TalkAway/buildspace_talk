# buildspace_talk
This is the space for our first MVP in web3

Certified lessons - tour guide + language lesson.



**OVERVIEW**

Talk Away is a social impact language learning startup, we help people learn languages in everday experience.
The class takes place on a walk with a language tutor.
As a teaching platform on the web3, we are building a dapp to further expand access to language learning. 

Our mission is to provide a differentiated teaching approach 
to promote language knowledge for people with limited financial resources and migratory vulnerability. 
We also aim to connect people from all over the world, fostering greater awareness of global cultural diversity.


# functionsdapp

# Profiles

**Quantity:** 4

**Types**

**Casual Student**: Earns level 0 certificate only | takes between 1-4 classes | Traveler | Digital Nomad |  

**Regular Student**: Earns up to 6 certificates | takes 4 or more classes | City Resident

**Tour Guide Instructor: Certified Tour Guide in Rio de Janeiro and associated to LIGUIA, works with groups of up to 4 students 
| need to do a formation of Talk Away - recorded classes.

**Casual Tutor**: Native |Does not need to be a teacher 

**Regular Tutor** This tutor can give the proficiency level certification | need to do a formation of Talk Away - recorded classes.

# Overview of the Structure

**Topics**

- Casual lessons 

- Certificated Lessons

- Talk Walk Tour 

- Be a Student 

- Be a Tutor 

**Registration**

**tutor tour guide**
(it's needed to speak a second language at minimum intermediate level)

- only people who have participated in the training will receive the registration link
- identity document 
- presentation video  
- complete name  
- location 
- languages you speak
- price per class | 4 classes | 10 classes


**Regular Tutor-- native speaker/ teacher/ certificated speaker** 

- In proficiency certification topic

- (it's needed to speak a second language at minimum intermediate level)

- make the training of talk away approach (it will generate a certification)

- video presentation
- full name 
- location 
- language proficiency
- image (can be face photo or avatar)
- price per class | 4 classes | 10 classes



**Casual Student**

- proficiency level of the language you will learn
- languages you speak 
- identity document 
- full name 
- picture (optional) 
- link to join the telegram or discord community

**Regular Student**

- proficiency level of the language you will learn
- languages you speak 
- identity document 
- full name 
- picture (optional) 
- link to join the telegram or discord community



**2 showcases** Talk Walk Tour | Casula Walking Lessons | Certificated lessons

**Community at discord** 
- Private tutors forum at discord 
- General chat room 
- Introduce yourself 
- Events


# Internal Structure

**GPS para acompanhar a caminhada od tutor e estudante**


Check in and check out of each experience

# Student Journey

**For all students**


After checking in, the student sees the Journey logbook:

Each lesson, the student writes down the main topics talked about on the walk; the tutor responds in a comment and checks in the student's writing. 

After the check, the student gets an NFT record of the walkthrough, for regular students,
that is included in the history of the change of level certificate (onchain) 

**Regular students**

Below the note space there will be 4 topics with the skills needed for level change, 

The tutor will check each of them according to the student's process. 

When they are all filled in, the student receives the SBT of proficiency level (onchain), but each level certification
only can be released with at minimum 8 walking lessons.

The students can schedule a free online meeting for proficiency evaluation and start in a specific level.

Each writing on the hikes will accumulate, building up a big notebook and go into a specific folder (offchain)

**For all students**

Will have a phrases propose while the walking, the student will choose if he is on street or in a coffee, for exemple,
and each 10 minutoes the app will suggest a phrase like this: "stop and look the heaven" or "touch the table and indentificate your material" 
- for each level we will generate a kind of phrase propose. 

# Payment

**Talk Walk Tour
- pay per use
- the student pays before accessing the tutor's contact, only after the tutor and student check out the commissions are distributed

**walk tour product**  

different prices for:

- 4 hours
- 6 hours 
- 8 hours 
- by night - 3 hours 
- 1
- 2
- 3-4 pax

**Walking Lessons without tour**

- per hour 
- 4 lessons 
- 10 lessons 
- 1
- 2
- 3-4 pax

*All lessons have discount copum possibilities 


**TECHNICAL PART AND PROJECT DETAILS**


**The smart contract will handle the following**

Create new user It will create a new user, either a free student or a certificate student.
Create new tutor It will create a tutor with information about the courses, services he will provide, and the price for his lesson.
Create new resources
Login/logout from the wallet and chack thebalance.
Pay per lesson: it will get the predefined price from the student and save it to the website contract address
Payment for multiple classes will be an offer to get some discounts.
Certificate generation

**Transfer payment to tutor**

it will send the money from the website address to the tutor's address after the user call the check class successfully.
Check class for user: after each class, the user -student- will call this function so the class passes successfully 
and the money can be transferred to the tutor.

**Check level** 

this function will be called by the tutor only and return the level of the user To be able to handle the 
following information we need to create a struct for the user, tutor, certification
Part of the classes payment will go to social projects that will be voted on by community: voting system and distribution of the fund.

**Small enums**

User type: student-tutor Level enum: determine the level the student has Student type enum: free - with certificate

**Student info will be saved on the contract**

User id
User name
User type
Public key
Level
Certificate
Has payed
Has checked

**Tutor info will be saved on the contract**

User id
User name
Rating
Course info hash will contain a hash to the saved class info and material if existing. Course material and info will be saved on IPFS
Certification will be SBTs and will be minted at the end of each level.

Technical parts: The stack will be React.js, node.js, and mongoose.

**Dapp Solid overview**

The home page contains classes and tutor info.
Forms for creating a user/tutor.
Log in with the user’s wallet.
The user profile contains info about the user. Attended class, level, certifications
The tutor profile contains info about the tutor, classes, rating
Terms policy
Contact us


