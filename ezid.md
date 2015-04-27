# Essential scoping documents for this work #

Important documents:
  * [Briefing presentation which scopes potential EZID(uk) work ](https://docs.google.com/open?id=1P8Fad_Rh5myjXO2qotZYvYedBxtzCDM8h3XT1s1RkPo)
  * [Persona use cases, first used to describe this work to senior level management (not based on real case studies)](https://docs.google.com/open?id=1VWKPVfrM-zKh8mdL2zVuCKlYTAseMobO6dhEelV12eQ).
  * [Initial brainstorm of potential WPs that would need to take place by CDL and JISC](https://docs.google.com/drawings/d/1915-Mn7rac9zXLA04FImMS2pH8V5r3_BlKmExsNgxT4/edit?hl=en_GB).
    * Estimate Budget from CDL on cost of WPs (see DFF email).

# DFF Handover notes #
Written on 20 Dec 2011

People involved:
  * From CDL:
    * Joan Starr (JS), Patricia Cruse (PC), John Kunze (JK), Greg Janee
  * From JISC:
    * Rachel Bruce (RB), Neil Jacobs (NJ), David F. Flanders (DFF), Torsten Reimer (TR), Joseph Hutcheon (JH)
  * Potential participating partners (Not Confirmed):
    * Edina via Christine Rees, Ian Stuart, Stuart MacDonald
    * Mimas via TBC
    * Cottage Labs via Ben O'Steen

## Previous development of this work ##

The origin of EZID began back in Nov of 2010 when RB and NJ visited several partner organisations in California to explore future potential options for partnerships with the Digital Infrastructure team.  This visit was followed up by DFF during his March 2011 visit to California where he attended the CNI conference as well as followed up RB /NJs visit to CDL to explore the potential of international infrastructure development.  Of interest was the use by CDL of the 'microservices' metaphor to explain how small services could be designed so that they easily fit together as a series of pipes like in plumbing.  One of these services that had developed from the microservice effort was the EZID service that CDL currently runs.  As EZID stands now its primary business use case is the provision of bulk sets of identifiers for datasets so that researchers can easily assign multiple DOIs to hundreds if not thousands of datasets.

From the March 2011 meeting with DFF, JS, PC & JS, several ideas were brought back to NJ and RB with regards to potential international infrastructure prototype services that JISC and CDL might consider as a joint activity.  JISC at the time (as well as now) is actively looking for potential business models it can utilise to incorporate itself (most likely as a not-for-profit organisation); CDL's business model is one of interest and so doing an innovation project with CDL gives an extra motive for looking to work on a project with them from JISC's PoV.

A further visit to the UK by JK occurred in the summer of 2011 where DFF (based on discussion in March 2011) had been able to develop for a UK audience and use cases for further develop of EZID for a UK context, aka EZID(uk).  The primary shift in the proposal for the EZID(UK) microservice as opposed to the EZID(CA) service is that it is primarily focused on the individual obtaining one or two identifiers (not hundreds or thousands).  There are a couple of use cases written up to elaborate this point of individual interaction with the service (see essential scoping documents above).  Another important analogy early on in these discussion with regards to the potential production of EZID as a service is that it MUST be focused on successfully delivering to a single audience in the first instance. Much like the success of the JISC's Turn-It-In (plagiarism) microservice which focuses in on a single audience (undergraduates), though also services a full range of use types be that postgraduates or researchers as well.  In the same way, the EZID(UK) service MUST be focused as a product marketed to a single audience, with reliance that this audience will naturally encourage other audiences to join, e.g. undergraduates will encourage their lecturers to use it or vice-versa.  The primary risk in this work is seeing its potential use for many audiences and therefore not focusing in on delivering a successful product to a single set of users.

During JKs visit in the summer of 2011 further details were able to be discussed with regards to potential balance of work as well as how to position the work as an innovation project (not as service, though JISC will consider its potential as a service during its course as an innovation project).  Careful balance must be struck with partner's (such as the BL, whom, for example provide an API to obtain bulk instances of datacite DOIs; as our Databank project is currently utilising).  However, of the upmost importance is the need to recognise that EZID is not guaranteeing persistent identifiers, but rather _offering access to a range of persistent identifiers_ so the user has **choice** in which identifiers they wish to use, accordingly the value statement of the project is not one of benefit to political or national organisations who are attempting to preserve the scholarly record, but rather **benefit to the user** in being able to save time by 'copying & pasting' an HTTP identifier in their research so they don't have to write out a citation reference every time they cite a thing, ergo the value statement is **ease** of use in **identifying** things, hence the name EZID (as well as its handle 'n2t', which stands for "name to thing").  Again, EZID is not guaranteed to persist identifiers but rather to provide choice to identifiers where the organisation says they will persist [1](1.md).

During Q3 & Q4 of 2011 CDL and JISC were able to draft up a series of potential workpackages that would need to be achieved to transform the EZID tool into a more specific workflow for obtaining identifiers by individuals.  These WPs were discussed with Edina given their expertise in URNs, Perl, BSD, IP Range Resolvability and LOCKSS which enabled JISC to spec out WPs that would need to be completed in partnership with CDLs own scoped WPs.  Further discussion will need to take place with Mimas to brief them on the same set of work.  Both of JISC's Datacentres will be asked to tender for this innovation work to project manage it, and both datacentres must have clear guidance that this is an innovation project and not a service development until JISC can decide of its value to end users.

## Recommended next steps ##
These are only recommendations and NOT definitive decision for JISC, hence "recommendations" for how this work **might** proceed.

CDL has provide an estimate budget for what they think their share of the work will require.  Edina and Mimas must now need to be asked to tender for the set of work that will need to take place in collaboration with CDL.  For this process to occur with due diligence the following steps need to take place:

  1. DFF will write up a brief of this work for JH explaining its nature and purpose so that JH can submit this to HEFCE's system to register the budget line. RB must approve this as an activity prior to proceeding.
  1. DFF to introduce TR to CDL team (JS, PC, JK, GJ), alongside handover documents and notes.
  1. TR to brief Mimas in the same way as Edina was briefed explaining the project management role and responsibility (as per DFFs demo to TR during turnover mtg).
  1. TR to manage the bid process including closed bid marking.
  1. TR to further scope four WPs that are separate to the work of the core project, including:
    * WP1: Ensuring the bidding and project start-up process runs smoothly including any partnership concerns both internal to the project (CDL, Edina/Mimas, JISC) as well as external partners who will be interested in this work including the EU's FP7/Horizon work (Digoiduna), as well as partners such as DOI providers like the BL and URN providers such as the France National ISSN provider as the Western European libraries that manage URN resolvers.  Other overall partners that should be considered include OrcIDs and Amazon re ASINs.  There is also the possibility of other identifiers entering the marketplace, though these should be considered with the user users ability to choose in mind.
    * WP2: evaluation and analysis of the project and its adoption by the sector, this should include collecting analytics from the project on how often the home page is accessed, for long and how many links users click on the home page, the number of identifiers minted, basic tracking of the identifiers as they appear on the Web (to name just the bare minimum analytics data to be easily collected from the project and analysed by JISC).  Ideally, Google Analytics can be put in place and shared with TR so he can monitor it remotely without having to request analytics reports.  As part of this WP, several users should be contacted and interviewed asking them about their experience with the service, this should also be done by the core project team so this work should naturally overlap with testing of the product.  In coordination with WP3 should be the active analyses of the sector for the best way to market and disseminate this service within institutions for further use, that is IF and ONLY IF this WP that evaluates the service sees the continuation of this product as viable.  This WP should primarily be focused on delivering an evaluation report for JISC to consider in terms of longer term investment once the product has been launched and is being beta tested with a set of users accross three or more Universities and/or Colleges.
    * WP3: Building on WP2 is this workpackage which must come up with a marketing strategy for how this work should be taken forward.  This WP should only be considered if WP2 is able to provide amble data on the valued use of the service by end users.  Partners that should be considered for this work are JISC Advanced in partnership with the Datacentre that manages the project.  It is significant that JISC is moving towards a more centralised provision whereby closer working relationships between Edina, Mimas, Advanced and other JISC "Services" are more closely related to one another as "departments" in the same organisation whose remit is very specific in terms of what support they can provide as part of a centralised JISC.
    * WP4: Based on the success of WP2 and WP3 should be this final WP which will evaluate the liklihood of building further international infrastructure componets in partnership with likeminded organisation.  This WP should be an internal private WP between JISC and CDL to asses the economic business model of EZID and how it might be further sustained.  This economic analysis should include examining the project's local success in both the UK and CA and seeing how it fits in those institutions.  In addition,  JISC has an Economics advisor to help analyse the micro and macro investment opportunities that CDL and JISC might further build upon.  This WP while dependent that the previous WPs are successful should (none the less) be pursued from the start of the project to assure that economic data is being collected from the start.

The achievement of all four of these WPs should be an established service, however JISC has the right to end this innovation project at any time and make no guarantees as to its status as a service or continued investment.

## Estimate timeline for this work (DRAFT) ##
The following is only an estimate and NO GUARANTEES should be made for either it accuracy nor for the funding itself (JISC itself is subject to it budgets being passed down from HEFCE and this is not ever definitive until the Grant letter has been written, sign and paid).
  * Jan: TR to brief Mimas in the same way that Edina was briefed for this work explaining the role and nature of the work.
  * Feb: Project Plan (Bids) are submitted to JISC for an internal Closed ITT Marking Panel.
  * March: Project starts, initial meeting (videoconference?) between CDL and JISC+(EDINA/MIMAS) occurs to agree working activity, including governance and payment methods.
  * April: Use cases for EZID(uk) are published by the Project Manager and agreed by the governance structure.
  * May: Alpha development prototype
  * June-Aug: Beta development and readiness to test on 3+ Universities and/or Colleges.
  * Sept: Testing with product control group.
  * Oct: revision and addition of new features.
  * Nov-Dec: JISC draft report on value of service based on analytics usage and sector interviews with users.
  * Jan 2012: (potential) F2F meeting with JISC and CDL to discuss WP4 re viability and likelihood of building international infrastructure.
  * Further scoping... TBC /dff


[1](1.md)= for example, if n2t.net failed as a service and the URLs went error 404, the identifiers within the namespace of n2t would still be resolvable because of the Cool URIs status of the URLs, e.g. http://n2t.net/urn/issn/1234567890123 <-- the information in this URL could be looked up via the URN resolvers held at national libraries.  In short EZID turns PIDs into "Cool URIs".