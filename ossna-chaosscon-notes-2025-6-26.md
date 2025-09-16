# Notes: 6/26/2025
## Welcome:
- Speaker: Dawn Foster, Director of Data Science, CHAOSS
- State of events, What happens when

## CHAOSS News
- Speaker: Elizabeth Barron, CHAOSS Community Manager
- CHAOSS: Community Health Analitics Open Source Software
- What's new in CHAOSS?
  1. Shift from metric development to practice
    - Now:
      - Stable group of metrics (89)
      - Occasionaly release a new one as needed
      - Metrics Developemnet shifted to Context-based groups
    - Now: Context woring goups:
      - University/Academic Open Source
      - Corporate OSPO
      - UN-SDG
      - Scientific/Research open Source
      - Funding Impact measurement
    - b) Developemnt of Practitioner Guides
      - Getting started
      - Getting started with responsiveness
      - **NEW** Sunsetting and open source project
      - **NEW** Building Diverse Leadership
    - Practitioner Guides
      - Demonstrating You Project's Contribution to the SDGs
      - ...
      1. Community Growth
        - Continue to focus on newcomers
        - Improved empowerment for contributions
        - More structured operational Groups
        - Amazing chapter leaders and Co-chairs
    - Now: Operational Working Groups
  2. Continual 
### Grimoire Labs Into
- Speaker: Santi ...
  - Grimoire Lab 2.0 Updates
  - Improved scalability - Goal to reach 20,000 repos in one day
  - Event-driven test data model
  - Kubernetes Intergration
  - API for CI/CD integration and SBOM ingestion
- Moving from a monolith to a microservices

## Keynote GrimoireLab in Action: Case Studies in Open Source Health Analytics
- Speakers: Terence (Tex) McCutcheon, Open Source Program Manager at Intersect MBO; Georg Link, Open Source Strategist at Bitergia
- Intorduction to GrimoureLabs
  - Is a founding project of CHAOSS with more than 20 years of history.
  - Rooted in research
  - 2004 LibreSoft @ University Rey
  - 2012
  - 2016
  - 2017 Founding of CHAOSS
  - 2024 version 1.0 release
- Case Description: Cardano and Intersection
  - Peer reviewed Blockchain created by Charles Hoskinson
  - IOHK goes open source with Cardano
  - Intersection MBO becomes steward of open source projects
  - Goal: Diversify and strengthen the foundation of Cardano
  - 
- Baseline Metrics
  - The innovation flow in the open source crypto ecosystem
    - We found a three-layer ecosystem.
      1. Most active users
      1. Connectedness
      1. 
  - Collaboration Dynamics
  - Organizational Landscape
  - Technical Leadership Transition
  - Intersect MBO
- Strategy: Paid Open Source Model
  - Sustainability
  - Transparency
  - Treasury --> Open Source --> Product --> Commercial Aduption --> Treasury...
  - Hpow do fund the maintainers?
  - Funding future innitiatives

  - Within Interest - there is an office and an open source commity
  - Intersect:
    1. Ideation
    1. Productization
    1. Technical Validation
    1. Budgeting
    1. Implementation
    1. Measurement
- Tactics: Paid Open Source Model
  - Key metrics - What are we actually getting out of GritmoureLAbs
  - (#) of commits 
  - (#) of issues
  - (#) of PRs
  - Contribution Ladder
    - Focusing on the developer experience
    - When can we contact them 
    - Cultivate new contributers
- Reporting: 
  - Can see how many repositories users are touching of contributers are contributing to.
  - Whay are their issues not being reponded
  - Q: Are there any unique challenges with open source contributions that can't be on done because of smart contracts?
  - Q: Are the any charts/metrics of the increase of contributers year over year?
    - Yes
  - Q: How are you getting overtime metrics? How are you querying?
    - Everything is calculated on the fly, opensearch is used for the backend
    - Persivol
  - Maintainer retainer
    - Project Lifecycle maturity
    Using AI heavily to release these reports
  - Creating a monthly maturity model
  - Can be added to excel files
  - Run through to chatGPT, because they are very strict
  - Review the analysis
- Closing:
  - Takeaways:
    - Establish your baseline early
    - Understand your ecosysyem
    - Collaborate with partners
    - Embed metrics
    - Promote Transparency
  - Q: What are the forks and the stars, Are forks and stars also included in the dashboard?
    - Yes
  - Q: Quantitative vs qualititative anaysis
    - AI is used for the qualitative, but also summarerizing both
  - Q: Do you do anything to filter out bot activity
    - Yes, they are measuing bot activity from GitHub Actions
    - Done by sorting
  - Q: Do you have a filter for AI contributuins or translation bots?
    - That is a growtn metric to hit, they have yet to see transation bots

## The State of OSS Funding data: Insights from ecosyste.ms
- Speaker: Andrew Nesbitt, Software Engineer at Ecosyste.ms
- This is an index of all open source data/stats
- 3 kinds of data
  - Funding.yml file
  - Funding metadat in package mangers
  - Funding metadata in maintainers profiles
- Funding links
  - just a url to get funding
- Funding links in packages
  - 3% of open source
- Most popular Funding Domains
- Top Ecosystems by numbers of funded packages
- Critical packages
  - Most used packages
  - 1% of 1% are 80% of all packages are used on NPM
- About 75% of open source projects don't have any funding
- Let's go Deeper
  - Open Critical collectives are referenced in th critical packages
  - $11m donated 
  - Organizatoopns vs Users GitHub Sponsers
    - 80% are individual contributers/sponsers
- Who owns the projects

## The Hidden Parallel: Why New Contributors and New Maintainers Need the Same Emotional Scaffolding
- Speaker: Laura Langdon, Community Manager at University of California
- Distribute Aid
- New Contributer
- New Maintainer
- Both groups haqve the simalar questions
- Giving resources is just too overwhelming and they won't do it
- The Hidden Parallel:
  - Both groups need the same the thing:
    - Permission to not know things
    - Real-time feedback
    - Understanding cultural norms
    - Confidence that they belong in the space
  - We've been treating these as seperate things
- Qeastions: How detailed should a PR be? How do I give feedback?
- The Open Source reality
  - Often documentation is delayed
  - Newcomers learn by exhausting tria-and-error processes or by oral tradition
  - Learning cultural norms is intimidating and difficult
- The Solution: Tech Hangs
  - Real time collaborative sessions where:
    - New contributers can watch people works and explain their work
    - Handholding happens when people need it.
  - Examples: 
    - Weekly "Talking and Doc-ing" collaborative sessions
- Magic Moments:
  - New contributers see how things are done
- Implementation Framework
  - Start Small
  - Create Safety
  - Make it sustainable
- Bonus: What to say
- How Do we Know It's Working?
- Why this matters for CHAOSS

## Git the Data: Augur’s 15-Minute Collection Kickstart
- Speakers: Cali Dolfi, Senior Data Scientist at Red Hat; Sean Goggins
- Augur is a path to data science removing the mystery
- mountains of data --> 8 Years of data carpentry --> 
- Install Pre Reqs
- Up the resources
- A minum of 6 CPUs
- Q: How do you usually work in Augur
  - I tend to work in a Jupiter notebook
- Q: If I'm new to Augur and I wnat to look at the CHAOSS project, what do I do?
  - Just add CHAOSS repo
  - Use one of the environments, notebooks, dbeavers, 8knot instance
  - The documentation shows the 
  - THe repel repel -- OSS Aspen
- Q: Looks like like it can pool a whole bunch of repos
  - Out of the box it collects on 6 repos, you can add more

## A Guided Tour of an Open Source Community Using 8Knot
- Speaker: Cali Dolfi, Senior Data Scientist at Red Hat
- 8knot, Augur and how they connect?
- There are a set of visualizations I like to look at first
- Project Aspen
- Rappel
- OpenSSF Scorecard
- First graph:
  - Contributor growth by engagement
  - How many are active
  - Who is drfting
    - This number can change based on the community
- Pull request activity
- Lottery Factor
  - Factor over time (every 6 months)
- Commit Activity by Domain
- Organizational assotiated activity
- Q: Do you have any graphs related to commits and issues?
  - When we count a contribution and comments as, do you have a graph for discussions? No
- Q: Other platforms?
  - GitLab, Augur, New Platfroms: CGit, Huge priority 
- Q: What would be the best way to contribute to Augur?
- Q: Was this aggregated at the repo level?
  - You can do both
- Q: If you move from one org how does that get reflected in the data?
- Q: If I'm collecting 100 random github repos is there a way to agregate them?
  - You can put all of the repos in a user group
- Q: If you have an SBOM and you want to assess the overall health of your SBOM
  - Does your SBOM include your upstream repository link
  - Encourage the field to be 
  - spdx 
  - TODO Group

## The Swiss Cheese Model for Proactive Open Source Risk Management
- Speaker: Georg Link, Open Source Strategist at Bitergia
- The Swiss Cheese Model
  - Created in 1990 - James Reason
  - Used for risk assesnmnet
  - Imperfect layers of defense

  - 
- Applying this to Open Source
  - What are the hazards or threats?
  - Attack Risks
  - Software supply chain attack
  - What are the critical assests or processies we want to tprotect
  - In the case of SolorWinds it took about 11% of the annual revenue to 
- 70% - 95% of software includes open source
- Most open source software is hiding in our dependency tree
- Hence Software bill of materials
- SiSa has done a lot of work on SBOMs
- The software resiliance act asks that you do your dodigigence
- What are our defensive layers
- Summarizing this in 4 slices/layers
  - Create an inventory, an SBOM
  - Vulnarability layer
  - Project Health
  - Internal Policies
- How effective is each layer?
- Ineficiencies in the project health layer
  - Overwhelming data
- Single vendor risk
- Vulnerability risk
- Shifting left
- Addressing ineficiencies
- Homework:
  - Play with the swisscheese model

## Closing
- Speaker: Dawn Foster, Director of Data Science, CHAOSS
