## Summary
### Mission
Diversity Cyber Council is a 501c3 Non-Profit that serves under-represented demographics in the tech industry by facilitating education, training, and staffing opportunities to establish a sustainable and diverse talent pipeline to the workforce.
### Vision
Our vision is to enhance inclusion and representation in the tech industry through training, mentoring, networking, and visibility programs.
### Goal
Our goal is to establish a sustainable and diverse talent pipeline that extends career equity to underrepresented demographics by providing access to competent training programs that lead to direct employment opportunities. 

## Business Problem and Requirements
### Functional Requirements

| Category | Requirement# | Actors |Description    |
| ------------ | ------------| ------------| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| User Management    | R1         | Candidate,Career Mentor, Non-profit         |The login screen allows registered candidates or non-profits to login to the site to access all of the features that their account gives them access to. If they type in their username and password and click submit the users credentials are validated and if correct they are logged in. |
| User Management        | R2      | Candidate,Non-profit      | If the candidates or non-profits has forgotten their password they click "Forgot Password?" which takes them to a password recovery screen. If the user does not have an account then they click the register button.                                                                        |
| User Management  | R3         | Non-profit   | 	New Non-Profit completes community profile and service capabilities assessment|
| Meeting Management  | R4         | Non-profit, Administrator   | 		Introductory meeting is schedule within 1-2 weeks to discuss non profit service capabilities, responsibilities, & expectations...		|
| Meeting Management  | R5         | System  | 		All mettings are recorded to the system for community	|
| Meeting Management  | R6         | System  | 		Introductory meeting is schedule within 1-2 weeks to discuss candidate needs and develop career roadmap	|
| Meeting Management  | R7         | Candidate  | 		Selected candidates for offerings can set reccurring or one-time events for non-profit services. These events include service name, event title, event location, event dates	|
| User Management  | R8         | Administrator   | 	Administrator accepts application for non-profit |
| User Management  | R9         | Non-profit   | 	Non-profit adds community leader for non-profit |
| User Management  | R10         | Administrator   | 	Administrator selects career mentors from candidates |
| User Management  |R11| Candidate | New Candidate completes a career profile and a career assessment	|
| User Management  | R12        | Non-profit   | New Non-Profit assigns/ cancels assignment to a community leader	|
| User Management  | R13| System           | The Platform must provide a way to allow Non-Profits to publicize offerings to the platform that can provide some level of automatic matching for Candidate requests.  |
| Offering Management  | R14  | System          | The Platform allows offerings to contain rich text, links, and downloadable readable content such as PDFs, but no other downloads.  |
| Offering Management  | R15    | Non-Profit        | Non-profit can create/read/update/delete and list offerings. Each offering must support a certain list of properties (defined by the platform), such as name, organization description, website, unique identifier (assigned by the Administrators) and other identification information.   |
| Offering Management  | R16    | Candidate        | Candidate can list offerings, apply to offerings in progress, and see the status of its application to offering.  |
| Offering Management  | R17    | Non-profit        | Non-profit can list owned offerings, see the candidates who apply to offerings, and select suitable candidate for each owned offering |
| Offering Management  | R18    | Non-profit,Citizen        | Non-profit and Citizen can evaluate selected candidate for assigned offering according to survey questions|
| Offering Management  | R19    | Candidate, Non-profit, Citizen        | All assigned offerings can be listed by all user types according to their rights (Non profit can see all information, candidate can see the ) |
| Offering Management  | R20    | Candidate       | Candidate can see history of its offerings and its success in support services |
| Offering Management  | R21    | System       | System scans the offerings and serves similar offerings and allow non-profits to merge offerings |
| Platform Management  | R22    | Administrator        | Administrator create/read/update/delete/list support service categories |
| Report Service  | R23   | Non-Profit             | The Platform must provide both operational reports (number of candidate matches / period, number of offerings / region, and so on) and analytical reports (projections of future desirable career paths, Offering gaps in a region based on demand, and so on) for use by Administrators     |
| Mail Service  | R24   | System            | The Platform must inform candidates/nont-profits/administrators for each steps of offering (offering creation, opening, candidate applications etc.), user registration, non-profit registration etc.    |
| Forum Service  | R25   | System            | System offers forum for all logged users and these forums can be seen publicly   |
| Survey Service  | R26   | Administrator            | Administrator create/update/delete/list surveys including questions and answers with points and connect these surveys with offering type such as (Resume Writing Services, Interview Prep,Free Business Attire, Apprenticeship Program Registration, etc.) and survey types conducted to non-profits, candidates, and citizens |
| User Management  | R27   | Administrator            | The administrator selects career mentor for candidates   |
| User Management  | R28   | Candidate, Career Mentor            | The career mentor and candidate can interact using messaging services  |
| Career Management  | R29   | Administrator            | Administrator defines career roadmap for candidates  |
| Career Management  | R30   | Administrator            | Administrator defines selected offering types and occurrences and points for each offering type   |
| Career Management  | R31   | System            |  System calculates the career points and career level for candiates every time period that can be configured bu administrator |
| Career Management  | R32   | System            | Administrator defines career roadmap for candidates  |
### Non-functional Requirements

| Requirement#   |Description    |
| ------------ | ----------------------------------------|
|  Non_R1         |Usability: All users should easily use the system |
|  Non_R2         |Accessability: All user types including all disabilities (seeing, hearing etc.) should easily use access system|
|  Non_R3         |Visibility:A technology solution serves the purpose of enhancing visibility |
|  Non_R4         |Colloborative:The system should increase colloboration between non-profits and candidates with AI capabilities |
| Non_R5           | Scalability: System can serve for all nonprofits and citizens so that it can be scalable |