---
layout: guidelines
---

# Software Assessment Guidelines #

**In Draft 5/15/2016**

## Abstract ##


## Goals of this Document ##


- To provide a basis for assessment guidelines that are effective and actionable both during active development and maintenance phases of research projects.
- To provide assessment guidelines to support different research group stages [ALSO NOT GREAT].
- To provide assessment guidelines effective for a range of stakeholders, from funders to individual researchers.
- To develop guidelines structured to reflect good code practices [THIS PHRASE IS NOT GREAT] and incorporating features related to research code requirements.


## HEADER TO COME ##


### Use Cases ###


Stakeholder | Use Case
----------- | --------
Funder | As a funding agency, we're interested in evaluating the software projects we fund.  
Project Manager, Principal Investigator (manager in practice) | As a manager, I’m interested in using the rubric/progression as a learning tool to help improve the development practices in my research group.
Principal Investigator | As a PI, I would like a tool to assess our progress and ensure we’re meeting our funder’s expectations for a software project based on the readiness level stated in the original proposal and as defined by the funder.
Science Software Developer, Researcher Who Codes | As a science software developer, I’m interested in using the recommended practices to improve my own workflow and skillsets.
Developer | As a developer, I would like community-supported guidelines to support requests to change our current dev team practices.
Grad Student, Post-Doc, Researcher interested in continuing code education | I’ve taken the introductory courses and want to continue to improve my skills but don’t know good next steps. I’d like guidance on next steps given my skillset.
Research Community | We want to provide educational materials or other support for community members to meet their goals re: research software implementation and career growth.


### What Are We Assessing ###


### What We Can't Assess ###

This section contains discussions concerning practices that we consider important to the implementation and sustainability of research software but that are difficult or impossible to assess by external means. 

[Examples of practices that are recommended but leave little to no trace for assessment.]



## Guidelines ##

[Reference and note for the descriptions of the bins and which ones are added for this doc.]

These guidelines are based on the criteria developed by the Software Sustainability Institute [REF], [other info], and feedback based on several ESIP activities. 

[Brief description of the development of these guidelines through ESIP, EarthCube, LASP, BESSIG]

The guidelines described in this document are, in large part, based on previous work by the Software Sustainability Institute and the Technology Assessment Framework (J. Greybeal as an ESIP Testbed grant). 

For new catergories or concepts, we believe that is important to include criteria here, even if the concept is not fully captured. ---something about starting places, living document, important to make those visible, if you will, so that they can be discussed and improved on.


- revisions for currentness and to reflect ESIP's goals related to education and mentorship
- revisions for composability: for encouraging change over time (replace smaller component with newer definitions) and to more explicitly define criteria for understandability and educational purposes. & for defining progressions.
- revisions for assessment metrics: clarify the application of the guidelines for the identified areas (project types, project or codebase, etc) for ease of use during the assessment process.


[Define the ESIP Core requirements]

[Define the binning, etc]

**The Draft Process**

For criteria categorized as "Other", all received criteria are included, as is, during the initial round. De-duplication, in those categories and across existing categories, is expected throughout the revision process.


<h4>Table of Contents</h4>
<ul>
    <li><a href="#fitness">Fitness</a>
        <ul>
            <li><a href="#fitness-accuracy">Accuracy</a></li>
            <li><a href="#fitness-credibilty">Credibility</a></li>
        </ul>
    </li>
    <li><a href="#sustainability">Sustainability &amp; Maintenance</a>
        <ul>
            <li><a href="#sustainability-copyright">Copyright</a></li>
            <li><a href="#sustainability-accessibility">Accessibility</a></li>
            <li><a href="#sustainability-analysability">Analysability</a></li>
            <li><a href="#sustainability-changeability">Changeability</a></li>
            <li><a href="#sustainability-community">Community</a></li>
            <li><a href="#sustainability-evolvability">Evolvability</a></li>
            <li><a href="#sustainability-governance">Governance</a></li>
            <li><a href="#sustainability-identity">Identity</a></li>
            <li><a href="#sustainability-interoperability">Interoperability</a></li>
            <li><a href="#sustainability-licensing">Licensing</a></li>
            <li><a href="#sustainability-portability">Portability</a></li>
            <li><a href="#sustainability-supportability">Supportability</a></li>
            <li><a href="#sustainability-testability">Testability</a></li>
        </ul>
    </li>
    <li><a href="#usabilty">Usability</a>
        <ul>
            <li><a href="#usability-buildability">Buildability</a></li>
            <li><a href="#usability-documentation">Documentation</a></li>
            <li><a href="#usability-friendliness">Friendliness</a></li>
            <li><a href="#usability-installability">Installability</a></li>
            <li><a href="#usability-learnability">Learnability</a></li>
            <li><a href="#usability-understandability">Understandability</a></li>
        </ul>
    </li>
    <li><a href="#other">Other</a>
        <ul>
            <li><a href="#other-security">Security</a></li>
            <li><a href="#other-preservation">Preservation &amp; Archiving</a></li>
            <li><a href="#other-credit">Credit</a></li>
        </ul>
    </li>
</ul>

<div class="guidelines">
    <h2>About the layout</h2>
    <p></p>

    <h4>Criteria Options</h4>
    <div class="revisions">
        <p class="original">The original statement.</p>
        <p class="original questioned"><i class="fa fa-warning fa-fw"></i>The original statement, flagged for review.</p>
        <p class="revision"><i class="fa fa-pencil fa-fw"></i>Suggested revisions to the original statement or a replacement for the original. The original statement is provided for reference.</p>
        <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Suggested new statement.</p>
        <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Suggested revision is to delete the statement entirely.</p>
    </div>

    <h4>Criteria Descriptors</h4>
    <p>The descriptors provide additional context for the criterion if applicable.</p>
    <p><span>Application:</span> indicates whether a statement refers to only the codebase, the project as a whole (generally relates to project artifacts not part of the codebase such as a project website), or applies to both.</p>
    <p><span>Grouping:</span> describes a logical grouping to the criteria within a subcategory.</p>
    <p><span>Notes:</span> any notes provided by the initial reviewers regarding suggested revisions.</p>
    <p><span>References:</span> link to a citation providing a rationale for the criterion.</p>
    <p><span>Similar Criteria:</span> links to criteria listed in other subcategories that may be duplicated concepts.</p>
    

    <h2 id="fitness">Fitness</h2>
    <h3 id="fitness-accuracy">Accuracy</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Tests exist to evaluate whether the results match the specification.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">The precision presented in answers to the user is appropriate for the product's algorithm and implementation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">The product produces the same results in response to the same inputs (unless specification calls for randomness).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">The product results are unaffected by increasing levels of use, analyzed inputs, or generated outputs; consistent with likely future demand.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">The specific results provided by the product match what the specification calls for.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">There are examples of outputs that follow the specification.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">There is a specification of the algorithm against which results can be compared.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Fitness: Accuracy -->

    <h3 id="fitness-credibility">Credibility</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">All web interfaces use secure (https) protocol</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Any group access privileges or functions are supported through group membership, not through group login via a single account.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Expertise of the originators of the project/product is represented throughout the content as appropriate (e.g., in author pages, references, citations, and about or background pages).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Opinions and perspectives are offered only as they relate to the mission of the project, and are clearly identified and put into context.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Presented information and data are consistent throughout the project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Re-authentication (e.g., on lost password) requires appropriate verification (e.g., email to known account, or 2-factor authentication; not security questions).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">The product user experience (e.g, response times) is materially unaffected by increasing levels of use, analyzed inputs, or generated outputs; consistent with user expectations.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">User can access all appropriate capabilities and information, but can not access any content or feature that should be privileged.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Where registration is allowed, registration validation is consistent with required project security (e.g., simple captcha for insecure public-facing resources; email required for mildly resource-constrained software; manual identity verification for critical products)</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div> 
    </div> <!-- end Fitness: Credibility -->

    <h2 id="sustainability">Sustainability and Maintenance</h2>
    <h3 id="sustainability-copyright">Copyright</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Each source code file/web page/document has a copyright statement.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">If supported by the language, each source code file has a copyright statement embedded within a constant.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">If there are multiple web sites then these all state exactly the same copyright, licencing and authorship.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site states copyright.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site states key roles: who developed/develops the product, funds it, oversees the web site, etc.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Sustainability:Copyright-->

    <h3 id="sustainability-accessibility">Accessibility</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Ability to browse source code repository online.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Access to source code repository is available (whether for free, payment, registration).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Anonymous read-only access to source code repository.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Binary distributions are available (whether for free, payment, registration).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Binary distributions are available without the need for any registration or authorisation of access by the project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Binary distributions are freely available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Downloads/versions page shows evidence of regular releases (e.g. six monthly, bi-weekly, etc.).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Repository is hosted externally to a single organisation/institution in a sustainable third-party repository (e.g. SourceForge, GoogleCode, LaunchPad, GitHub) which will live beyond the lifetime of any current funding line.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source distributions are available (whether for free, payment, registration).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source distributions are available without the need for any registration or authorisation of access by the project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source distributions are freely available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Sustainability: Accessibility -->

    <h3 id="sustainability-analysability">Analysability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code is commented.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code is laid out and indented well.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code or content is structured into modules or packages.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code uses sensible class, package and variable names.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">There are no TODOs in the code.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">There is no commented out code.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">There are no old source code files that should be handled by version control e.g. “SomeComponentOld.java”.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Coding standards are recommended by the project.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Coding standards, for each programming language used, are recommended by the project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Standardized Code</p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Coding standards are required to be observed.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Standardized Code</p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project-specific coding standards are consistent with community or generic coding standards (e.g. for C, Java, FORTRAN, Python, Ruby, etc.)</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Standardized Code</p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Coding standards are verified using a linter (should one be available for the given programming language).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Standardized Code</p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Styleguides are provided for the project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Standardized Code</p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code comments are written in an API document generation mark-up language e.g. JavaDoc or Doxygen.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Document Generation</p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project documentation identifies the API generation tool used.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Document Generation</p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project documentation describes how to regenerate the documentation</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Document Generation</p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project uses automated documentation generation tool, e.g. Swagger or RAML.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Document Generation</p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code or content repository is a revision control system.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Source code or content repository is managed through a version control system.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source or content releases are snapshots of the repository.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Releases follow protocols of the version control system in place.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Tagged Git releases, etc.</p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Auto-generated source code is in separate directories from other source code.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Revisit depending on portability/buildability revisions</p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>How to regenerate the auto-generated source code is documented.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Revisit depending on portability/buildability revisions</p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Project files for IDEs are provided.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Revisit depending on portability/buildability revisions</p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        
        
        
        
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code structure relates clearly to the architecture or design.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        
        <div class="criterion">
            <div class="revisions">
                <p class="original">Structure of the source code or content repository and how this maps to the software’s components is documented.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Sustainability:Analysability-->

    <h3 id="sustainability-changeability">Changeability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Changes in the source code repository are e-mailed to a mailing list.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Contributions policy is publicly available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Contributors retain copyright/IP of their contributions.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has defined a contributions policy.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has defined a stability/deprecation policy for components, APIs, pages, etc.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Releases document deprecated components/APIs in that release.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Releases document removed/changed components/APIs in that release.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Stability/deprecation policy is publicly available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">This e-mailing list can be subscribed to by anyone.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Users, user-developers and developers who are not project members can contribute.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Sustainability:Changeability-->

    <h3 id="sustainability-community">Community</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Developers exist who are not members of the project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Users are requested to cite the product if publishing papers based on results derived from the product.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Users are required to cite a boilerplate citation if publishing papers based on results derived from the product.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Users exist who are not members of the project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has list of important partners and collaborators.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has list of software that uses/bundles this product, or sites that reference this work.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has list of the project’s publications.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has list of third-party publications that cite the product.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has quotes from satisfied users.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has statement of number of users/developers/members.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has success stories.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Sustainability:Community -->

    <h3 id="sustainability-evolvability">Evolvability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site describes end dates of current funding lines.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site describes how project is funded/sustained.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site describes project roadmap or plans or milestones (either on a web page or within a ticketing system).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Sustainability:Evolvability-->

    <h3 id="sustainability-governance">Governance</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Governance policy is publicly available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has defined a governance policy.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>

    </div> <!-- end Sustainability:Governance -->

    <h3 id="sustainability-identity">Identity</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software has a distinct name regardless of its application area. A search by Google on the name plus keywords from the application area throws up the project web site in the first page of matches.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software has a distinct name within its application area. A search by Google on the name plus keywords from the application area throws up the project web site in the first page of matches.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software has a logo.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software has its own domain name.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software name does not throw up embarrassing “did you mean…” hits on Google.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software name does not violate an existing trade-mark.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software name is trade-marked.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Sustainability:Identity -->

    <h3 id="sustainability-interoperability">Interoperability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Provides tests demonstrating compliance to open standards.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Uses mature, ratified, non-draft open standards.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Uses open standards.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Sustainability:Interoperability -->

    <h3 id="sustainability-licensing">Licensing</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Each source code file or document has a licence header; each web page has a rights and authorship footer.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Site or product content has a 'free for public use' license or statement.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Site or product content has a license.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Software (source and binaries) has a licence.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Software has an Open Software Initiative (OSI) recognised licence.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Software has an open source licence.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site states applicable licences.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Sustainability:Licensing -->

    <h3 id="sustainability-portability">Portability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Application can be built on and run under Debian.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Application can be built on and run under Fedora.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Application can be built on and run under MacOSX.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Application can be built on and run under RedHat.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Application can be built on and run under Solaris.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Application can be built on and run under Ubuntu.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Application can be built on and run under UNIX/Linux.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Application can be built on and run under Windows 7.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Application can be built on and run under Windows Vista.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Application can be built on and run under Windows XP.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Application can be built on and run under Windows.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Browser applications/sites run under Google Chrome.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Browser applications/sites run under Internet Explorer.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Browser applications/sites run under Mozilla Firefox.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Browser applications/sites run under Opera.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Browser applications/sites run under Safari.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Sustainability:Portability-->

    <h3 id="sustainability-supportability">Supportability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Above pages/windows/files describe, or link to, a description of “how to ask for help” e.g. cite version number, send transcript, error logs etc.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">E-mail archives are publicly readable.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">E-mail archives are searchable.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">E-mail archives or ticketing system shows that queries are responded to within a week (not necessarily fixed, but at least looked at and a decision taken as to their priority).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">E-mail lists or forums, if present, have regular posts.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">E-mails are archived.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">E-mails are read by more than one person.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">If there is a blog, is it is regularly used.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project e-mail address has project domain name.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has a ticketing system.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has an e-mail address.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project resources are hosted externally to a single-organisation/institution in a sustainable third-party repository (e.g. SourceForge, GoogleCode, LaunchPad, GitHub) which will live beyond the lifetime of the current project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Software describes how to get support (in a README for command-line tools or a Help=>About window in a GUI).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Ticketing system is publicly readable.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Ticketing system is searchable.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">User doc has page describing how to get support.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has page describing how to get support.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has search facility.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has site map or index.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Sustainability:Supportability-->

    <h3 id="sustainability-testability">Testability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">A minimum test coverage level that must be met has been defined.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Continuous integration is supported – tests are automatically run whenever the source code changes.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">For GUIs, project uses automated GUI test frameworks.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has automated tests to check conformance to coding standards.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has automated tests to check test coverage.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has integration tests.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has scripts for testing scenarios that have not been automated (e.g. for testing GUIs).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has unit tests.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project recommends tools to check conformance to coding standards.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project recommends tools to check test coverage.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project specifies how to set up external resources e.g. FTP servers, databases for tests.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Test results are e-mailed to a mailing list.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Test results are visible publicly.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Test results are visible to all developers/members.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Tests are automatically run nightly.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Tests create their configuration own files, database tables etc.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">There is an automated test for this minimum test coverage level.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">This e-mailing list can be subscribed to by anyone.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Sustainability:Testability-->

    <h2 id="usability">Usability</h2>
    <h3 id="usability-buildability">Buildability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">All mandatory third-party dependencies or external references are currently available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">All optional third-party dependencies or external references are currently available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">An automated build (e.g. Make, ANT, custom solution) is used to build any software.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Dependency management is used to automatically download dependencies (e.g. ANT, Ivy, Maven or custom solution).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source distributions have instructions for building corresponding software.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source distributions list all third-party dependencies that are not bundled, along with web addresses, suitable versions, licences and whether these are mandatory or optional.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Tests are provided to verify the build or distribution has succeeded, or service/information is presented as intended.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has instructions for building the product.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site lists all third-party dependencies that are not bundled, along with web addresses, suitable versions, licences and whether these are mandatory or optional.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Usability:Buildability -->

    <h3 id="usability-documentation">Documentation</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">API documentation is autogenerated (e.g., by JavaDoc or Doxygen), and documents APIs completely (e.g., configuration files, property names, etc.).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Consists of clear, step-by-step instructions for use or adoption.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Documentation is held under version control alongside any code or other product components.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Documentation is on the project web site.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>A link to the documentation is contained in the code.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Code and documentation can be separated.</p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Documentation on the project web site makes it clear what version of the product the documentation applies to.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Does not use terms like “intuitive”, “user friendly”, “easy to use”, “simple” or “obviously”, unless as part of quotes from satisfied users.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">English language descriptions of commands and errors are provided but only to complement the above.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">For common problems and error messages, the symptoms and step-by-step solutions are provided.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Documentation is updated to reflect new errors and resolution methods identified.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>New errors and resolutions can be identified over time.</p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>For software, a best-practice guideline is selected and code is validated against it.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>What does this mean? Do you mean -- For software, use industry best practices for a given language or platform and then validate that the code meets those practices (i.e., a third party code review).</p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Further information is suitable for the level of the reader, for each class of user.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Explanations should be free of jargon.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Users can have diverse experiences.</p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Gives examples of what the user can see at each step, e.g., screen shots or command-line excerpts; installation outcomes; working examples and error examples.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Is task-oriented or objective-oriented.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Lists resources for further information.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Partitioned into sections for users, user-developers and developers (depending on the software).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Plain-text files (e.g. READMEs) use indentation and underlining (e.g. === and ---) to structure the text, and avoid TAB character indentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Provides a high-level overview of the product.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">States assumed background and expertise of the reader, for each class of user.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">States command names and syntax, says what menus to use, lists parameters and error messages exactly as they appear or should be typed; or provides similarly explicit instructions on how to apply product.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Uses teletype-style fonts for command line inputs and outputs, source code fragments, function names, class names etc.; uses appropriately styled fonts for key information and special terms or links.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Constraints or restrictions are included in the documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Quality control information is included in the documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Usability:Documentation-->

    <h3 id="usability-friendliness">Friendliness</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">All essential options and information for a task are visible, while excess information is avoided. Display elements are easily distinguished, and tool tips provided. Possible and impossible actions are indicated.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Display handles variety of scales, including mobile phone size if that is targeted, while allowing user ready access to needed controls.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Generated data products are organized clearly, with embedded metadata wherever possible.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Lists of resources are neatly presented for easy access, comparison, access to details, and handling of scale. Both filter and scrolling are available; user can control number of items presented.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Simple and common tasks are easy to perform and communicated clearly and simply in the user's reference frame. The product minimizes the effort for users, by making appropriate assumptions, presenting appropriate defaults, and offering appropriate short-cuts.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">System can be controlled or used by foreign speakers and color-vision-deficient individuals.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Terminology used throughout the system or product is internally consistent, appropriate to the context, and suitable for targeted users, avoiding codes unless universally known.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">User commands are quickly and intuitively reflected in system behavior and subsequent system presentation (e.g., previous filters remain visible).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">User intefaces maintain consistent patterns of behavior and style (e.g., buttons and cancel/save exits have consistent look and feel), creating an understandable presentation throughout the application.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">User interfaces are organized in meaningful and useful ways that are recognizable to users.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">User mistakes are tolerated gracefully; multiple levels of "command undo" are provided, paths to 'go back' are available, irreversible actions are rare but verified if needed, and suggestions are offered in response to faulty input.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">User variation is handled automatically; varying sequences and input formats are handled, and reasonable actions are accepted.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Users are informed of relevant software actions, state changes, errors, and assumptions in clear and simple ways.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Usability:Friendliness -->

    <h3 id="usability-installability">Installability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">All GUIs contain a Help menu with commands to see the project name, web site, how/where to get help, version, date, licence and copyright (or where to find this information), location of entry point into user doc.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">All mandatory third-party dependencies or external references are currently available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">All optional third-party dependencies or external references are currently available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">All other content distributed as an archive contains a README.TXT with project name, web site, nature, how /where to get help, version, and date.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">All source and binary distributions contain a README.TXT with project name, web site, how/where to get help, version, date, licence and copyright (or where to find this information), location of entry point into user doc.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Binary distributions have instructions for installing the product.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Binary distributions list all third-party dependencies and external references that are not bundled, along with (as appropriate) web addresses, suitable versions, licences and whether these are mandatory or optional.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Dependency management is used to automatically download dependencies (e.g. ANT, Ivy, Maven or custom solution).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Installers allow user to select where to install software.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Tests are provided (or silently performed) to verify the install has succeeded or service/product is fully available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Uninstallers exist, and uninstall every file or warns user of any files that were not removed and where these are.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has instructions for installing or accessing the product.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site lists all third-party dependencies and external references that are not bundled, along with (as appropriate) web addresses, suitable versions, licences and whether these are mandatory or optional.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">When an archive (e.g. TAR.GZ or ZIP) is unpacked, it creates a single directory with the files within. It does not spread its contents all over the current directory.  </p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">When software is installed, or when a product or service has multiple facets, its contents are organised into sub-directories (e.g. docs for documentation, libs for dependent libraries) or IRL hierarchies (/about, /support, etc.) as appropriate.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Usability:Installabilty-->

    <h3 id="usability-learnability">Learnability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">A getting started guide is provided outlining a basic example of using the product.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">API documentation is provided for userdevelopers and developers.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Instructions are provided for many basic use cases.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Instructions are provided supporting all use cases.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Reference guides or contextual specifications (may be simple labels, if clear) are provided for all command line, GUI and configuration options.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Usability:Learnability-->

    <h3 id="usability-understandability">Understandability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Architectural overview, with diagrams, is available.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Architectural overview, with diagrams, is included or referenced in the documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Case studies of use are available.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Case studies of use are included or referenced in the documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Descriptions of intended use cases are available.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Descriptions of intended use cases are included or referenced in the documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Design rationale is available – why the system does things the way it does.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Design rationale is included or referenced in the documentation – why the system does things the way it does.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">High-level description of how the product works is available.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>High-level description of how the product works is included or referenced in the documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">High-level description of what the product does is available.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>High-level description of what the product does is included or referenced in the documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">High-level description of what/who the product is for is available.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>High-level description of what/who the product is for is included or referenced in the documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Constraints or restrictions are archived with the source code.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>HConstraints or restrictions are included or referenced in the documentation and archived with the source code.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Usability:Understandability -->

    <h2 id="other">Other</h2>

    <h3 id="other-security">Security</h3>
    <div class="criteria">

    </div> <!-- end Security -->

    <h3 id="other-preservation">Preservation/Archiving</h3>
    <div class="criteria">
        <!-- downs -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Source code used to create data are archived with the data or separately with bidirectional references between the data and software.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Source code developed for accessing or using the data are archived with the data or separately with bidirectional references between the data and software.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Documentation are archived with the source code.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Licenses are archived with the source code.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Constraints or restrictions are archived with the source code.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>

        <!-- toner -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Document describing known environment in which code was originally run</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>List known dependencies</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>consider container technologies to ensure reproducibility of software content or function.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>documentation describing objectives of software, known limitations or bugs, and reason for and purpose of its existence</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Ideally, preserved/archived code should include "test data", so future users can unpack and run code, and see if results appear as expected. (Unless data is already archived elsewhere)</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Code should be documented in a natural language explaining each process/code section.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>(In some cases, preserving code for reuse is impossible, but being able to refer back to old code and follow it without needing to know intimately the language it was written in is helpful.)</p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Archived code should not be an executable (.exe) but a group of files packaged together that can be built or reviewed by future users for understanding. Code should be as self-contained as possible.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Does the software use open source platforms and libraries, or does it require the use of licensed software?</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Copyright/licensing must be noted and made clear to future users. </p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Copyright/licensing must be noted and made clear to future users. </p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Archived code should include any documentation that applies to the particular release of the code--including both specific version documentation and overall software documentation. </p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>(Resources enabling "usability" of code also apply to future users acquiring code from the archive.)</p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Preservation -->

    <h3 id="other-credit">Publication &amp; Credit</h3>
    <div class="criteria">
        <!-- downs -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Authors of software are identied in the suggested citation for the software.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Substantial contributions to software are considered authorship.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Other contributions to software are acknowledged in documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Authors of documentation are identified in the suggested citation for the documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Software used to create data are cited in the data documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Data for which the software were created are cited in the software documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Review committees consider and recognize software contributions and citations of software.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Publications about the data cite the software used to create the data.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Publications about the use of the data cite the software used to analyze the data.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
    </div> <!-- end Credit -->
</div> <!-- end guidelines-->


## Participants ##


## References ##




