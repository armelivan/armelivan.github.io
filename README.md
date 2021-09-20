---
title: "About"
permalink: "/about/"
layout: page
---

An Automated Fake News Detection System Based on Factchecking Analysis and Trusted Web Sources.

Proposed by:
-	Sabrine Amri [sabrine.amri@umontreal.ca]
-	Esma Aïmeur [aimeur@iro.umontreal.ca]
Project description:
Fake news detection can be defined as the prediction of the veracity of a particular news article, using varied approaches. Content-based detection is one of the most used approach, which focuses on what is being transmitted, that is, on identifying the meaning of the content of the news. Factchecking approaches try to tackle this issue.  Formally, fact-checking is the task of evaluating whether the statements made are true, which is usually done by trained professionals [1].

 
Therefore, many fact-checking websites was developed. For this end, we can refer to The International Fact-Checking Network’s (IFCN) signatories list , which lists only trusted factchecking websites that have a high reputation. As example of high reputation factchecking organizations we can mention Africa Check, the Ferret Fact Service, factscan.ca, politifact.com, snopes.com, checkyourfact.com, truthorfiction.com, etc.
The Truthfulness of claims and news is described by factchecking websites using different discrete textual values of ratings. For example, PolitiFact factchecking website uses the following (“True”, “Mostly True”, “Mostly False”, etc.).

 Recently, some researchers [2] are discussing this issue and trying to harmonize their datasets containing the claims through providing normalized rating score alongside the original ratings as provided in their so called (Rating normalization tables for ClaimsKG ). 

In order to provide the normalized rating score, these authors summarise the distribution of rating values and then assigned them to a conservative and coarser-grained set of labels that correspond to the least common denominator between all the classifications of the individual sites. The rating scheme they provide consists of four basic categories (TRUE, FALSE, MIXTURE, OTHER).
However, this rating schema is still difficult to use to measure news truthfulness given by multiple factchecking websites. 
This project aims to develop a software solution to automate the computing of the veracity of a given news (news truthfulness scoring) by measuring the consensus among fact-checkers decisions:
1.	Collect the various decisions made by all factchecking websites regarding the veracity of a given news article (news truthfulness). 
2.	Quantify the given decisions in order to exploit them in measuring the veracity of the news given by multiple factchecking websites. 
3.	Combine the obtained value in step 2, in order to have as output a one single value that represents the decision about the truthfulness of the news. 

In order to improve the result obtained form measuring consensus among fact-checkers, the proposed software must check if the news is already published by a trusted source. These sources may include official websites of different entities such as international organizations, official websites of ministries, official websites of media sources (radios, TVs, etc.), websites of news (yahoo news, google news), verified accounts on social media, etc.

Required work:

1.	Propose a solution for measuring consensus among fact-checkers.
2.	Design and implement the solution.


![image](https://user-images.githubusercontent.com/34576054/133950010-f40424a7-0f9a-416f-ae1b-70f05b4e314c.png)
