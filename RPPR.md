# Budget
Don't edit this - the RPPR generator populates this section

# Research Design
This project aims to create a variety of dashboard views and data feeds to help both technical and non-technical team members, community members, and NCATS readily see what is happening in CD2H and navigate to the information of most interest or salient use to them. The design is intended to be nimble with regard to technology and project evolution. As projects within CD2H come and go, and involve an increasing number of community participants, we expect the dashboarding needs to also evolve. We want to be able to highlight archived projects that have moved on to dissemination phases, de-emphasize but still make available projects that have been put on hold, and promote the addition and enhancement of new projects from the community.

# Methodology

The main methods are the combined use of Github for project tracking and community engagement, and automated information feeds to/from Gsuite documents and forms. We also plan to provide dashboard views for the NCATS CD2H website, which is currently implemented as a Wordpress site. We will consider replacing the site with either a Github.io site or possibly Drupal, to improve the functionality and increase team contributions. 

# Expected Outcomes

* Dashboard overview of all past and current CD2H projects, with their milestones and milestone progress indicated
* Information feed to the CD2H website, highlighting to non-technical users what CD2H is working on
* Content feeds for newsletter and RPPR population
* All CD2H paid staff onboarded to NCATS Gsuite; key/current CD2H content migrated and organized; stretch goal: community members also onboarded

# Deliverables

- Dashboard overview of all past and current CD2H projects, with their milestones and milestone progress indicated
- Information feed to the CD2H website, highlighting to non-technical users what CD2H is working on
- Content feeds for newsletter and RPPR population
- CD2H staff onboarded to NCATS Gsuite and key/current CD2H content migrated and organized

# Timeline (monthly)
* 6/1 - Dashboard overview of all past and current CD2H projects, with their milestones and milestone progress indicated
* 7/1 - New website design requirements complete, website technology chosen
* 8/1 Information feed to the CD2H website, highlighting to non-technical users what CD2H is working on; Content feeds for newsletter; All CD2H staff NCATS Gsuite launched for CD2H
* 9/1 - New dashboard views showing community-level participation/contribution; social network analytics
* 10/1 - Content feeds for RPPR population; Improved project management processes/contribution capabilities for community members
* 11/2019 - RPPR submission

# Potential Pitfalls and Alternative Strategies
One of the goals of the move to doing the project management in Github was that there was a need for transparency, both for project management purposes but also for community engagement and contributions. One potential pitfall is that we have simply migrated the project management to Github but not the actual work itself. The dashboards will still likely be useful as an overview of progress on issues and milestones in this case, but if the actual codebases are not in Github it will be difficult to assess things like contributions, code completeness, activity, and most importantly, they will not provide the much needed opportunity for community contributions. A strategy to address this problem is to use one of the synchonization tools that can synchronize ticketing systems such as Jira or Redmine to Github, and to create public shadow repositories for the work. We will also provide training to help people get used to using Github for their work. Finally, we will explore the opposite synchronization strategies - pushing content back to institutional Jira instances or other work tracking systems. 


# Y3 (July 1, 2019-June 30, 2020) Accomplishments 
The following content is from the June 30 - Dec 30, 2019 mid year progress report [here](https://docs.google.com/document/d/1LLe3uCfEUakWxIJyi5SA4ZocYDmINvhySTperaui1Bw/edit).  Please add progress for Jan 1 - June 30th, 2020. 

* Dashboard overview of all past and current CD2H projects, with their milestones and milestone progress indicated:
  * 100% complete. The CD2H integration of GoogleDrive, GitHub, etc. is available at labs.cd2h.org/analytics; this includes live dashboards into the GitHub milestones and issues for all cores and projects. The Operational  Architecture project has live connections to GoogleDrive and GitHub resources for the project. Data is both captured within the SciTS warehouse and drawn on demand from the APIs, so dashboard views are always current.
  
* Content feeds for RPPR population; Improved project management processes/contribution capabilities for community members:
  * RPPR generator 100% complete. 
  * We developed an RPPR generator driven by structured files in the respective GitHub project repositories and GoogleDrive documents.  This generator was used to instantiate the bulk of the previous period’s RPPR. We are taking a slightly different approach for this mid-cycle RPPR, but many of the components of the generator are still in place. 
  * Workflows for the newsletter are also in place; however we do not anticipate any value in automating this, given the nature of the task.

* CD2H staff onboarded to NCATS GSuite and key/current CD2H content migrated and organized:
  * Onboarding to Google Groups: 100% complete. All onboarding of members (whether to community or all hands) is completed within 1-2 days of survey completion. Rosters of all onboarded individuals (by project, institution, etc) are available at bit.ly/cd2h-people-slim
  * 100% complete: Test migrations of documents from Google shared folders to the ctsa.io team drives were completed and it was determined that email aliasing was a mission-critical feature for program-wide migration.
  * 10% complete: Full migration of existing documents from shared folder to ctsa.io team drive remains to be done. Full deployment of the GSuite instance infrastructure is nearing the final stages of implementation, importantly, email aliasing has been implemented and is now in beta. However, managing the different accounts has been confusing to most people; email aliasing effective 12/11/19 will simplify this somewhat, however aliasing does not appear to be fully working yet. GSuite migration was also deprioritized to make allowance for more outreach activities such as the fall meeting and development of training materials in coordination with CLIC.
  * Remaining work to be done for GSuite migration is described here.
  
* Guidebook chapters:
  * We have established the Reusable Data Guidebook infrastructure and guidance and have solicited the previously indicated required chapters.
  * The GuideBook front end is published using ReadTheDocs.
  * Eight chapters have been published as of this writing.
  
* Information feed to the CD2H website, highlighting to non-technical users what CD2H is working on; Content feeds for newsletter:
    * Round 1 completed; Round 2 underway. 
    * The CD2H Website was completely redesigned and simplified to highlight to non-technical users what CD2H is working on at the core level. Additional information available at cd2h.org/brochure. 
    * Work on round 2 website content and platform configuration was put on hold pending the onboarding of the new now-in-place Admin Core members, including the web developer at Iowa. Certain content is also pending decisions on the Phase III projects (January)


