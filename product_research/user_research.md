# User Research Notes

## Summary of Results
We tested with Julian as well as Mia who is a daycare staff working with infants at Hydrokids.

Both UX testers liked the minimalistic aspect of our product. The daycare staff really liked how it’ll help automatically track a child’s events such as diaper change, eating, and sleeping since she currently tracks it on her phone. She believes it’ll help reduce her phone time on the phone and let her spend more time with the children. 

Below is a summary and action items we’ll be taking for each page of the prototype. 

*Login Page*

No issues here. Instructor and daycare staff logged in fine. 

*Students Page*

No issues here. Both people found the page using the bottom bar and found Samatha King without issues. 

*Individual Student Page*

Some issues with differentiating between student incidents and general incidents. Thought the connection was confusing. Daycare staff wanted “diaper change” event on there as well since it’s a critical event they deal with. 

**Action**: 
- Will attach the students as well under the general incidents and will add “diaper change” event. 
- Should allow daycare staff to export the logs as well to give to parents. 

*General Incidents Page*

Confusion on what the checkmark vs cross meant, thought it meant that the incident wasn’t resolved yet. 

**Action**: Consider using different symbols or just using the words instead. There is a legend on the top of the screen, but not noticeable enough since the user didn’t see it. 

*General Incident Video Page*

Instructor suggested the students involved should be attached to the video as well, this caused a bit of confusion as to how student incidents and general incidents connected. 

**Action**: Will also add the students involved under the video. 

*Active Incident Page*

Daycare staff didn’t realize active incidents was on the home page instead of Incidents page. And that the word Ignore seemed wrong. Instructor thought there was some step missing after clicking on ‘acknowledge’ or ‘ignore’. Also wasn’t sure how to report an incident if it was marked wrong. 

**Action**: 
- Change so that video should be opened before the user can select ‘Acknowledge’ or ‘Ignore’
- Change the word ‘Ignore’ to something else, possibly ‘Dismiss’
- No recurring alarm - might be distracting and annoying since the daycare staff will be first working on resolving the issue rather than clicking a button on the app. But bypassing ‘do not disturbs’ is fine. 
- Need a way to report incidents that the AI got wrong. 




## Appendix 

### Interview Notes

**Please log back in as Irvan Danmateo, for the prototype, we’ve created an account for you.**  
Julian:  Successfully logged in.  
Mia: Successfully logged in.  
  
**Please find details of one of your students, Samantha King**  
Julian: Successfully found the student by navigating to the student page with the bottom/navigation bar.  
Mia: Successfully landed on the student page and found Samantha with the bottom/navigation bar.  
  
**Please check the daily logs for Samantha**  
Julian: Successfully found the daily logs by clicking on Samantha in the student list.  
  - Comments: The differences and relationships between the incident tab under student page and the incident page are not unclear.  
  - Suggestions: Should add a link to the incident page on the incident tab under student page and vise versa.  
  
Mia: Successfully found the daily logs by clicking on Samantha in the student list.  
  - Comments: Title and the time columns in the logs are helpful.  
  - Suggestions: Add diaper change as an event logged in the daily logs.  
  
**Now please check the list of incidents that have been resolved**  
Julian: Successfully navigated to the incident page to find the list of incidents that have been resolved.  
  - Comments: The differences and relationships between the incident tab under student page and the incident page are not unclear.  
  - Suggestions: Should add a link to the incident page on the incident tab under student page and vise versa.  

Mia: Clicked on Samantha’s past incidents instead of navigating to the incident page. Successfully navigated to the incident page after clarifying that the task was asking for all/general incidents.  
  
**Please open the video of the very latest incident that was resolved**  
Julian: Successfully found the most recent resolved incident and clicked on the video.  
Mia: Clicked on the wrong incident as the participant thought that the 'x' icon meant that the incident wasn’t resolved so clicked on another incident.  

**Lastly, please find all incidents that haven’t been resolved and resolve the oldest one appropriately, the AI marked it wrong**  
Julian: Successfully navigated to the home page and clicked on the oldest open incident.  
  - Comments: An user should be able to view the video and label before deciding to either acknowledge or ignore button. An user should be able to report or edit misclassified incidents.  
  - Suggestions: Should add a popup window for the user to view the details of the incident before acknowledge or ignore it. Should add another option for an user to report or edit misclassified incidents.  

Mia: Clicked on the video before clicking the ‘acknowledge’ button. Clicked on the ‘acknowledge’ button instead of the ‘ignore’ button.
  - Comments:  The ignore button can be confusing and misleading. If an user recives a notification, one would be working on solving the issue first instead of logging into the app and clicking on acknowledge.  
  - Suggestions: The alarm should not be recurring, and one single notification would be enough.  

### Table for Observer Notes

| Observations                                                | Instructor                                                                                                                                   | P1 - Hydrokids infant room staff                                                                                                                                                                                                                                                                                      | Notes on possible changes                                                                                                         |
|-------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| Understood the difference between ack and ignore            | Understood the difference but has used similar technology before - but felt like there should be more after than just clicking ack or ignore | Suggested having dismiss over Ignore since ignore seems too aggressive Was not aware that ignore could be because the AI marked it wrong                                                                                                                                                                              | Consider changing ‘Ignore’ to ‘Dismiss’  Consider forcing to open video first then resolving the incident                         |
| Understood the icons in the bottom bar                      | Navigated the bottom bar well, navigated to the student page and incident page with the bar.                                                 | Found samantha without any issues. Navigated through the students, home, and incidents tab using the bottom bar                                                                                                                                                                                                       |                                                                                                                                   |
| Understood the difference between active and past incidents | Understood where to find the active events                                                                                                   | Was confused about past vs current incidents - not aware they were on different pages.  Clicked on x in the past incident log thinking it was an “unresolved incident”                                                                                                                                                | Consider making ignored incident or acknowledged incident more obvious.                                                           |
| Understood how to close active incident                     | Understood how to close it but felt that a step is missing - also was not sure what to do if something was misclassified                     | Wanted to play the incident before clicking acknowledge or resolve Thought ignore means “did nothing or already saw it happen” Acknowledge can just get it to go away because most daycares have a paper they need to fill out extensively anyway Thought recurring notifications would be more annoying than helpful | Not have recurring notifications for incidents that haven’t been resolved Force to open the video before resolving the incident.  |
| Confused about filtering options                            |                                                                                                                                              | Would like to filter by person                                                                                                                                                                                                                                                                                        | Will consider adding filtering options                                                                                            |
| Feel inconsistent design when moving to next page           | Liked the design and the minimalistic aspect of it                                                                                           | Liked how minimalistic it was.                                                                                                                                                                                                                                                                                        |                                                                                                                                   |
| Feel overwhelmed by the amount of information in a page.    | Was not sure how incidents under a student and incidents page were connected - was confused why there were two pages                         | “quite straightforward” Would like each incident to also include which students were involved Want to have diaper change in daily logs, likes idea of having pictures inside                                                                                                                                          |                                                                                                                                   |
| Feel challenging when trying to go to a specific page       | No challenges on the pages that were presented.                                                                                              | Slight challenge finding active incident, thought it was in the past incidents page                                                                                                                                                                                                                                   | Might need more clarity in navigating between active incidents and past incidents or some sort of tutorial.                       |

### Post Interview Questions

- What did you like about the app? In terms of features and/or styles

Julian: Simple looks stylish, looks on a good path

Mia: Main thing is doing the recording for automatically, gives more time to actually watch over children.
- Which task(s) did you find hard to complete?

Julian: Some of the information is not connected properly, incident to students
View it and add students that weren’t added properly, pop up window

Mia: Maybe have most-recent at the bottom bc existing daycare apps have that
- On a scale of 0 to 10, how intuitive did you find the app?

Julian: 8 

Mia: 8 - docked marks for confusion with ignore and acknowledge as well as active and past incidents. 
- How would you describe the experience using this app? Does it help with the struggles described in the scenario?

Julian: Pretty good experience overall, but I don’t know how useful it will be if you can’t do anything with these incidents. 

Mia: Good. Takes pressure off, especially recording children all day and not having time to actually interact with them
- How likely are you going to use this app if you were a daycare worker? And why?

Julian: Would consider trialling

Mia: Is excited for it, really liked how it captures everything that they do now but just more automatically. 
