## FYP Diary

Student: Niall Crowe

Supervisor: Diarmuid

### Fri, Sept 23rd

+ FYP supervisor allocation published on Moodle.

### Mon, Oct 3rd (Scheduled Meeting)

+ Niall briefed me on the project idea, which seemed to have much potential. The core technologies used were novel (Podman, Go), and the problem domain had a lot of scope, if required.
+ Niall spent his 3rd-year work placement at RedHat, where he got some experience with Podman, in particular, to host a web server - a trigger for the project idea.
+ While a methodology was not explicitly discussed, an Agile approach that would deliver a prototype by semester 1 seemed ideal for this project.
+ Niall had already begun working on the client side, although it shouldn't pose many problems as there is a vast collection of open-source libraries. The only potential stumbling block might be the availability of an embedded eBook reader. 
+ Podman is central to the project's success, so some time researching it is necessary. As a first step, Niall should investigate its configuration options, particularly those relating to local hard disk access.

###  Mon. Oct. 10th (Meeting)
+ Niall uses his PC for development work on the project. He has successfully set up an environment to run Podman. While he has yet to get Podman to access the local filesystem, the how-to has been established from his background reading - it will be necessary for the end-of-term prototype. 
+ We had a general discussion on the application, covering issues like eBook formats and metadata, persistence requirements (Niall's preference is MySQL as his Distributed Systems module uses it), and authentication.
+ The ultimate objective would be to run the server-side (Podman) in the cloud. Niall needs to investigate this, focusing on AWS as the preferred provider.

###  Mon. Oct. 17th (Meeting)
+ We completed the Research Ethics Checklist on Moodle.
+ Niall reported that he would be able to satisfy the cloud deployment requirement by using EC2 to host Podman and AWS RDS for persistence (user accounts, etc.)

###  Mon. Oct. 24th (Meeting)
+ As the mid-term break approaches, work on the prototype needs to begin in earnest. The objective would be to have a local skeleton instance of Podman running, where it accesses an eBook file(s) on a hard-coded directory path. A message confirming this could be sent to the console or displayed by a simple React app hosted locally. A bonus would be to output some metadata from the books. 
###  Mon. Nov. 7th (Meeting)
+ Niall needed more time to develop the prototype due to deadlines for other modules' assignments. This is a severe setback, as the prototype is the primary deliverable for semester 1. 
+ The focus for next week is to start working on the prototype.
+ Niall discovered a library for reading eBook metadata, but it's Java-based. If a Go-to-Java bridge exists, this could be useful,