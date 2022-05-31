## Business Problem and Requirements

functional

It can be divided into two as User Req ve Non-profit req (mgoksever) 

| Category | Requirement# | Actors |Description    |
| ------------ | ------------| ------------| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| User Management    | R1         | Candidate,Non-profit         |The login screen allows registered candidates or non-profits to login to the site to access all of the features that their account gives them access to. If they type in their username and password and click submit the users credentials are validated and if correct they are logged in. |
| User Management        | R2      | Candidate,Non-profit      | If the candidates or non-profits has forgotten their password they click "Forgot Password?" which takes them to a password recovery screen. If the user does not have an account then they click the register button.                                                                        |
| User Management  | R3         | Non-profit   | 	New Non-Profit completes community profile and service capabilities assessment|
| Meeting Management  | R3         | Non-profit, Administrator   | 		Introductory meeting is schedule within 1-2 weeks to discuss non profit service capabilities, responsibilities, & expectations...		|
| Meeting Management  | R3         | System  | 		All mettings are recorded to the system for community	|
| Meeting Management  | R3         | System  | 		Introductory meeting is schedule within 1-2 weeks to discuss candidate needs and develop career roadmap	|
| Meeting Management  | R3         | Candidate  | 		Selected candidates for offerings can set reccurring or one-time events for non-profit services. These events include service name, event title, event location, event dates	|
| User Management  | R...         | Career Mentor   | 	TODO... |
| User Management  | R...         | Community Leader   | 	TODO... |
| User Management  | R...         | Administrator   | 	Administrator accepts application for non-profit |
| User Management  |R4| Candidate | New Candidate completes a career profile and a career assessment	|
| User Management  | R..        | Non-profit   | New Non-Profit assigns/ cancels assignment to a community leader	|
| User Management  | R..| System           | The Platform must provide a way to allow Non-Profits to publicize offerings to the platform that can provide some level of automatic matching for Candidate requests.  |
| Offering Management  | R..  | System          | The Platform allows offerings to contain rich text, links, and downloadable readable content such as PDFs, but no other downloads.  |
| Offering Management  | R...    | Non-Profit        | Non-profit can create/read/update/delete and list offerings. Each offering must support a certain list of properties (defined by the platform), such as name, organization description, website, unique identifier (assigned by the Administrators) and other identification information.   |
| Offering Management  | R...    | Candidate        | Candidate can list offerings, apply to offerings in progress, and see the status of its application to offering.  |
| Offering Management  | R...    | Non-profit        | Non-profit can list owned offerings, see the candidates who apply to offerings, and select suitable candidate for each owned offering |
| Offering Management  | R...    | Non-profit        | Non-profit can evaluate selected candidate for assigned offering |
| Offering Management  | R...    | Candidate       | Candidate can see history of its offerings and its success in support services |
| Platform Management  | R...    | Administrator        | Administrator create/read/update/delete/list support service categories |
| Report Service  | R7   | Non-Profit             | The Platform must provide both operational reports (number of candidate matches / period, number of offerings / region, and so on) and analytical reports (projections of future desirable career paths, Offering gaps in a region based on demand, and so on) for use by Administrators     |
| Mail Service  | R7   | System            | The Platform must inform candidates/nont-profits/administrators for each steps of offering (offering creation, opening, candidate applications etc.), user registration, non-profit registration etc.    |
| Forum Service  | R7   | System            | System offers forum for all logged users and these forums can be seen publicly   |


TODO:
Operational Process - Mentor Assignment & Roadmap	

Step 6	New candidate assigned a career mentor

Step 7	Email sent to new candidate introducing career mentor

Step 8	Introductory meeting is schedule within 1-2 weeks to discuss candidate needs and develop career roadmap	

Step 9	Regular cadence touchpoints scheduled between new candidate and career mentor 	

Step 10	Career mentor uploads new candidate career roadmap in platform	

Step 11	Career mentor updates candidate assignment in platform to reflect career roadmap	

Step 9	Regular cadence touchpoints scheduled between new non-profit and community leader	

Step 10 Platform Role based training is assigned to new Non-Profit			

Step 11 New Non-Profit is invited to monthly community meetings		

Non-functional requirements

| Requirement# | Description |
| ------------ | ----------- |
| R1           | Usability   |
| R2           | Scalability |
