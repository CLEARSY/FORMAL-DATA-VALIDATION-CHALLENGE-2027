# FORMAL-DATA-VALIDATION-CHALLENGE-2027
![](images/github-title.jpg)

The [RSSRail 2027 conference]([https://rssrail2025.isti.cnr.it/](https://rssrail2027.dzsf.de/WebS/RSSRail2027/EN/home_node.html)) is organising a data validation challenge to promote the use of formal methods for validating constant data among CBTC and ERTMS industry companies, operators, and research teams. 
To participate do as follow:
1. Have a look at the content of this site and see if it fits your skills.
2. Register by sending an email to challengeRSSR2026@clearsy.com. Registration is informal but mandatory to participate.
3. Develop your solution. Ask questions to Matthias. Questions are shared to anyone as well as the answers.
4. Send presentation slides at least 2 weeks before the conference, to validate your participation to the Challenge session.
5. Present your contribution on site in Pisa during the Challenge session.

## What?
The goal? To identify **anomalies** in a database for a specified list of self-sufficient specifications. 
This database, especially designed for this event, will use the open format of the ERTMS system. 
It will include key elements such as telegrams, transponders, and LEUs. 
The tasks aim to verify the coherence of telegram formats, the rules of transponder positions, and the construction of movement authority packets within a realistic framework. 
Participation is free and open to all teams, from academia and from industry.

## How?
The challenge is designed to be completed in one week by a team of 2 to 3 people. 
The necessary resources (specification, data) will be accessible on this dedicated github repository from June to November 2025, allowing participants to organize their resolution team. 
The data will be produced in .xml and .xlsx formats for wide accessibility. 
A support will be provided during this period to address any questions and resolve issues. 
Questions and answers will be shared with all participants to ensure a common understanding.

## When?
During the conference a dedicated 1h30 session will be organized: 10' for Baptiste to present the subject, equal time for the participants to expose their models and results.
It will enable participating teams to present their analyses and discuss the results. 
This will be the opportunity for newcomers to engage with the subject thanks to this hands-on experience. 

![](images/schedule-update.jpg)


## Explanations
### What is Formal Data Validation?
Formal data validation in the railway industry refers to the use of formal methods (mathematically-based techniques) to systematically and rigorously verify the correctness of data used in safety-critical systems. 
It is especially crucial in railways, where incorrect configuration data (e.g., track topology, signal positions, speed limits) can lead to unsafe behavior, even if the software is correct.

###  What is "data" in this context?
In railway systems, large amounts of configuration data are used to adapt generic software to specific track layouts and operational scenarios. Examples include:
- Geometry and topology of the railway network
- Positions and parameters of signals and switches
- Speed profiles
- Balise group positions (for ERTMS)
- Route tables and interlocking rules

### What does "formal validation" do?
Formal data validation checks that all data used by the safety-critical software:
- Are correct (conform to rules and constraints)
- Are complete (nothing missing)
- Are consistent (no internal contradictions)
- Preserve safety properties (e.g., no two conflicting routes active at the same time)


### Typical techniques used
- Modeling of data constraints using formal specification languages (e.g., B, Event-B, Z, or custom domain-specific languages)
- Automated or semi-automated checking using tools
- Proofs or exhaustive checks that the data satisfy safety invariants

### Some scientific resources
- Abo, R., Voisin, L. (2014). Formal Implementation of Data Validation for Railway Safety-Related Systems with OVADO. In: Counsell, S., Núñez, M. (eds) Software Engineering and Formal Methods. SEFM 2013. Lecture Notes in Computer Science(), vol 8368. Springer.
- Bendisposto, J., Krings, S., Leuschel, M. (2014). Who watches the watchers: Validating the ProB Validation Tool}, In: Electronic Proceedings in Theoretical Computer Science, vol 149.
- Butler, M. et al. (2020). The First Twenty-Five Years of Industrial Use of the B-Method. In: ter Beek, M.H., Ničković, D. (eds) Formal Methods for Industrial Critical Systems. FMICS 2020. Lecture Notes in Computer Science(), vol 12327. Springer.
- Lecomte, T., Burdy, L, Leuschel, M. (2012). Formally Checking Large Data Sets in the Railways. In: Proceedings of DS-Event-B 2012: Workshop on the experience of and advances in developing dependable systems in Event-B, ICFEM 2012. 
