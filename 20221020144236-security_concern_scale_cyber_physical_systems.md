# 20221020144236-security_concern_scale_cyber_physical_systems
#hcps #cyber-physical-systems #security #scale-development #methods

## Broad goal

We want to develop a general survey scale that can assess the extent to which
a lay person is concerned about the security of a cyber physical system. This
scale should be able to be applied generally across different cyber physical
systems, such that asking the same questions in regards to different systems
will give a measurement of concern for each system.

## Approach

The general approach to developing a scale of security concern for cyber
physical systems will be the following: (i) assess what's been done in past
research, (ii) identify the important constructs that will make up the
measurement of "security concern", (iii) develop survey questions that will
reveal each of those constructs, and (iv) collect data to validate the
connection between the questions and their intended constructs, as well as
validating that our measurement of security concern predicts other constructs
in ways that would be expected (eg, negatively predict willingness to adopt
the technology). See below for more detail on each point.


### Gather previous research

In progress. We want past research dealing with:

* Scales for measuring security concerns in other domains
* People's intuitions about what security best practices are
    * We're especially interested in their *wrong* intuitions
    * Could pilot test for this point if there's not much previous research
        * See [[20220919144842-mental_model_analogies_cyber_security.md]] for
            discussion of people's understanding of technology and the
            security risks associated with it.
* The actual types of harm that can come from an attack on CPS's generally.
	* See [[cps attack harm]] (still in development).

### Identify important constructs

(under development)

**Core constructs**

The following are core, independent constructs that make up the overall construct
we're interested in measuring (ie, security concern):

* Consequences
    * What are the perceived consequences of a security breach?
* Agency
    * In what ways does the individual perceive that their actions will
        influence the likelihood of a security breach?
* Responsibility
    * Perceived responsibility of a security breach.
    * Same thing as blame?
* Likelihood of security breach
    * Perceived likelihood that CPS security will be breached generally.
    * Perceived likelihood that CPS security will be breached personally.
        * ie, that it will happen to "me".

**Interesting independent variables**

This section might be less related to scale development *per se* but rather
related to interesting hypotheses that can be tested once a reliable scale of
CPS security concern is developed:

* Individual / collective
    * Does security concern vary in interesting ways depending on whether the
        risk is characterized more at an individual level (eg, a personal
        smart car) vs. a collective level (eg, a communal smart train).
* Familiarity
    * Does the extent to which one has familiarity with a type of system or
        technology predict their level of concern? 
    * For example, might people have different intuitions about security risks
        for smart cars vs. the electric grid because of greater familiarity with cars
        generally than with the mechanisms of smart grid
        operation?
* Priming
    * Will people's security concerns differ depending on which aspects of the
        CPS are highlighted or primed?
    * For example, when soliciting security concerns about smart cars, people
        could first be cued with information either about computers (to make
        salient the technology component of the smart car) or about cars
        generally (to make salient the automobile component of the smart car).

**Possible covariates**

Same caveat as last section: this section might be more relevant to testing
interesting hypotheses once a scale has been developed.

What are important characteristics of individuals that we'd want to understand
or control for when thinking about people's intuitions about CPS security
concerns? Possibilities include:

* Current security practices
    * Is the individual vigilant in their security practices generally? Will
        security intuitions in one domain (eg, cyber security) be more likely
        to transfer to CPS than other domains (eg, general physical safety)?
    * See [[20220919144842-mental_model_analogies_cyber_security.md]] for a
        discussion of possible analogies that people use to understand risks
        around cyber systems.
* Usage of the technology
    * Does the extent to which a person uses the CPS influence their
        intuitions of its security? 
    * Related to familiarity. All those who use the technology should be
        familiar with it, but not necessarily vice versa.

### Develop survey items

Once we've covered past research and developed a final set of core constructs,
we will develop survey items specific to each core construct. For example, if
"agency" is a core construct, we will develop a set of questions that should
reveal people's understanding of agency with respect to security concerns.

### Validate the scale

Once questions are developed, we will collect data and run statistical tests
designed to assess whether survey items cluster together in ways that we would
expect based on our organization of survey questions and core constructs.

Once question responses seem to be grouping in ways that we would expect, we
can test whether the scale of security concern predicts other factors that we
might expect it to. For example, we would expect security concerns to
negatively predict willingness to adopt the CPS into one's life.

**Related notes:**
* [[20221019152229-cyber_physical_systems.md]]
* [[20220920101902-human_security_CPS.md]]
