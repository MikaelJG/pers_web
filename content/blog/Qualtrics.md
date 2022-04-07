---
title: "Surveys in Qualtrics"
date: 2022-04-03T22:41:10+05:30
draft: false
github_link: "https://github.com/MikaelJG"
author: "Mikael J. Gonsalves"
bg_image: ""
description: ""
toc: 
---

## Rule of thumbs

In creating surveys, remember:

* Simple, multiple choice questions are answered more frequently
* Question wording matters (avoid jargon, focus on accessibility)
* Question position matters (last ones are often skiped)
* Give extensive choices in multiple choice questions
* Aim for realistic scales (with a neutral mid point)
* Divide double-barrel questions (asking 2 questions in 1)
* Written answers are often skiped

For structure, consider:

* Consent/ NDA (non-disclosure agreements)
* General questions (filter your audience)
* Essential questions
* Specific questions
* Democraphics
* Contact information

## With Qualtrics

Before building the survey itself, you may change Qualtrics' default settings.

#### Recommended Qualtrics Parameters

> In: **Look and feel/general/add progress bar** </p>
> Participants will see and appreciate their progress.</p>
> **Options/General/Change display name to match study name.** </p>
> **Options/General/Change survey description.** </p>
> Qualtric's default are advertisements.</p>
> **Options/Responses/Record incomplet questions.** </p> 
> Interesting is to later reflect on incomplete questions.</p>
> **options/security/ prevent multiple submissions.** It cleans data. </p>
> For instance, some may try to multiply rewards. In GUXR, in-game telemetry may be contrasted with survey response. </p>
> **Qualtrics defaults record IP adresses, location data and contact information** </p>
> At the price of anonymity, it also medigates multiple submissions and cleans data.

## Building the survey itself

As first question, prioritize consent. You can easily embed a consent form or nds (non-disclosure agreement) in the question.
> In: **Question type/Test-graphic/More/Insert file** </p>
> Clicking on the file will display it.

#### Consent example (Q.1)

> Thank you for your interest in my survey. Your participation helps advance research on the topic of ...</p>
> This survey is divided into three section: (1) .... (2) ... (3) .... It takes 10-15 minutes to complete.</p>
> If you would prefer to be interview (without completing the survey), please skip to the end where you may leave your contact information.</p>
> **You must be 18 years or older to participate. You do not need to be... to take the survey.** </p>
> -</p>
> All comments and questions may be addressed to the researcher:</p>
> Mikael J. Gonsalves, PhD (email@uwo.ca)</p>
> Department of Health Sciences</p>
> University of Western Ontario</p>
> -</p>
> Please look over the attaches terms of consent before proceeding. **PDF Consent Terms**

#### Confirmation (Q.2)

> **Please indicate if you agree with the attached terms of consent.** </p>
> Yes</p>
> No </p>

#### Find your target audience

Following consent, you have an opportunity to filter participants and find your audience. In multiple choices questions, direct some answers to the end of the survey. It cleans data and helps analysis.

> **In: Question Type/ Question behavior/skip logic OR Display logic** </p>
> With around 2 questions, you will confirm that the right audience is taking your survey.

#### Types of questions

* For multiple/multiple choice questions: Matrix table format. 
* For essay type answers: In-text type question/ select essay text box.
* For % data: slider question.
* For % data equal to 100: constant sum question.
* For ranking: rank order question.</p>
**Yet, simple multiple choice questions are best.**

#### End of survey

At the end, questions can be more specific

For contact info: For field question [ending survey]/Require validation email & phone
The text could look like this:

> Thank you for completing this survey! Interviews will last one hour and will be conducted via phone or zoom. If you are interested, please leave a phone number or email address.</p>
> You will be contacted to schedule an interview.</p>
> -</p>
> Name/Username -{Text Box}-</p>
> Phone Number-{Text Box}-</p>
> Email Address-{Text Box}-</p>
> Other-{Text Box}--</p>
> -</p>

## On Analysis and reports

> **In data & Analysis/Export Data/CSV/ Use numveric values**</p> [relates to R!] </p>
> **In data & Analysis/text IQ... Qualtrics suggests themes** (from text answers)</p>
> Some will not make sense. OR create your own theme. </p>
> **.../text IQ/ Keywords constellation of themes**</p>
> **In data & Analysis/crosstable**</p>
> Useful to cross demographics question & Substantive questions.</p>
> (ex: columns/ political affiliation. Rows/consider yourself as intellectual).

   | Political Affiliation  | Considers as intellectual |
   | ----- | --- |
   | Very conservative  | 80%  |
   | Liberal | 30%  |
</p>

> **In data & Analysis/reports** Qualtrics suggests visuals for every question

## On Distribution

In shared materials, add: 
1. Who is eligible
2. What participation entails
3. How long at of time commitment
4. Assurance of confidentiality
5. Contact info
6. Link to survey

