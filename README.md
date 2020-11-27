# Self-Study-Syllabus
This syllabus lays out a flexible, subject-to-change plan for becoming "job ready" in the software development/data science industries. It is customized specifically for my (Ellie's) interests and focuses, which include a desire to be able to work with data science (especially natural language and marketing) but also to develop applications for end-users. This requires not just a wider set of tools that may be required, but more importantly a deeper and wider understanding of how to use those tools. I hold a PhD in communication with some quantitative research history.

*Time goal*: 6 months from December 1, 2020 (May 1, 2021) - have these skills, portfolio elements, and be prepared for interviews (including algorithm challenges)

*Time commitment*: 40 hours per week minimum, tracked on Wakatime; try to avoid more than one day with no coding per week

## Project Goals

I utilize project-based learning; I select my projects based on both my interests and the skill sets they require, selecting for projects that are both interesting and require mastery of vital skills. With this in mind, I envision completing at least 5 of the following 8 portfolio projects:

* Video game review natural language processing (NLP) analysis and report [in progress, expect completion of main work by December 15, 2020]
    * examine the controversy around a recent video game release; attempt to detect bias and hate speech by utilizing existing training corpuses (for hate speech specifically) and unsupervised topic modeling as well as document/corpus comparison with "peer" video game titles
    * publish findings in a reactive website allowing users to examine graphs and data, and explain the significance from both a diversity and a business point of view
    * skill masteries required: database adminstration (Neo4j, MongoDB, Postgres, possibly MySQL); Python; R; JavaScript (back and front end); visualization libraries (matplotlib, d3.js, datawrapper); React/Express (for data presentation); environment variables; Python lxml and Xpaths for web parsing; NLTK tokenization; spaCy and Gensim visualizations; Gensim trigrams and bigrams; fasttext (Facebook); possibly Tensorflow CPU topic modeling; statistics and mathematics rigor
    * contribution to the field: create a better understanding of circumstances related to online toxicity; help provide NLP data which can be used to identify insincere "review bomb" reviews; develop a baseline corpus for video game review terminology, etc.
* DataMech: a web GUI that queries databases, JSON, and CSV based on user specification to automate certain tedious tasks related to preparing text for NLP processing
    * initial functionality will be to prepare text for fasttext analysis by allowing user to select one column from the data source (presumably the text to be analyzed) and rendering this to a UNIX line break separated text file (sort of a CSV)
    * subsequently, users should be able to select multiple columns to support labeled models for supervised training 
    * aim to support .csv, .json, Postgres, MySQL, MongoDB, and Neo4j to begin with
    * later features will also provide tokenization, etc. at a limited level, according to the procedures of differing toolkits (NLTK vs. fasttext)
    * to be hosted publicly as long as it remains affordable, requiring free user registration to limit overuse
    * skill masteries required: aforementioned database drivers, specifically for JavaScript; Express; GraphQL for backend and database interface; React for front-end *maybe* (this could be implemented with just Express); system administration and security; UI design 
    * contribution to field: providing a quicker way to get to the actual NLP portion of NLP analysis
* Media Inclusivity and Financial Outcomes Analysis [in progress since September 2020, aim to have results by March 2021]: a well crafted, organized, and as much as possible, controlled study of the financial effects of including diverse main characters in mass media - particularly film. May require some clean-room replication of data as IMDb is the source of so much media information and their terms of use are highly restrictive.
    * will involve a partially-manual data mining/database construction effort to gain information on relative and peer titles, and in particular, to gain reliable financial data about them
    * will involve in-depth statistical analysis to determine correlations and attempt to infer causation 
    * technologies required: any database, any web framework to present results; SciPy, matplotlib, NumPy, etc. UNLESS analysis is done with similar libraries using Julia or R; d3.js for visualization; maybe be a good opportunity to try Julia
    * contribution to field: provide hard statistical data to the public confirming or disconfirming common claims about the commercial viability of diverse main characters
* Two-stick Action Game Demo: a demo of a top down 2D sprite game where the player controls an avatar who moves with WASD/stick 1 and aims with the mouse/stick 2. If possible, implement stealth.
    * Masteries required: working with and customizing animated sprite images; either Nodegame and related Node graphics libraries, or Unity and C#; general game design principles; UI design
* "React Native Twine": a clone with expanded functionality of the Twine text game engine, with a different scripting language, compatible with phones and mobile distributions 
    * Masteries required: React Native and Electron; mobile app distribution pathways; GraphQL for the backend; user interface design; designing a scripting language
* Twitter topic monitor 
    * Within the constraints of the Twitter developer API, write a script to archive Tweets naming certain keywords
    * Ideally, calculate the likelihood of the tweet actually matching the topic
    * Collect the maximum amount of tweets the API will permit 
    * Masteries required: Twitter developer API, a database, NLP topic analysis and comparison
* CollectiveBlog
    * An attempt to create an alternative "social blogging platform" to Medium, which maintains *strong* content moderation standards, does not monetize except possibly through unobtrusive advertisements, but does allow users to discover related blog entries and to promote their own crowdfunding/monetization
    * Masteries required: integration APIs for single sign on; general web frameworks; NLP to detect problematic posts for moderation, possibly based on both hate speech and video game data; server infrastructure and deployment; advertisement targeting; scaling
    * Resources required: to be more than a demo, I estimate about $1000 will need to be initially set aside for server costs 
    * This is a project where I would expect to use Kubernetes in production to deploy key elements
*Untitled Media Review & Commentary Site
    * Likely using the same tech as the above, but specifically focused on diversity-centric media journalism, with a custom blog engine 

## Essential skill goals
These are the skills I hope these projects and others that come up will help me develop:

**Coding Languages (Current Proficiency/Target Proficiency)**
Python (Skilled/Expert)
JavaScript (Familiar/Expert)
R (Familiar/Familiar)
Any two of the following 5:
Kotlin (Beginner/Skilled)
C# (Beginner/Skilled)
Java (Beginner/Skilled)
C++ (Beginner/Familiar)
Rust (Unknown/Familiar)

**Utility Languages**
SQL (Familiar/Expert)
Cypher (Skilled/Expert)
BASH (Skilled/Skilled)
Puppet (Beginner/Familiar)
Dockerfile (Beginner/Familiar)
PowerShell (Beginner/Familiar)
Git Config (Familiar/Skilled)
JSON (Familiar/Expert)
CSV (Expert/Expert)

**Databases**
MySQL/MariaDB (Skilled/Skilled)
Postgres (Skilled/Expert)
MongoDB (Familiar/Expert)
Neo4j (Skilled/Expert)
SQLite (Beginner/Familiar)

**Frameworks - Data**
FastText (NLP) (Familiar/Skilled)
NLTK (NLP) (Familiar/Expert)
spaCy (NLP) (Familiar/Skilled)
Gensim (NLP) (Familiar/Expert)
Tensorflow (ML) (Beginner/Familiar)
Hadoop/Spark (ML) (Beginner/Familiar)
C++ equivalents of these frameworks (Beginner/Familiar)

**Frameworks: Web**
React (Beginner/Expert)
Express (Beginner/Expert)
NGINX (Familiar/Skilled)
OPTIONAL/AS PROJECTS PERMIT:
Django (Beginner/Familiar)
Kotlin web frameworks (Beginner/Skilled)
Flutter (Beginner/Familiar)

**General/"Soft" Skills**
Resume polishing
Public web presence 
Personal branding
Algorithms and puzzles
Deep statistical knowledge (Familiar/Skilled)
