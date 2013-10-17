#Peer Helper Tool (Prototype)
##Description
Peer Helper is a tool that allows users to request assistance from their peers on a range of both technical and non technical issues they need addressed. The tool hosts a list of skills, competencies and topics that are held by one or several peers for which the user may choose from. If the user finds a topic that he or she needs help with, he or she would do so by clicking on the field which will provide said person with contact information of someone who may assist them. As the contact information is provided, an email is sent to the contact to notify them that someone has requested help. This notification is sent via email and contains the information of the person requesting help. More soon...

The user may also add his or her own skills to the list that may benefit his or her peers.

##Terms
**User:** 
Any person using the Peer Helper Tool

**Peer:**
Person that works within the same general field as the user

**Mentor:**
Peer whom possesses a competency and may be called upon for assistance.

**Skill**
Knowledge or competency in any general or specific topic

##Features

**Email Automation**

When requesting assistance from a mentor, an email is automatically generated and sent to the mentor so that they are notified that someone needs their help. The email also gives details on whom is requesting assistance and what it is they need help with. The email also provides a link to decline the request and/or be removed from the list of mentors for that topic.


**Point-System**

Every user is assigned points based on how they use the tool. A user is given 10 points for every person they help. Points can be used to skip waiting lists and get help immediately as oppose to being added at the end of the queue.

**Simple Design**

The interface has been designed with simplicity in mind. Every visible element of the tool serves a specific purpose so that users are not overwhelmed with useless information or options. The use of pup-ups and tool-tips within the tool allow for only necessary information to be visible at any given time.

**Ridiculously Easy to Use**

The main focus of this tool is to make the user-experience as time efficient and effortless as possible. This is achieved by reducing the number of actions the user needs to do to get the information they need. By only asking the user to provide their username when making a request, the user can get assistance in virtually no time. The tool also catagorizes each skill and provides a search bar as well as search filters which reduces the number of clicks the user needs to do. Having the email automatically sent with all the required information to all relevant parties also reduces the work done by the user. Adding a skill is just as easy as requesting help. 

**Flow Efficient**

Through a combination of simple yet effective design, rediculously easy-to-use features and a simple premise, the tool is very flow efficient. And by having everything contained within one page means the tool never needs to load new information.

##Features to Implement

###Front End
* Categorize skills/Competencies
* Add Search feature
* Add customizable Search filters
* Add sub-categories
* Add "request user name" pop-up when clicking on a skill
* Convert dynamic css to javascript
* Dynamically add/remove skills from list
* Add pop-up that allows a user to add his/her skills
* Include Title, Tags, Username, Desc. in skill pop-up
* Add "priority request" button/feature
* Create dynamic list (grow/shrink according to number of entries)

###Behind The Scenes
* Build Database with contact information (User Name | Contact Name | Contact Email)
* Build automated email system
* Generate emails to unsubscribe users from being mentors
* Create 2-day counter
* Link Mentors (Users) to their skills
* Assign points to users
* Handle customer reports
* Handle Mentor lists

###General
* Over-Simplify Everything
* Develop point-system