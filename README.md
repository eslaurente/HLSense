**HLSense Message Search Utility**

HLSense is an individual project that allows a user to search a database of already-categorized HL7 messages. Examples of different HL7 message types are ADT, ORM, and ORU messages. "HLSense" because it views very cryptic, dense HL7 generic messages in a high-level abstraction. One could say HLSense makes sense of the HL7 messages in the database. HLSense has already deduced key identifiers of an HL7 message enough to provide the user the basic functionality targeting the message or messages that he/she needs, based on key criteria. The web application should allow the user to search by a small set of criteria that, such as the patient's name, SSN, the MHR's MRN, order number, etc... This application's purpose is to help facilitate the organization of HL7 message records, at the same time, being user-friendly for anyone to use.

**Use case:**

Suppose Andrew, an OCHIN staff, wants to find a particular message and what the RAW message was. He knows what message type of the HL7 message and know the date OCHIN received it. He opens up HLSense:

    He realizes that HLSense is pretty intuitive: The header has the words "A message...", with a checkbox that says "with" and a dropdown list of the criteria. In his head, he vocalizes, he is on HLSense "to find a message with a message type of 'ORU', that was received on the 02/03/2015".
    He follows this sequence of criteria and replicates it from the options on the top of the page to the "Find" button
    He checks two boxes for two criteria: the type of message and date received and clicks "Find".
    The table below the page lists the results of the search.
    He clicks the Date column of the table and orders the list by Date
    The first element on the list seems to match what he was looking for, so he double-clicks it and a pop-up box shows two version of the message: the original RAW message, and the transformed message (if it was transformed).
    Andrew is happy

**Technologies**

MEAN Stack ( MongoDB, Express, Angular.js, Node.js: JavasScript-oriented full web development stack)

    MongoDB (a database management system, gaining popularity as it has a 'NoSQL' approach to relational databases)
    Express (a thin routing framework layer above Node.js)
    Angular.js (JavaScript front-end framework)
    Node.js (allows a JavaScript-based web server and library/package dependencies)
    http://mean.io/#!/
    WebStorm IDE (JetBrains' JavaScript IDE)
    GitHub (Version source control)
    Windows 7/8 and Mac OS X environment

In this implementation phase, I will be learning the MEAN stack and implementing it as I go, starting from the back-end, making my way up to the front-end according to my minimally-viable product (from my mockup below)

**Minimally-viable Product**

The implied features and systems in the mockup (attachment below)

**Stretch Goals**

Be able to display messages in HL7 messages in a pretty-print, tree-like structure Register new user/User login system Administrative system Create new message entries via the front-end (most likely an administrative/elevated user feature)
