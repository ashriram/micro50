---
layout: default
title: Review Model
---


<mark> MICRO 2017 will use a revision-based review process like similar to MICRO 2015. This document is derived from the MICRO 2015. </mark>


This webpage outlines the review process for MICRO 2017. MICRO 2017 will extend the rebuttal period to two weeks (MICRO 2015 set the response period to 3 weeks). Authors of highly ranked papers (those that are likely to be discussed at the PC meeting) will be recommended to submit a revised version of the paper based on the suggestions/concerns of the reviewers. The review process remains unchanged for the papers that are unlikely to be discussed at the PC meeting (rank 80+ and no champion), whereby the authors are recommended to submit a rebuttal only. We discuss the timeline for the review process, and describe the details and decisions during each part of the review process.

## Introduction

<img src="{{ site.baseurl }}/images/overall.png" height="250px">

One of the objectives of a good review process is to provide feedback to the authors that allows them improve the quality of their submissions. In the reviewing model currently employed at our conferences, the reviewers provide a list of concerns to the authors, and the authors have only a limited way to respond, in the form of a rebuttal. The tone of rebuttal typically is to clarify the misconceptions of reviewers. However, the authors are explicitly prohibited from adding any new content to the paper, so they are unable to demonstrate how they have specifically addressed the concerns provided by the reviewers. In the proposed review model, we seek to provide the authors a window of three weeks in which they can revise the paper to address the concerns, and incorporate the suggestions, of the reviewers. This is not unlike the review model used in Journals, except that this is a single-shot revision rather than having several rounds of interactions between the reviewers and the authors. Such single-shot revision has been incorporated at top conferences in other fields, such as the International Conference on Very Large Data Bases (VLDB), with great success. The figure below captures the overall review process for MICRO 2017.

The key dates for MICRO 2017 are as follows: 


* [Submission deadline for full paper: April 4th (11:59 pm EDT)](#1)
* [Reviews due from PC/ERC](#2)
* [Discussion between reviewers](#3)
*  [Determine recommendation for revision/rebuttal](#3)
*  [Reviews released to authors: June 1st ](#4)
*  [Deadline for rebuttal and revision: June 14](#5)
*  [Reviewers read revision/rebuttal: June 16 - June 21](#6)
*  [Online discussion period: June 21-26 ](#6)
*  [PC meeting in Atlanta: June 29-30 ](#7)
* .[Final decision communicated to authors: July 5th](#8)

<!-- -->

1. <a name="1"></a>**Submission Deadline (April 4th, 11:59pm EDT)** 
The submission deadline for MICRO 2015 is approximately one week earlier than the submission deadline for MICRO 2014, in order to accommodate the proposed three-week revision period. The page limit will be 11 pages for text and unlimited space for references. The submission format that we provide will be identical to the camera-ready version, in order to avoid the time to port from submission version to camera-ready version for the accepted papers.  

2. <a name="2"></a>:**Review Period (April 4th to June 1st)**
The PC chair will strive to allocate all reviews within six days of the submission deadline. Each paper will be assigned five reviews: 3 from PC and 2 from ERC. The reviewers will have six week to complete their reviews. The six-week review period is similar to what we currently have for HPCA, so it is not unreasonable to expect reviews in six weeks. 

3. <a name="3"></a>**Online Discussion Between Reviewers (May 20th - June 1st)**
There is a one-week period between the review submission and releasing the reviews to the authors. The purpose of the pre-rebuttal discussion is that the reviewers can see the other reviews. This will (hopefully) help all the reviewers to build a consensus on the concerns and feedback, and also eliminate potential misunderstanding that a reviewer may have. The reviewers are allowed to change their scores based on the discussion.
**Determining the Decision of Rebuttal or Revision (May 30th - June 1st)**
All papers should have five reviews by this period. All papers will be rank ordered based on the average score of all the reviews for that paper. To reduce the workload for PC members, only a select few (that are likely to appear at the PC meeting) will be recommended for revision. In addition, a reviewer can champion a paper for revision.  The algorithm for determining the recommendation of revision is shown in the figure below. Note, that we are using a threshold of Top80 only as an example, and we may need to fine-tune the exact threshold based on the runtime information. Similarly, we may consider using a model that ignores the review with minimum score while calculating the average scores for the paper, in order to reduce the impact of an outlier harsh review.  **The outcome of this phase is to group the papers into two categories**: (Category A) "Invited for Revision" and (Category B) "Recommended for Rebuttal Only". All papers in the Category A will also be allocated a “lead”. The lead will “oversee” the reviews, revision, and discussion for the rest of the process, including the post-response period.
<img src="{{ site.baseurl }}/images/review.png" height="250px">


4. <a name="4"></a>**Reviews Released to Authors (June 1st)**
Along with the reviews the authors will get one of the following recommendation: (A) Invited for Revision (In addition to Rebuttal)
(B) Recommended for Rebuttal Only. For the “Category A” papers, authors are allowed to incorporate the suggestions from the reviewers and address their concerns. The authors are encouraged to improve the editorial quality of the paper. The authors must highlight the sections where changes are made. The authors are NOT allowed to make any unsolicited additions to the paper. In the rebuttal, the authors should point to the sections in the revised paper where they have addressed the concerns of the reviewers, and summarize the revisions made. For the “Category B” papers, the authors are recommended to submit a rebuttal only.

5. <a name="5"></a>**Authors Submit Rebuttal and/or Revision (June 14th)**
The authors have three weeks to submit their revision and/or rebuttal. Note that revision is optional. So, even if a paper is recommended for revision, the authors may still choose to respond only with a rebuttal (or choose to not respond at all).

6. <a name="6"></a>**Reviewers Read Revision and/or Rebuttal (June 16th - June 21)**
The reviewers read the revisions for “Category A” papers, and see if/how their concerns got addressed and provide their final merit score. For “Category B” papers, the PC members read the rebuttal and provide their final merit score.  The reviewers have approximately 10 days to key in their post-response scores.
**Online Discussion Before PC Meeting (June 21-26)**
The reviewers discuss papers online and revise their scores. By default, papers in Category B are unlikely to be discussed at the PC meeting, unless someone advocates for the paper. The online discussion can promote a paper in Category B to be discussed at the PC meeting. All papers in Category A will get discussed at the PC meeting, however it is understood that the rank of any paper may get lowered if the reviewers reduce their scores based on all available information. **The PC chair will lock the submission website on June 27-28**, to compile the rank ordered list of all papers based on post response rankings, in preparation for the PC meeting.

7. <a href="7"></a>**In-Person PC Meeting in Atlanta (June 29-30)** 
The PC meeting will be held in Atlanta. We will have a 1.5 days PC meeting. The papers will be discussed in rank ordered arrangement based on the post-response merit scores. The author names will remain shielded throughout the process to maintain an unbiased process. We are also looking into using buzzers for the voting during the PC meeting to ensure a fair, unbiased, and quick voting.  

8. <a href="8"></a>**Final Decision to Authors (July 4th)**
The accept/reject decision will be communicated to the authors on Thursday, Sept 3.

Disclaimer

This is a compile-time list of process and policy decisions, and the policy decisions may need to be fine-tuned based on runtime events. Keeping in the spirit of compiler-microarchitecture interaction of MICRO, the PC chair will strive to develop the best static decisions before the process starts, but override these decisions if the runtime information demands as such. All changes in key decisions will be communicated to the steering committee. 
If you have any feedback or suggestions, please email the Program Chairs at emer@csail.mit.edu, sanchez@csail.mit.ed

<!-- -->

------------------------------------------------------------------------------

<h3>Frequently Asked Questions/Concerns about the New Review Model (adopted from MICRO 2015) </h3>

1. ***Do we have enough time to be able to do this?***

	Yes. The typical review period between submission and rebuttal for
	MICRO is 11 weeks. For HPCA it is about 7 weeks. So, MICRO enjoys
	a 4 week longer review period. We have&nbsp; pulled the submission
	deadline for MICRO by one week, as the submission deadline for
	MICRO does not clash with results of a prior conference. We have
	thus been able to fit the 3-week revision window in almost the
	regular timeline of MICRO.

2. ***Isn’t this too much work for the PC members?***

	We have worked on policy decision to reduce the extra work.&nbsp;
	The restriction of limiting the revision to only Top80 papers was
	done primarily to reduce the added work from revision.&nbsp;&nbsp;
	For example, if 300 papers get submitted then roughly one-fourth
	of the papers will be eligible for revision. For example, out of
	the stack of 20 papers for the PC member, only 5 will be
	recommended for revision, on average. We can safely assume that
	the top 2 or so will not need (a major) revision, so it is really
	generates into reading the revised version of the remaining 3-4
	papers which the PC members have already reviewed once. We believe
	this is not as much extra work for the PC members, especially if
	it helps them make up their mind, seeing their concerns have been
	addressed. Furthermore, these papers will get discussed at the PC
	meeting, so the extra discussion and time spent on these papers
	will hopefully lead to more meaningful discussions at the PC
	meeting.

3. ***Isn’t this too much work for the authors?***

	Only the Top 80 papers are invited for revision. This means
	that the paper has a pretty good shot at getting accepted, so we
	are providing an additional opportunity for these papers to make
	their case by revising their papers in response to the reviewer's
	concerns. However, revision is optional, and; the
	papers will not be penalized if they chose to not submit a
	revision (or rebuttal for that matter). For the papers that are
	not in 	the Top 80, there is no option for revision (unless there is a
	champion), so we would recommend a rebuttal only, so the
	process remains the same as what we have right now for these
	papers.
	

4. ***Isn’t three weeks too short for the authors to revise their papers?***
	
	The duration between decision and camera ready for MICRO 2014 was
	about 4 weeks. So, if the concern took more than 4 weeks to
	address, then the authors would not have been able to put it in
	their camera ready version anyway. So, the 3-week period misses
	out on the class of concerns that would have been possible in four
	weeks, but not three weeks, which we are inclined to believe are
	fairly uncommon.
	
	
5. ***Is there a control on what gets added to the revised version?***
	
	We will have guideline stating that the authors are not allowed to
	include any unsolicited new material in the revised
	version (for example, it is not okay to write a cache paper first
	and ''revise'' it to a branch prediction paper). The only purpose of
	the revision is to address the questions pointed by the reviewers
	and possibly to enhance the editorial quality of the paper.
	
	
6.  ***Are we encouraging people to submit sloppy papers, given that
	there is a second shot?***
	
	The paper has to be in the PC-meeting discussion range (Top 80) in
	the pre-revision stage to get a recommendation for revision. For
	example, if the paper ranks in bottom half of all submitted
	papers, then this new process will degenerate into what we have
	right now — the authors submit a rebuttal and the decision will be
	based on the reviews and rebuttal. We are hopeful that the revised
	process will encourage the authors to submit the best version of
	the work, so that they can be in the Top 80, and get a
	recommendation for revision. 
	
	
7. ***With the proposed scheme authors might spend significant
	time revising the paper only to have it, ultimately
	rejected, which could be a little disheartening*** – PC member
	
	Yes, that is true, and the sentiment would be understandable. It
	would be important to set the expectations right to avoid/reduce
	the disappointment. We plan to communicate to the authors that an
	invitation for revision is not a guarantee that the paper will be
	accepted. There are about 80 papers invited for revision, and
	historically about 50-55 papers get accepted. If the authors
	address the reviewers concerns, then they will increase the
	likelihood of the papers getting accepted. Even if the paper does
	not get accepted after revision, the authors will still have a
	stronger version of the paper to submit to a later conference
	(e.g. HPCA), so their effort in revision is not wasted. Similarly,
	if the paper is accepted, then the authors now need to do that
	much less work for the camera ready version. So, in either case,
	the effort in revision is not wasted effort -- the effort just
	gets shifted in time, and hopefully with the added benefit of
	increasing the likelihood that the paper gets accepted at MICRO
	2015.
	
	
8. ***Are we converting our conference into a journal? ``I see
	this as a bug and not as a feature''***


	We are just trying to get the best elements of the review process
	wherever we can find them, and fit them in our time constraints.
	Therefore, we are limiting the revision to only the papers are
	likely to be in PC meeting, and the iterative revision is limited
	to one round too (inspired in part again from VLDB conference,
	where after one round of revision the authors get a decision of
	either an accept, or do not submit till next year). With the
	proposed change, our conference still remains a conference, but
	hopefully with a much stronger review process.
