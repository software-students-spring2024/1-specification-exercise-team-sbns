# Specification Phase Exercise

A little exercise to get started with the specification phase of the software development lifecycle. See the [instructions](instructions.md) for more detail.

## Team members


Stanley Moukhametzianov (SM9231) [Github Profile](https://github.com/Stanley-Moukhametzianov)
<br>
Benson Li (BL2995) [Github Profile](https://github.com/bensonnli)
<br>
Nicholas Meng (ndm9914) [Github Profile](https://github.com/Nmeng01)
<br>
Sangeyl Lee (SL6733) [Github Profile](https://github.com/S2ang) 

## Stakeholders
___


### Names

 - **Andrew Xu (Third Year Student at NYU)**
	- I focused my questions around his needs for using Albert as well as some of the problems that he currently has. This would allow us to address those issues when making the mobile app version. He would also make a good representative sample as he has used Albert for many years. This includes making his schedule, checking his grades, and checking his degree progress. As such, this would be an ideal user for our app. 

 - **Rita Hsu (Third Year Student at NYU)**
   - I interviewed her based around her purposes of using Albert. She is representative of an end-user of Albert as she has been consistently using it for three years and would be able to help identify common goals/needs for NYU students as well as points of frustration. She is also familiar with it, having used it for 3 years at this point, making her an ideal person to help identify user requirements. 
	
 - **Basia Fellner-Dublin (Fourth Year Student at NYU)**
   - I kept my questions open-ended at the beginning and once we had identified a big key issue, we went into a bit more detail not only about this specific problem, but also about how she thinks we could address it. She is a good representative as a fourth year who has a lot of experience using Albert.

- **David Choi (Fourth Year Student at NYU)**
  - During the interview, David highlighted a critical gap in the current Albert system: the lack of immediate feedback from academic advisors. This issue becomes particularly pressing when urgent academic guidance is needed, and advisors are not readily accessible. David's insights are valuable for understanding the specific challenges that students face when seeking academic advice, making him a key stakeholder in the development of solutions such as an AI chatbot designed to address these gaps.

### Goals Or Needs
 - **Finding which classes are offered each semester**
   - Some classes are not offered every semester and sometimes they are with different professors. Albert allows students to see the current classes offered for each semester and the professors who are teaching them.  
 - **Checking if classes are on waitlist and how many people are on the waitlist** 
   - Sometimes classes get canceled or filled up before students can sign up. Albert tells students which classes are available as well as how many students are waitlisted and which position the student is on the waitlist.  
 - **Creating a notifications tab so that users can receive updates on specific classes**
   - Rather than making users search for a class over and over when they want to receive updates, users should be able to 'follow' classes of their choice and receive status updates on major changes.
 - **Looking at course grades**
   - Students should be able to access their course midterm/final grades, as well as past grades. They should also be able to request a transcript. 
 - **Creating a dedicated part of the app for course search**
   - Separate, smaller containers overlayed across the home page causes too many issues. There should be a button that takes the user to a dedicated full-screen course search.
 - **Organizing course search more intuitively and implementing a simple 'back' button for easier navigation**
   - The organization of the course search should be redone so that it is more user-friendly and consistent across all pages. A 'back' button should replace some of Albert's current navigation tools for increased simplicity and ease of navigation.
 - **Immediate feedback from academic advisors**
    - Students often require prompt responses to their academic queries, especially when making decisions that affect their course selections, degree progress, and overall academic planning. An AI chatbot could provide an immediate, 24/7 support system for answering common questions, reducing the waiting time for advisor responses.
 
### Problems or Frustrations
 - **The public course search UI is very lengthy and difficult to use on mobile and on desktop.**
   - This is a problem that I faced as well. The public course search for mobile has a massive UI issue with that you are required to scroll for a large amount of time before you can find the classes that you want to sign up for. 
   - For example, higher level computer science classes are all the way on the bottom, so you are forced to scroll through all the lower level classes before you can find the section of classes that you need. 
   - A possible fix for this problem would be to collapse all the classes. So rather than seeing all the available classes for CSCI-UA 2, you would just see a button labeled CSCI-UA 2. Then on click you would see the available classes. This would drastically reduce the amount of scrolling needed and allow students to find classes faster.
 - **Waitlists don’t give students an accurate representation of the chance that the student can get into the class.**
   - For example, a waitlist of 30 on a 80 person class is likely, but a waitlist of 30 on a 30 person class is not very likely. However, both seem to have the same chance to the user.
   - We can fix this by having waitlists, or classes in general, show class size. This will give students a more accurate idea of how likely the waitlist is to move around and a better idea of if they will be able to enter the class.    
 - **Students don't get notified when classes open or close at random times.**
   - This is a problem many students face when trying to enroll in important classes for their degree requirements. Students have to often check by themselves whether classes are open or closed. Sometimes, by the time check, classes that have opened up in the meantime may have already closed.
   - A possible fix for this problem would be to give users the capability to enable notifications on certain classes or even the whole department course catalog. The app would then send a notification to the mobile device if a specific class opens up or closes. There could also be a separate notifications page within the app based on what the user has chosen to be notified about. This would eliminate the need for students to constantly check Albert course search. 
 - **Opening a separate container for the course search and the general navigation system that it uses causes confusion and leads to odd displays.**
   - Using course search and other Albert tools with the current pop-up container is very annoying to use, especially on mobile devices. Scrolling does not behave consistently and often times the container becomes distorted and impossible to use without closing and reopening the container.
   - Oftentimes, finding classes is incredibly tedious because of how complicated the organization of the course search UI is. The UI is unintuitive and the navigation buttons often do not function the way users might think they function.
 - **Delayed responses when advisors are unavailable**
    - The main issue David pointed out is the delay in getting responses from advisors, especially outside office hours or during peak times. This delay can hinder students' ability to make timely decisions about their academics.
    - To address the need for immediate feedback, an AI chatbot could be integrated into the Albert system. This chatbot would be designed to answer a wide range of academic queries, from course selection advice to degree requirements and administrative procedures. By providing real-time responses, the chatbot would alleviate the pressure on academic advisors and enhance the student experience by offering accessible, immediate support.
___

## Product Vision Statement

**Optimizing NYU Albert for enhanced mobile usability and a user-friendly interface.**

## User Requirements

##### User Stories

- As an NYU student, I want to find available classes so that I can make my schedule for the next semester. 

- As an NYU student, I want to be able to see class sizes so that I can better know my chances of getting off the waitlist. 

- As an NYU student, I want to have specific classes hidden so that I can easily find my class without having a very long scroll distance. 

- As an NYU student, I would like a notification when specific classes open or close so that I don't have to manually check each time to see. 

- As an NYU student, I would like to keep track of my grades for each class and have access to my transcript, so that I know if I am doing well and can see my overall grades. 

- As an NYU student, I would want a dedicated course search feature so that I don't have difficulty dealing with overlapping screens and it is easy to use on mobile. 

- As an NYU student, I would want an easier-to-navigate course search with a back button so that I don't have to go from the start again to go back, and can have an easier time finding my classes. 

- As an NYU student, I would want to see the classes that I have enrolled in, and be able to add, drop, or edit my schedule. 

- As an NYU student, I would want to know if there are any holds preventing me from scheduling my classes as well as see the date of when I can enroll for classes, so that I can fix any of the holds and enroll in classes as soon as possible. 

- As a NYU student, I would want an AI chatbot to quickly ask questions regarding my schedule, so that I can get help quickly without having to wait for my advisor. 

- As an NYU student, I would like to have a current list of my midterm and final exam dates, so that I can get an organized area to see all of my important exams and make sure I don't miss them.  
- As an NYU student, I would want to see the requirements that I need for my major and core, so that I know what requirements I have completed and what classes I need to take to be able to graduate. 

- As an NYU Professor, I would like to be able to update my midterm and final exam dates so that students do not see the wrong information on Albert. 

- As an NYU Professor, I want to list my available classes so that students can know the classes are available and sign up for them. 

- As an NYU Professor, I want to be able to give students their midterm and final course grades, so that students can know how they are doing in the class, and know their end-of-semester grades. 

- As an NYU advisor, I would like an AI chatbot, so that I can focus my time more efficiently, and if the AI doesn't help the student, I can get an idea of what they wanted from the chat logs.  



## Activity Diagrams
As an NYU student, I want to find available classes so that I can make my schedule for the next semester. 

![UML_meng_resized](https://github.com/Nmeng01/1-specification-exercise-team-sbns/assets/123509773/d31bf765-7ea2-4bed-80cb-bc0fd19eae67)


![Activity Diagram2](https://github.com/S2ang/1-specification-exercise-team-sbns/blob/main/activity.drawio.png?raw=true)


## Clickable Prototype

Wireframes: [Link](https://www.figma.com/file/nSkqnmzc38OTEwQxHjqKMK/team-sbns-project-1-prototype?type=design&node-id=0%3A1&mode=design&t=XGYzKCDdDUq228r2-1)
<br>
Prototype: [Link](https://www.figma.com/proto/nSkqnmzc38OTEwQxHjqKMK/team-sbns-project-1-prototype?type=design&node-id=1-2&t=aIGpHNIbKMvAGwef-1&scaling=scale-down&page-id=0%3A1&starting-point-node-id=1%3A2)

