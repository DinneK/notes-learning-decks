# Notes: 6/23/2025
## Keynote Notes:
### Morning Anouncements
- 1st Speaker: Jim Zemlin - The Linux Foundation
- 2025 So Far - Highlights
  - OpenInfra foundation
    - Airship
    - Kata Countainers 
    - Starlinx
    - Openstack
  - OpenSSF
    - Launch of Model signing 1.0
    - Introduced a signin network
  - Open Universal Scene Descriptor
    - Tools for visual fx
  - Nvidia
    - RISC -V
  - Overture Maps Foundation
  - Tazama - Tazama Drops
    - Real time modern prevention of finacial fraud, particularly in the developing world
    - In order to provide better financial inclusion 
  - Cloudflare - C2PA
    - Content Authenticity Initiative
  - CNCF Launches - GitJobs
  - PyTorch
  - Weekly Newsletter - 
- New Things at the Linux Foundation
  - State of talent 2025
  - The joint development foundation turns 10 - JDF
    - Consensious for a set of inellectual property agreements
    - Open source and standard developement offices merging
  - OpenSTX Project
    - Wireless networking Technology
  - FAIR Package Manager Project
    - Federated and ...Repository
- 2nd Speaker - Mike Smith - Google
  - Agent2Agent Protocol Project
    - How to deploy agents to connect AI models.
    - Truly open protocol

### Keynote: Frank Nagle, Assistant Professor Harvard Business School & Chief Economist, The Linux Foundation
- Speaker: Frank Nagle - Moving to MIT
- The Economic Value of Open Source
  - Value = Price * Quantity
    - P(OpenSource) = 0
    - Q(OpenSource) = ???
  - "Price is just what you pay. Value is what you get." - Warren Buffet
  - Digital Dark Matter
    - APACHE HTTP Server Project
  - Census II Report
    - 10k+ companies
  - Used COCOMO II to figure out value
  - 15 Years ago only 42% of companies used open source 2010
  - Today 97% of companies use open source 2024
  - OSS contributers gained 2X productuvity 
  - When should companies contribute to open source?
    1. Early or late in the tech lifecycle
    2. Lower in tech stack
    3. Market unlikely to be winner take all (or You control the standard)
    4. Very low or very high levels of competition
    5. Lower acceptance or regularity clarity
  - Collaborate on the Core Compete on the edges

### Keynote: The Agent2Agent (A2A) Protocol Project - Mike Smith, Staff Software Engineer, Google
- Speaker: Mike Smith
- What is A2A?
  - Open protocol for how agents can communicate with one another over and over
  - Explosion of people interested in building agents
  - How do I make a call to this agent
  - AgentCards (JSON document) and RPC (JSON RPC)
    - Agent intactions can be compicated 
    - Trying to simplify into one request
  - Independent Agent Stacks
    - Stacks very
- Upcoming Spec Updates
  - Extensions
    - Ways for people to introduce inpependent extensions
  - Registry for available agents
    - Created a registry proposal Google GitHub
  - Agent Trust
- What about MCP?
  - Is there already a protocal out there?
  - Agents Talking to Tools
    - End-User -- Client -- remote agent (These can be ambiguous)
  - Believes all of these things deserve to live together

### Keynote: Brian Chambers, Chief Architect for Chik-A-Filet & Michael Henry Chief of Information, Secretariat of the Airforce, Studies and Analysis
- Speakers: Brian Chambers & Michael Henry
- Edge Monsters
  - The edge depends on who you are serving
  - How many you are serving
- Connectivity is a challenge
  - Network connectivity
  - Bandwidth
  - Resource contraints
  - Physical Space constraints
  - Lack of on-site tech support
  - Scling footpront costs
- You have to own the entire stack
  - Cluster management is a huge deal
  - Security
- 6 Priciples for crushing it at the edge
  1. Do the heavy lifting
  1. Build a "North Star" Edge controller
  1. If it's not declarative, it doesn't exist
  1. Security must be built-in, NOT bolted on
  1. Telemetry... only when you need it
  1. Heed the Storage Gremlins
- Everything done at Chick-A-Filet is built on open source technologies


## Government Space
- Speaker: Jordan Kasper
- Transparency
- Cost * - If we don't contribute back to the 
- Contribution
- FOR THE PEOPLE!
- Challenges:
  - "OSS is insecure"
    - They say that they can't confirm the source of the software
    - It's difficult for the federal government to acept that it is secure
    - Publishing - "Say, that this will make it vulnirable"
    - "It's illegal" - said by a lawyer
    - When a contractor writes the system that contractor owns the copyright
    - "We paid for it's ours"
    - Lack if Tecnical Knowledge
    - Stagnation
      - Hard for civil technololigist don't keep up with current tech
      - Resulting in vulnarabilities
- Federal Source Code Policy (M-16-21)
  - Section 4: Government-wide Code Reuse
    1. Data rights to share code
    2. Code inventory
      - SHARE IT Act - Source code Harmonization And Reuse in Information Technology Act
- EO 14144 (January 2025)
  - Section 2(c) (was 2(e))
- Reality of open source
  - Is anyone actually using open source?
- Some examples?
  - SE Linux(NSA) 2000
  - US Web Design System (GSA)
  - Open MCT (NASA)
  - IRS Direct File (IRS)
- How much is open?
  - What about upstream OSS?
  - Government is (arguably) the largest consumer of OSS...
  ...and might be the worst consumers of open source.
  - What are the processes of using open source:
    1. Selection
    1. Consumption
    1. Contribution
- The Possibilities
  - GOAL: Increase Open Source Publication
    - Clear guidance on the process
    - Build modular, reusable components
    - Make it a contractor requirenment
    - Enforce secure coding practices
  - GOAL: Secure Government Systems
    - Maseline OSS selection process
    - Automate OSS scanning & approval
    - Use mirrors
    - 
  - GOAL: Support a Secure Ecosystem
    - Contribute all security fixes upstream
    - Contributions to OSS we rely on
    - Grants fopr critical OSS infrustucture
    - Be an active participant in the community
- What can you do?
  - Push for open by default


## Panel Discussion: Open Source: What's Next
- Speakers: Tony Wasserman, Stormy Peters, Rao Lakkakula, Nithya Ruff, Chris Aniszczyk
- Is it reasonable for an AI program can write code and give it am open source liscence?
  - Stormy: Concerned about people stopping contribution to open source. Gen Z is afraid of looking bad in public, AI can help onboard people.
  - Nithya: We are forgetting different things
  - Tony Wasserman: LLMs don't think, there is a whole area that is missing
  - Rao: Believes that in general AI will contribute to open source. We have to be very clear about what we do.
  - Chris: Discussed "How do we get established developers to change there ways?" Put it in the KPIs.
- How do we bring in new people? What are the motivating factors? 
  - Nithya: AI is taken for granted. I worry that people are not looking beyond the code. What is the legal implication? Why certain practices are used. Would love to see more mentorship in governence.
  - Stormy: It's gotton really hard to know where to go to find the project. No standard on any of the projects.
    - Reddit has an agreement with Google
  - Rao: Contribute more to the projects we consume. Start working on the core and that's how you build sustainability.
  - Tony: Now somebody has to come in and maintain the code.
  - Nithya: Maybe AI can be leveraged. LLMs can be trained on old code.
  - Chris: Open source and sustainability, code should be openly governed. You are opening the door to increased contributions. The conversation around sustainability can't be decoupled from governence.
  - Nithya: We need support networks with deep culture around sustainability.
- What role do you think education plays in sustainability?
  - Stormy: Education is a different question than the question of open source sustainability.
  - Chris: For the learner I think it's important that they embrace the approach that works for them.
- How do we find mentors?
  - The todo group is nothing but a giant community of OSPOs
  - Curious: University OSPOs
  - Session later today: TODO Group AI
- How do we get the people on this panel to get that next generation to come to open source?
  - Intentially mentor
- How were you sourced to be the panelists?
  - Sometimes we really lean on those who we are comfortable with
  - Stormy: Always happy to copresent
  - Panels are great way to dip your toe in.
- Hilary - Linux Foundation
- There is need for OSPO mentorships, or technical writing mentorship. 
  - Governence mentorships
- Supply chain will be paramount in the future and open source is huge contribute to it.
- TODO Group is looking to start a mentorship program
- Are there new areas about how to report value back to companies.


## Panel: The Impact of Funding for Sustainable Open Source Projects
- Speakers: Alyssa Wright, Dawn Foster, Georg Link, Andrew Nesbitt
- What have you learned over your time funding open source, that has shifted your perspective?
  - Alyssa: Always amazed by what you don't know. It's way more than just getting grants/money. When thinking about foss, we think about the health of the network and long term impact.
  - Dawn: Learned how difficult it is to show the impact of what you are doing. Particularly with government funds, they all do different things, and you have very different projects, different objectives. How do you measure the impact? It's not as easy as going up and gathering data.
  - Georg: Didn't know how many projects are maintained and owned by individuals. 
  - Andrew: There is more to it than money, sustainability, 
- How can we brainstorm some additional resources to make sharing easier and more accebile for single maintainers?
  - Dawn: Giving people access can be be problematic and makes people more cautious. 
  - Alyssa: It's a problem of trust. Building cultural spaces where we can build trust. How can grow in this project as apposed to how do we grow the community?
  - Andrew: How do implement governence in a project? That stuff is really hard. And not a lot of documentation around it. Possible solution is a lot of documentation and training?
  - Governence changes how the project has to be handled. There has to be more than one person.
- Looking for grants in hard. Are there other things that you have come across that will help with that kind of funding?
  - Is there something about measuing threshhold around projects. If you are looking for funding to sustain the project, you have not crossed the threshhold for maintainablility.
  - Dawn: How does the project evaluate funds and what is the funding for. 
    - One of the things is setting up a curriculum.
  - Andrew: A lot of projects find themselves in a high level of state, but didn't move up in the same rate of maturity. Need to move both at the same rate.
    - If you can find someone who knows how to write grants, hold on to them.
  - Georg: Sees a gap in the middle
- Insights on ecomonmies of scale. And what are some insights on critical mass?
  - Andrew: Trying to build several things at once.
  - The value of storytellers can't be underaestimated. 
- What happens don't go right?
  - Dawn: Building these open source communities is ridiculously hard work. Recruiting contributers is a lot of work. I think it's oke that not every project survives forever. Currently, looking at the reasons projects are being archived. We should stop beating ourselves up about it.
- What would you do with money, no strings attached to improve open source?
