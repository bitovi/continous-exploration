# Bitovi's Continous Exploration Pattern

This is a sample project that shows how to progress medium to large inititives (feature ideas) into:

- Prioritized
- Estimated, and
- Efficiently deliverable 

workstreams.

## Workflow

You can see an example `Free Fanny Pack` initiative being filled out across different stages in the workflow in this repo's [Program Initiatives project](https://github.com/bitovi/continous-exploration/projects/1).

The workflow steps (and matching example initiative) are as follows:

- __Unrefined__ - [fanny pack example](https://github.com/bitovi/continous-exploration/issues/7) - Raw ideas
- __Has requirements__ - [fanny pack example](https://github.com/bitovi/continous-exploration/issues/1) - User-centric requirements, wireframe, out-of-scope features.
- __Has estimate__ - [fanny pack example](https://github.com/bitovi/continous-exploration/issues/2) - Work breakdown and development cost estimation.
- __Has evaluation__ - [fanny pack example](https://github.com/bitovi/continous-exploration/issues/6) - Value proven and/or estimated.

Each one of the `fanny pack example` issues above includes an example of the work in that stage and an answers the following questions about that stage:

- What is the purpose of that stage?
- How to move an initiative into that stage?
- How to sort that stage?

## Background

This pattern is inspired by [Scaled Agile's Continous Exploration process](https://www.scaledagileframework.com/continuous-exploration/) and Bitovi's work over the past several years. The pattern outlined here a more stakeholder-driven workflow than the more agile `Observe > Hypothesize > Validate > Develop > Validate` methods that Bitovi prefers. However, most companies are still strongly stakeholder led. So this workflow works very well for those organizations.

Example of a more agile workflow:

![Pure Continous Exploration](https://docs.google.com/drawings/d/e/2PACX-1vRG_Eiduu9xIWeSbWa_xWY-yf9qVcCeEP8aFJvaFWmfKEEBDHhRRRBzpGaYt6mA03m273ujU8qs3QQ8/pub?w=500)

![Continous Exploration With Stakeholders](https://docs.google.com/drawings/d/e/2PACX-1vQ0zOne0Um6B6HR1lExc-mG5AncvPtm4jOJihHStDPSQZZ1sW1WFYtDiQq7DE_n6FP1Vv6b0Q4GvHhK/pub?w=500)


## Operation

Most of this work can be done by two groups of individuals:

- Stakeholders
- Project Manager (PM) - aka Product Owner (PO) or Technical Product Owner (TPO)

We recommend that this work is done continously. This means that these initiatives are being _filled out_ and _reprioritized_ each sprint. The results of that effort are also being shared with the larger team each sprint. To develop an initiaitve, a TPO will typically have 7 meetings over a 3-4 week period.

First, there is a `CE Meeting` every sprint where the TPO and Stakeholders reporitize the program backlog.  Once an item in the `unrefined` list is selected as top priority, the following happens:

- Meeting 1 - (1 hr) Meet with stakeholders to get high-level requirements. Include UX and engineering represenative.
- Work item - Develop the UX, write up the initiative's requirements.
- Meeting 2 - (30 min) Review the UX with stakeholders.  Attempt to get initiative into `has requirements` stage.  
- Work Item - Break down the initiative into expected epics.
- Meeting 3 - (1.5 hrs) Meet with the engineering to review the requirements, start breaking the work down into epics. There will almost always be followup to requirements.
- Meeting 4 - (30 min) Meet with stakeholders and review engineering considerations.  Update the initiative's requirements.
- Meeting 6 - (1 hr) Meet with engineering to finalize epics. Attempt to move initiative into `has estimate` stage.  

Once this work is complete, the TPO should work with stakeholders to prioritize the initiative in the `has evaluation` list.  Once prioritized, this loosely represents the development backlog.


<details>
<summary> Comparison to Scaled Agile's PI Planning events </summary>

This is in contrast to Scaled Agile's [PI Planning](https://www.scaledagileframework.com/pi-planning/) where everyone meets face to face for multiple days once a quarter.
While many organizations like this approach, Bitovi finds it inneficient and less effective than a continous approach for several reasons:

__Spacing__ - PI Planning happens all at once, this creates several difficulties:

- It requires a huge amount of preperation is needed to organize work for a 3 month period. Individual initiative-focused meetings are easier to prepare.
- It doesn't provide time for digestion and thoughtfulness. People think better when given time to digest, think, and research. Incremental meetings spaced out produce better results.

__Output Mismatch__ - PI Planning doesn't often produce an output that matches what teams use for day-to-day planning. PI planning is often done with physical cards, strings and tape. While this is fun, it has the following downsides:
- There is extra work to translate the physical board into its digital representation.
- Plans will change and additional planning meetings will occur. But these will likely be done against the day-to-day digital representation. This results in teams planning in 2 different systems. Incremental meetings are always done within the digital representation of work.

__Remote Challenges__ - PI Planning doesn't work well for remote teams. You can't easily "break out" online like you can in-person. Incremental meetings around a single initiative can be more easily targeted to include _just_ who needs to be included. These smaller meetings are less wasteful of people's time.

__Proving Value Early__ - PI planning doesn't lend itself to proving value early. The meeting's goal is to plan out the delivery of specific features. It doesn't create space for "proving" those features are valuable. 



That being said, PI planning is __great__ for team building.  

</details>

## Artifacts

- Program initiatives board
- High-level project roadmap
- Detailed roadmap
