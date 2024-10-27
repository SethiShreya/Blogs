# Proposal For Outreachy
## Expand Translation and Synonym commands with Wiktionary

## Profile Information
Name:   Shreya Sethi<br>
Email: shreyasethi47@gmail.com<br>
IRC nickname on Matrix: sethishreya<br>
Location - India UTC+5:30 (Indian Standard Time)<br>
Working Hours: 9 AM to 2 AM (UTC+05:30)<br>
TimeZone - Dec. 9, 2024 to March 7, 2025<br>
Commitments - I am currently an XR developer at a Startup, XR Vision Labs, remotely but I assure it won’t affect my work with
Scribe as I have done in the past

[Github](https://github.com/SethiShreya/) | [Linkedin](https://www.linkedin.com/in/sethishreya/)

## About Scribe
Scribe-data is an open-source community that uses
Wikimedia-based data to create and develop software for
second-language learners to communicate effectively.

Scribe’s main user-facing application is Scibe-iOS– a
collection of keyboards for second-language learners that can
be used in any app and provides real-time grammar and
translation assistance to second-language learners in seven
languages: French, German, Italian, Portuguese, Russian,
Spanish, and Swedish. Scribe-data is now also working on
Scribe-Android and Scribe-Desktop.

## Mentors
- Andrew McAllister
- wkyoshida
- Henrik Thomasson

## My Contributions
I have started contributing to Scribe-Data for the past 21 days
(5 Oct to 26 Oct).

I understood and ran the project for the first 1-2 days to
understand the workflow and structure.

Then I started contributing and my contributions include:

### Scribe-Data

| S. No | Time   | Contribution                                             | Number | Link | Merged/Not Merged |
|-------|--------|----------------------------------------------------------|--------|------|--------------------|
| 1     | 6 Oct  | Write data in user user-defined custom directory         | #263   | [Link](https://github.com/scribe-org/Scribe-Data/pull/263) | Merged             |
| 2     | 8 Oct  | Expand Punjabi query for nouns and verbs for Gurmukhi and Shahmukhi | #279 | [Link](https://github.com/scribe-org/Scribe-Data/pull/279) | Merged             |
| 3     | 10 Oct | Expanded total command                                   | #311   | [Link](https://github.com/scribe-org/Scribe-Data/pull/311) | Merged             |
| 4     | 12 Oct | Expanded Punjabi language, expand command to run bifurcated folders | #331 | [Link](https://github.com/scribe-org/Scribe-Data/pull/331) | Merged |
| 5     | 16 Oct | Readme updated                                           | #389   | [Link](https://github.com/scribe-org/Scribe-Data/pull/389) | Merged             |
| 6     | 16 Oct | Emoji Installation Readme updated                        | #388   | [Link](https://github.com/scribe-org/Scribe-Data/pull/388) | Merged             |
| 7     | 17 Oct | Fixed Python path for windows in docs, and issues        | #406   | [Link](https://github.com/scribe-org/Scribe-Data/pull/406) | Not Merged         |
| 8     | 19 Oct | Developed Centralized Emoji generation                   | #397   | [Link](https://github.com/scribe-org/Scribe-Data/pull/440) | Merged             |


## About the Project
Scribe-data is a Python-based backend for the Scribe
community using Wikimedia data to deliver translations,
grammar information, and conjugation details to its command
line interface and user-facing applications ie. iOS, Android,
and Desktop. It efficiently extracts words and grammatical
elements from sources like Wikidata, delivering
gender-specific nouns, their plurals, conjugated verbs, and
autosuggestions.

This project will enhance Scribe-data by expanding its word
translation functionality and adding synonym extraction. The
improvements will directly support Scribe-data’s CLI,
optimizing its usability across applications.

### Objectives
- Enhance translation functionality by integrating a robust
Wiktionary-based translation module.
- Develop synonym extraction for various languages using
Wiktionary.
- Format output data for end-user applications (iOS,
Android, Desktop).
- Ensure future-proofing by implementing unit tests for the
new functionality.
- Optimize data extraction from Wiktionary for performance
and compatibility with Scribe data.

## Timeline (Dec. 9, 2024 to March 7, 2025)
### 1. Research (Weeks 1-2: Dec 9 - Dec 22)
Conduct in-depth research on Wiktionary data structure
and familiarize with Scribe-data’s existing functionalities.
- Identify critical integration points for expanding
translation and synonym functionalities within
Scribe-data.
- Collaborate with mentors to design a structured approach
for implementing the new features.

### 2. Writing SPARQL Queries for Translation (Weeks 3-4: Dec 23 - Jan 5)
- Develop and test SPARQL queries to accurately extract
translation data from Wiktionary.
- Optimize the queries to retrieve comprehensive
translation datasets efficiently.
- Begin testing with sample datasets to ensure the queries
are effective for initial translations.

### 3. Translations (Weeks 5-7: Jan 6 - Jan 26)
- Develop Python scripts to implement the translation
functionality in Scribe-data using Wiktionary data.
- Refine the data extraction process to support multiple
languages while ensuring consistency across user-facing
platforms.
- Format the translation data in line with Scribe-data’s
standards for the CLI, iOS, Android, and Desktop
applications.
- Conduct initial testing with a variety of user inputs to
verify code consistency and functionality.

### 4. Synonyms (Weeks 8-9: Jan 27 - Feb 9)
- Develop and integrate functionality for extracting
synonyms from Wiktionary data.
- Fine-tune synonym extraction for language compatibility,
ensuring integration with Scribe-data’s CLI.
- Format the output data for compatibility across
Scribe-data applications, ensuring accuracy for various
languages.
- Perform initial testing with diverse user inputs to confirm
code consistency and robustness.

### 5. Testing (Weeks 10-11: Feb 10 - Feb 23)
- Write and implement unit tests to validate translation
accuracy, format consistency, and resilience to future
code changes.
- Review and optimize code performance, making
necessary adjustments for efficient functionality.

### 6. Conclusion (Weeks 12-Final Week: Feb 24 - Mar 7)
- Finalize documentation for the new translation and
synonym features, including detailed usage instructions
for CLI and application developers.
- Coordinate with the applications community to integrate
these functionalities into Scribe’s iOS, Android, and
Desktop applications.

## Other Deliverables During Internship
- Weekly blog post about internship and Scribe-Org
community experience.
- Write technical blogs for project flows and working
- Regular communication with mentors and other
community members.
- Help other community members
  
## About Me
I am a graduate done my Bachelor in Computer Science from
the University of Delhi. I have an experience of more than 4
years in development and led my university’s research lab
and students, researching and developing Extended reality,
and computer vision. My interests include Computer Vision,
AI, XR, and Photogrammetry. I have worked with many open
source projects but this is my first time contributing to an
Open source project. I am Immediately proficient in Python
and also have secured a LinkedIn skill badge for Python as
well.
