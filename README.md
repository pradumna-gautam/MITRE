# MITRE
Translating Cybersecurity Descriptions into Interpretable MITRE Tactics using Transfer Learning
• Intrusion logs and threat intelligence reports have been developed to assist security analysts
• Description in these logs and reports, however, can be cryptic and not easy to interpret. Thus:
We ask:
Given a description of cyberattack techniques, how to interpret the intended effects (MITRE Tactics [1])?

• E.g.,1, Initialization scripts can be used to perform administrative functions, which may often execute
other programs or send information to an internal logging server.

• E.g.,2, Custom Outlook forms can be created that will execute code when a specifically crafted email is sent.

Privilege Escalation? Persistence? Both?

Developed a Natural Language Processing (NLP) model to translate cybersecurity descriptions into one or more corresponding tactics to assist analysts in diagnosing what adversaries try to accomplish. Due to the limited labeled data that can be curated from MITRE ATT&CK, we propose the use of transfer learning on the BERT model since it was pre-trained on a vast amount of text data and has the capacity to learn semantic knowledge from a description bidirectionally.
