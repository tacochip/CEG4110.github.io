# Weekly Team Report

## Week 1:
### Progress Report: 
On the first week, a group workspace was created through Slack containing channels that were advised to be included by the instructor. Each team member was added and disclosed their availability throughout the week. Our group concluded that the best days to meet would be Tuesday and Thursday during classtime, with additional time to be taken at 5 p.m. on Tuesdays if needed.

### Number of Meetings: 0

### Group Work-Hours: 0

## Week 2:
### Progress Report:
Our team began our project by creating our team website through Github Pages (this site) and our private repository also through Github. Teamates got to know one another, discussed other possible meeting times, and discussed the overall flow we would like to follow for the remainder of the semester. The base necessary sections were added to the website and all team members were added as collaborators on both the team website and the private repo. Once intialized, both the link to our website and an invite to the private repo were submitted to the instructor via direct message on Slack. 

### Number of Meetings: 1

### Group Work-Hours: 2

## Week 3:
### Progress Report:
Our team acknowledged the due dates for the requirements spreadsheet and requirements presenation and began deciding what our top five requirements would be for this project. Once decided, we began by listing our top five requirements on the spreadsheet template and at least two sub-requirements for each. After filling in the sections on the spreadsheet that could be addressed with our current progress, we began creating our top five requirements presenation using the provided template.

### Number of Meetings: 2

### Group Work-Hours: 3

## Week 4:
### Progress Report:
This week, our work mainly consisted of polishing our requirements documents from our most recent meetings. This included listing every possible test case we could come up with on our presentation, adding in testers and developers on the spreadsheet, and figuring out our test descriptions for each requirement and sub-requirement. After completing both documents to our fullest ability with the current state of our project, both documents were submitted via direct message on Slack to the instructor. 

### Number of Meetings: 2

### Group Work-Hours: 3

## Week 5:
### Progress Report:
On the fifth week of work, our team began figuring out how we were going to approach the next objective; Creating a fully functional front end by October 16th. The software that we had previously chosen to use already included a login system, user management, and a feature to create pages and manage who has access to them. The work conducted mainly consisted of research and summing up what pages needed to be included and the UI for each page. 

### Number of Meetings: 1

### Group Work-Hours: 2

## Week 6:
### Progress Report:
After referring to the conclusions from the previous week, our group spent this meeting creating a full front-end. This included a schedule query page, faculty approve/deny page, and a page where the student can add/drop classes per the semester of their choice. The rest of our time met was dedicated to figuring out how we will transfer class data, student input, and faculty-student cases between pages through the back-end. 

### Number of Meetings: 1

### Group Work-Hours: 2

## Week 7:
### Progress Report:
With the upcoming mid-term demonstration day, our group polished our front-end and made sure it met all requirements concerning the front-end of the design project. This included establishing a password-lockout function on the login page, editing previous pages to be webforms to allow for easier selection and UI, and providing quick-links on user pages to grant easy access to required webforms. 
 
### Number of Meetings: 2

### Group Work-Hours: 3

## Week 8:
### Progress Report: This week contained the "mid-term demo day". Our group had already established a solid front-end for our website and decided on Tuesday that we were fully ready to present the following Thursday. On Thursday, our project website was presented to Sean Banerjee and received light constructive criticism that offered new insight to how we will construct our back-end information flow. No further work was completed after presenting the project. 
 
### Number of Meetings: 0

### Group Work-Hours: 0

## Week 9:
### Progress Report: The week following the mid-term, our group began constructing our back-end and information transfer. This included a constructing a notification system, working on webform logic, and installing appropriate plugins on Drupal that perform certain functions needed for course logic. Seeing as this was the first week fully concentrating on the back-end, our group dedicated more time to fully understand how we will go about constructing the rest of our website rather than implementing functions right away. 

### Number of Meetings: 2

### Group Work-Hours: 3

## Week 10:
### Progress Report:


### Number of Meetings: 

### Group Work-Hours: 



# Team Member Information

## Sean Mcmeans
- **Year:** Junior

## Cyrus Straley
- **Year:** Senior

## Charles Ojanama
- **Year:** Senior

---

# Project Overview
_This section will provide a detailed description of the project, its goals, and functionality._

---

# Software Requirement Specification (SRS)

---

# Software Test Plan
# Test Cases

| ID   | Test Case                                                                 |
|------|---------------------------------------------------------------------------|
| 1    | Conduct multiple logins for different user types to ensure the system identifies each specific user type individually. |
| 1.1  | Perform multiple logins of each user type using one or more uppercase characters. |
| 1.2  | Test each user type's password entry with and without a single uppercase character and special character. |
| 2    | Schedule should be generated with classes appropriate for the majors/minors of the student. |
| 2.1  | Test that student has all prerequisites for scheduled classes. |
| 2.2  | Test that generated schedule matches the student’s credit hours. |
| 3    | Test that an allowed/unallowed co-op works/fails. |
| 3.1  | Test an extended graduation plan feasibility in the case of a co-op extension. |
| 3.2  | Test that the system notifies the user if their current class schedule is too few credit hours to fit a co-op without altering their graduation timeline. |
| 4    | Test that any changes made by a student user notify faculty. |
| 4.1  | Test that any co-op requests or schedule changes can't be officially made without faculty approval. |
| 4.2  | Test that faculty class recommendations take precedent over system recommendations. |
| 5    | Test that classes outside of WSU catalog aren't available to students. |
| 5.1  | Test that only admin user types have the ability to modify user accounts. |
| 5.2  | Test that users cannot take classes that do not fall within their major requirements. |
