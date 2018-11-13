# Final Project Proposal Template

## Datavyu

Datavyu is a desktop application that assists in visualizing and coding behavioral observations from video data sources. The project is an offshoot of MacShapa, a mac application, which has decades of development behind it. Both MacShapa and Datavyu were evangelized and supported by Dr. Karen Adolph of New York University. Due to the nature of the client base, the project though invaluable to the researchers work, has been starved as far as resoruces are concerned. I want to help the community grow by looking at the website / forums / integration with github of the project, so it is easy to navigate for beginners

## Team Members

Ahmad Arshad : https://github.com/muji786

## Define the problem.

What is the current state of things? 

Datavyu has only one full time developer working on the project. It needs more human and technical resources for solicitng feedback, as well as new feature development / bug tackling. Main support forum is at: http://datavyu.org/support. This is an obsolete ostickets installation that is very confusing and difficult for users to create accounts on and use.

What issue do you wish to solve and why? 

I want to facilitiate bug reporting, feature request and general support easier for users. This will help users feel more vested and heard. I want better integration with gitflow that may pull other contributors who feel strongly about research and open source.

What need / gap does this project fill? Who is the audience?_

Current and upcoming Researchers in developmental sciences who work with video

## Address Greater Landscape

_Please address how the open source project you are creating or contributing to fits into a greater field or tech landscape. Who has done similar work before? How are you building off this, and how? What sets your project apart from your colleagues?_

Datavyu is unique that it is a high precision video annotation tool which is open source. There are commercial tools out there, that costs 10s of thousands of dollars for single licenses. Mangold / Noldus / CLAN / are the competitiors. ELAN is another tool that is open source, however it is more geared towards language research (audio) vs video. In its absence, researchers are using excel or paper and pen to annotate video that causes errors that affects research outcomes.

## Deliverables

a) Implement Github issues as a place for users to submit bugs.
b) Implement a new forum software https://discourse.org that will be used for discussions.

## Implementation

_Describe the technical details about your implementation and development process._

I will be using a community version of discource and installing it on a Linode or AWS ec2 instance. I will archive the old forum for historical reasons and migrate the user database to the new software. An email will be sent out to them to notify changes. 

I will also be encouraging them to utilize github issues to submit new bug reports. Some hand holding may be required here.

## Timeline

This project will be completed over 4 weeks (Nov 13 - Dec 11). Describe a timeline in detail below.

### Week 1

- Discover the server infrastructure of Datavyu.org and forum software.
- Discuss Github issues with the mentor and the format of Issues etc

### Week 2

- Work on migrating existing userbase to discource. This would require SQL access
- Installing a barebone discource installation

### Week 3

- Import new users / tags / categories
- Attempt import of older forums

### Week 4

- Marketing emails as well as testing


## Documentation

_Describe your plan for documentation. Will you keep a blog? Make videos? Some project management tool? Track everything on GitHub as issues?_

I will use my blog for documentation at https://dev1.ed-projects.nyu.edu/geotools)[https://dev1.ed-projects.nyu.edu/geotools

## Longer-Term Goals

_What do you see as the longer term plan for this project and your project involvement?_

I will continue to work with the Datavyu mentor and maybe directly help with fixing some older framework AWT/Swing bugs

## Accessibility

_What challenges are there related to your project in terms of Web Content Accessibility Requirements: [see the Accessibility assignment as a reference](https://github.com/Open-Source-Studio-at-ITP/Syllabus/blob/source/accessibility-assignment.md#instructions)._

Not applicable.

## Mentoring

_List some possible mentors for this project. Describe what kinds of help you need (technical, conceptual, outreach, etc.) For more, read [the mentor guidelines](https://github.com/Open-Source-Studio-at-ITP/Final-Projects/blob/source/mentor-guidelines.md)_

Dr. Reda Nezzar https://github.com/TheoWolf who is the lead and only developer of Datavyu will be my mentor who will bring me upto speed with the server infrastructure as well as discuss how to implement these two deliverables in a way that best serves the community.

## More about you

_What are your interests and experience? Have you contributed to other open source projects? What barriers or concerns have kept you from contributing to free and open source software? If you have an online portfolio, github account, or other relevant documentation of your work, please include links. If the project is a collaboration, a section should be included for each collaborator._

I have always been very passionate about open source projects as well as non for profit mission driven organizations. My barrier from contributing have strictly been time related. This will give me a good chance to work as a collaborater with 

## References

This proposal template was created with material and advice from:

- [How to write a proposal for GSoC](http://teom.org/blog/kde/how-to-write-a-kick-ass-proposal-for-google-summer-of-code/)
- [Processing Foundation GSoC application template](https://docs.google.com/document/d/1UFcWh2IWqhICh4YIFNwtKUaWWXifaBB67rjPxbYzjbE/edit)
- [Getting into Summer of Code programs](http://exploreshaifali.github.io/2015/06/08/getting-into-summer-of-code-programs/)
