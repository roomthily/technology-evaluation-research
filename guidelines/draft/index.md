---
layout: guidelines
---

# Draft Software Assessment Guidelines #

<div class="feedback">
<p>Comments and feedback are encouraged until <strong>July 8, 2016</strong>. </p>
<p>To comment, please use one of the following options, in oreder of preference:</p>
<ol>
    <li>Comment directly on this page using the <a href="https://hypothes.is/">Hypothes.is</a> annotation system.</li>
    <li>Create an issue in <a href="https://github.com/roomthily/technology-evaluation-research/issues">GitHub</a>.</li>
    <li>Submit a pull request to the <code>gh-pages</code> branch in this <a href="https://github.com/roomthily/technology-evaluation-research/">repository</a>. Information on the structure is <a href="{{ site.baseurl }}/guidelines/contributing">available</a>. (This is not the preferred option.)</li>
</ol>
</div>

## Abstract ##


## Goals of this Document ##


- To provide a basis for assessment guidelines that are effective and actionable both during active development and maintenance phases of research projects.
- To provide assessment guidelines to support different research group stages [ALSO NOT GREAT].
- To provide assessment guidelines effective for a range of stakeholders, from funders to individual researchers.
- To develop guidelines structured to reflect good code practices [THIS PHRASE IS NOT GREAT] and incorporating features related to research code requirements.


## Background ##


### Use Cases ###

The guidelines presented in this document 

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

[Brief description of the development of these guidelines through ESIP, EarthCube, LASP, BESSIG]

The guidelines described in this document are, in large part, based on previous work by the Software Sustainability Institute and the Technology Assessment Framework (J. Greybeal as an ESIP Testbed grant). 

The subcategories are taken from the ISO 9126 [REF] and definitions are provided [here]({{ site.baseurl }}/guidelines/categories).

For new catergories or concepts, we believe that is important to include criteria here, even if the concept is not fully captured. ---something about starting places, living document, important to make those visible, if you will, so that they can be discussed and improved on.


- revisions for currentness and to reflect ESIP's goals related to education and mentorship
- revisions for composability: for encouraging change over time (replace smaller component with newer definitions) and to more explicitly define criteria for understandability and educational purposes. & for defining progressions.
- revisions for assessment metrics: clarify the application of the guidelines for the identified areas (project types, project or codebase, etc) for ease of use during the assessment process.


[Define the ESIP Core requirements]

[Define the binning, etc]

**The Draft Process**

For criteria categorized as "Other", all received criteria are included, as is, during the initial round. De-duplication, in those categories and across existing categories, is expected throughout the revision process.

**Ed. note: consider the about-to-be-published software citation principles for some areas defined here. Do the criteria align with the general principles identified by the community?**


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
            <li><a href="#other-performance">Performance</a></li>
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
    <p><span>Notes:</span> any notes provided by he initial reviewers regarding suggested revisions.</p>
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
                <h4>Application</h4>
                <p>Algorithm | Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">The precision presented in answers to the user is appropriate for the product's algorithm and implementation.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Algorithm | Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">The product produces the same results in response to the same inputs (unless specification calls for randomness).</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Algorithm | Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">The product results are unaffected by increasing levels of use, analyzed inputs, or generated outputs; consistent with likely future demand.</p>
            </div>
            <div class="metadata">
               <h4>Application</h4>
                <p>Algorithm | Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">The specific results provided by the product match what the specification calls for.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Algorithm | Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">There are examples of outputs that follow the specification.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Algorithm | Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">There is a specification of the algorithm against which results can be compared.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Algorithm | Code</p>
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
                <h4>Notes</h4>
                <p>Unclear application - project website or web application (the project's deliverable) in which case, is it better placed under Security?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Any group access privileges or functions are supported through group membership, not through group login via a single account.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Auth and Access</p>
                <h4>Notes</h4>
                <p>Move to Security? Update to better reflect roles, groups, etc, terminology.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Expertise of the originators of the project/product is represented throughout the content as appropriate (e.g., in author pages, references, citations, and about or background pages).</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Opinions and perspectives are offered only as they relate to the mission of the project, and are clearly identified and put into context.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Presented information and data are consistent throughout the project.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Re-authentication (e.g., on lost password) requires appropriate verification (e.g., email to known account, or 2-factor authentication; not security questions).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Auth and Access</p>
                <h4>Notes</h4>
                <p>Move to Security? Wordsmith a bit?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">The product user experience (e.g, response times) is materially unaffected by increasing levels of use, analyzed inputs, or generated outputs; consistent with user expectations.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">User can access all appropriate capabilities and information, but can not access any content or feature that should be privileged.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Auth and Access</p>
                <h4>Notes</h4>
                <p>Move to Security? Add statement re: testing the roles, etc. Possibly consideration some statement on 3rd party integrations?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Where registration is allowed, registration validation is consistent with required project security (e.g., simple captcha for insecure public-facing resources; email required for mildly resource-constrained software; manual identity verification for critical products)</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Auth and Access</p>
                <h4>Notes</h4>
                <p>Move to Security? wordsmith, at least.</p>
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
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">If supported by the language, each source code file has a copyright statement embedded within a constant.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">If there are multiple web sites then these all state exactly the same copyright, licencing and authorship.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site states copyright.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site states key roles: who developed/develops the product, funds it, oversees the web site, etc.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Sustainability:Copyright-->

    <h3 id="sustainability-accessibility">Accessibility</h3>
    <p>Ed. note: suggest revisions for three situations - 1) project members are hosting their own repository management system (git, Trac, etc) which does affect public/private access and browsability; 2) project members are using a third party DVCS like GitHub or BitBucket which affects public/private but other aspects are not directly tied to the *project* assessment; c) project members post their software repositories to a domain/research code system which is more related to publication and preservation (but still about whether the code is accessible).</p>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Ability to browse source code repository online.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Source Code</p>
                <h4>Notes</h4>
                <p>Realistically, could assume when hosting in external platform, ie GitHub, that this is a feature of the external system and not something to evaluate for the project itself.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Access to source code repository is available (whether for free, payment, registration).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Source Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Anonymous read-only access to source code repository.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Source Code</p>
                <h4>Notes</h4>
                <p>If kept, clarify language. The related flagged items read more as guidance to choose an external platform </p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Repository is hosted externally to a single organisation/institution in a sustainable third-party repository (e.g. SourceForge, GoogleCode, LaunchPad, GitHub) which will live beyond the lifetime of any current funding line.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>All repositories developed by the project team are hosted externally in a sustainable thrid-party platform, either a code-hosting platform or a domain- or research-specific software repository.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Source Code</p>
                <h4>Notes</h4>
                <p>Removing the platform names (too many are gone now) and including text for the newer domain area repositories (see Astronomy community efforts and some general research software repositories (OntoSoft)).</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source distributions are available (whether for free, payment, registration).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Source Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source distributions are available without the need for any registration or authorisation of access by the project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Source Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source distributions are freely available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Source Code</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Binary distributions are available (whether for free, payment, registration).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Artifacts</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Binary distributions are available without the need for any registration or authorisation of access by the project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Artifacts</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Binary distributions are freely available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Artifacts</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Downloads/versions page shows evidence of regular releases (e.g. six monthly, bi-weekly, etc.).</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>This seems out of place. Capture release scheduling under the larger Versioning umbrella. *If* releases needs to be under Accessibility, it needs to relate directly to the avaialability of the source code versions and the build artifacts.</p>
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
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code is laid out and indented well.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code or content is structured into modules or packages.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code uses sensible class, package and variable names.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">There are no TODOs in the code.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">There is no commented out code.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">There are no old source code files that should be handled by version control e.g. “SomeComponentOld.java”.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
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
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Coding standards are required to be observed.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Standardized Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project-specific coding standards are consistent with community or generic coding standards (e.g. for C, Java, FORTRAN, Python, Ruby, etc.)</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Standardized Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Coding standards are verified using a linter (should one be available for the given programming language).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Standardized Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Styleguides are provided for the project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Standardized Code</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code comments are written in an API document generation mark-up language e.g. JavaDoc or Doxygen.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Document Generation</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project documentation identifies the API generation tool used.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Document Generation</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project documentation describes how to regenerate the documentation</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Document Generation</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project uses automated documentation generation tool, e.g. Swagger or RAML.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Document Generation</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code or content repository is a revision control system.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Source code or content repository is managed through a version control system.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source or content releases are snapshots of the repository.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Releases follow protocols of the version control system in place.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Tagged Git releases, etc.</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Auto-generated source code is in separate directories from other source code.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Revisit depending on portability/buildability revisions</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>How to regenerate the auto-generated source code is documented.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Revisit depending on portability/buildability revisions</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Project files for IDEs are provided.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Revisit depending on portability/buildability revisions</p>
            </div>
        </div>
    
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code structure relates clearly to the architecture or design.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        
        <div class="criterion">
            <div class="revisions">
                <p class="original">Structure of the source code or content repository and how this maps to the software’s components is documented.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Sustainability:Analysability-->

    <h3 id="sustainability-changeability">Changeability</h3>
    <div class="criteria">
        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="original">Changes in the source code repository are e-mailed to a mailing list.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Changes to the source code repository are made available through some notification system, whether mailing list of ticketing system notifications.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Dev Transparency</p>
                <h4>Notes</h4>
                <p>Updated to reflect GitHub/BitBucket/Trac interactions ("watch" functionality).</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">This e-mailing list can be subscribed to by anyone.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Anyone can subscribe to the notification system providing software release updates.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Dev Transparency</p>
                <h4>Notes</h4>
                <p>Check for duplication in the ticketing system criteria.</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Contributions policy is publicly available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Contribution Policy</p>
                <h4>Notes</h4>
                <p>See also Governance (and shift to governance? to match FLOSS organizational conversations?)</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Contributors retain copyright/IP of their contributions.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Contribution Policy</p>
                <h4>Notes</h4>
                <p>If we're following the open source model, this is incorrect - Contributor License Agreements release the rights from the contributor back to the project. The original implies that someone could revoke permissions for their contribution to a project, which would have credibility/stability issues. </p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has defined a contributions policy.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Contribution Policy</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Users, user-developers and developers who are not project members can contribute.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Contribution policy is not limited to code contributions and describes processes for anyone to contribute to the project even if nt project members.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Contribution policy</p>
                <h4>Notes</h4>
                <p>(Not policy but maybe there should be a stronger section under community for explicitly stating non-project member options or under governance or is it implied by having a CONTRIBUTING statement?)</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has defined a stability/deprecation policy for components, APIs, pages, etc.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Change policies</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Releases document deprecated components/APIs in that release.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Change policies</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Releases document removed/changed components/APIs in that release.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Change policies</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>A release is accompanied by a change log document (or update to a CHANGELOG document), including deprecated or modified components/APIs.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Change policies</p>
                <h4>Notes</h4>
                <p>Merged the previous into one statement about change logs.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Stability/deprecation policy is publicly available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Change policies</p>
            </div>
        </div>
    </div> <!-- end Sustainability:Changeability-->

    <h3 id="sustainability-community">Community</h3>
    <div class="criteria">
        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Users are requested to cite the product if publishing papers based on results derived from the product.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Flagged for publication/credit binning</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Users are required to cite a boilerplate citation if publishing papers based on results derived from the product.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Flagged for publication/credit binning</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has list of important partners and collaborators.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Project in the wild</p>
                <h4>Notes</h4>
                <p>(Applies to any "Project in the wild") This hits project lifecycle concerns (most of these criteria are unlikely to be true for a project on its first grant round) so need to clarify *when* we expect to see these kinds of features. Also gets to Identity (esp. the parts tied to branding) and post-publication concerns which don't speak to community. Consider community around developing/actively using codebase and scholarly community as different criteria buckets?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has list of software that uses/bundles this product, or sites that reference this work.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Project in the wild</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has list of the project’s publications.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Project in the wild</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has list of third-party publications that cite the product.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Project in the wild</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has quotes from satisfied users.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Project in the wild</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has statement of number of users/developers/members.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Project in the wild</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has success stories.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Project in the wild</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Developers exist who are not members of the project.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Users exist who are not members of the project.</p>
            </div>
            <div class="metadata">
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
                <p>Funding/Sustainability</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site describes how project is funded/sustained.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Funding/Sustainability</p>
            </div>
        </div>
        
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site describes project roadmap or plans or milestones (either on a web page or within a ticketing system).</p>
            </div>
            <div class="metadata">
            </div>
        </div>

        <!-- kokkonen -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Web site describes software requirements on hardware, operating system versions, tool versions.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>(Check documentation for OS, 3rd party versions; wherever it winds up, a group for Hardware is a good idea (GPU-optimized code, etc)</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Software includes no arbitrary shutdown dates.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Consider a more general statement against global defaults or hard-coded defaults in the code base (we can provide examples of similar issues around default size limits, etc. Guidelines - limited use of globals, uses configuration files.</p>
            </div>
        </div>

        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>[Ed. note: some criteria related to reuse of OS frameworks, ie. not reinventing every wheel. This is a placeholder and reminder.]</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Reuse</p>
            </div>
        </div>
    </div> <!-- end Sustainability:Evolvability-->

    <h3 id="sustainability-governance">Governance</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has defined a governance policy.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Governance policy is publicly available.</p>
            </div>
            <div class="metadata">
            </div>
        </div>

        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project website or code repository contains documentation describing the contribution policies and procedures.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Contribution</p>
                <h4>Notes</h4>
                <p>Probably a repeated concept but currently comes up in FLOSS governance discussions, might just need to be shifted from various other sub-categories.</p>
                <h4>References</h4>
                <p><a href="#"></a>See "contributing Guidelines" ref.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Contribution policies and procedures included in a CONTRIBUTING file.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Contribution</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Contribution policies and procedures describes the code review process, including who performs the review, who accepts the reviews and how long reviews take.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Contribution</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Contribution policies and procedures clearly define decision making processes for all contributors.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Contribution</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project website or code repository includes a code of conduct.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Sustainability:Governance -->

    <h3 id="sustainability-identity">Identity</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software has a distinct name regardless of its application area. A search by Google on the name plus keywords from the application area throws up the project web site in the first page of matches.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Project/software name or acronym is distinct within the application area.</p>
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project/software name or acronym is easily discoverable, eg. the acronym is not a very common word or, if it is, the phrase provides additional information for discovery.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Branding</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software has a distinct name within its application area. A search by Google on the name plus keywords from the application area throws up the project web site in the first page of matches.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Branding</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software has a logo.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Branding</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software has its own domain name.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Basic</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Project/product/software name does not throw up embarrassing “did you mean…” hits on Google.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Maybe should just be a better guideline on naming? Three is a lot related to search?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software name does not violate an existing trade-mark.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Basic</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software name is trade-marked.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Advanced</p>
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
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Uses mature, ratified, non-draft open standards.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Uses open standards.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Sustainability:Interoperability -->

    <h3 id="sustainability-licensing">Licensing</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Each source code file or document has a licence header; each web page has a rights and authorship footer.</p>
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>License is specified in each source code file or document.</p>
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project website includes authorship information.</p>
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Each code repository README (or similar) indicates license applied.</p>
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Each code repository README (or similar) includes authorship information.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Both</p>
                <h4>Notes</h4>
                <p>Many concepts in the original (need to check for duplication across criteria).</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Site or product content has a 'free for public use' license or statement.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Project website has a 'free for public use' license or statement.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Project</p>
                <h4>Notes</h4>
                <p>Consistent language ("project website").</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Site or product content has a license.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Project website has a license.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Project</p>
                <h4>Notes</h4>
                <p>Consistent language ("project website").</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Software (source and binaries) has a licence.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Software has an Open Software Initiative (OSI) recognised licence.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Software has an open source licence.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site states applicable licences.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Project</p>
            </div>
        </div>

        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project documentation defines contributor license agreements, either by requesting a CLA or by stating the rights transferred to the project by a contributor not directly affiliated with the project.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Code</p>
            </div>
        </div>
    </div> <!-- end Sustainability:Licensing -->

    <h3 id="sustainability-portability">Portability</h3>
    <p>Ed. note: this entire section is flagged for review, to be resolved by either condensing the two main concepts (software can be built and run on multiple platforms and web application functions across multiple browsers) into more general criteria or by removing the section altogether and updating related criteria in other sections (such as buildability and documentation criteria related to that).</p>
    <div class="criteria">
        <!-- gallagher -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>For code that compiles and does not use a VM: Uses a build system that interogates the build environment to determine features AND the software actually uses the result of that interogation</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Software</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>For code that is interpreted: Follows standard (likely ad hoc) practices for distribution and interpreter version/selection.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Software</p>
            </div>
        </div>

        <!-- elliott -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>If the algorithm takes advantage of GPU architecture, is it hardware vendor agnostic?</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>GPU/Hardware</p>
                <h4>Notes</h4>
                <p>If the code takes advantage a GPU for its computation, does it use a vendor specific language (e.g. CUDA), or an open standard capabile of running on multiple hardware platforms (e.g OpenCL)?  Using an open standard helps to ensure that more users can run it on their existing systems.  In addition, open standards will likely help with maintainability and compatibility down the road.  CUDA requires NVIDIA cards, whereas OpenCL can run on NVIDIA, AMD, and Intel graphics cards.</p>
            </div>
        </div>

        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under Debian.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under Fedora.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under MacOSX.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under RedHat.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under Solaris.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under Ubuntu.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under UNIX/Linux.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under Windows 7.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under Windows Vista.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under Windows XP.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under Windows.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Browser applications/sites run under Google Chrome.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Browser applications/sites run under Internet Explorer.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Browser applications/sites run under Mozilla Firefox.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Browser applications/sites run under Opera.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Browser applications/sites run under Safari.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Sustainability:Portability-->

    <h3 id="sustainability-supportability">Supportability</h3>
    <p>Ed. note: criteria marked as <code>Grouping: Email</code> need revision for the different modes of email support and regrouped accordingly (direct email, form-based contact, mailing list). </p>
    <div class="criteria">
        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Above pages/windows/files describe, or link to, a description of “how to ask for help” e.g. cite version number, send transcript, error logs etc.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Not sure about "Above" here. Maybe meant to be "About"? Seems to describe an email/contact page template for help requests.</p>
            </div>
        </div>

        <!-- emails -->
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has an e-mail address.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Project has an e-mail address for support.</p>
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project website includes a contact form for requesting support.</p>
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project provides a mailing list for requesting support.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Email</p>
                <h4>Notes</h4>
                <p>Needs a switch statement - email for support, contact form for support, mailing list, irc, bug tracking system? Sort of conflates "email address" with mailing list functionality.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project e-mail address has project domain name.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Project e-mail uses the project's domain name.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Email</p>
                <h4>Notes</h4>
                <p>Not sure these kinds of statements are broadly applicable - it assumes more of an OS model but university or research/science code out of federal agencies may not be able to use a project domain.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">E-mail archives are publicly readable.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Email</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">E-mail archives are searchable.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Email</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">E-mail lists or forums, if present, have regular posts.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Email</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">E-mails are archived.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Email</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>E-mail archives or ticketing system shows that queries are responded to within a week (not necessarily fixed, but at least looked at and a decision taken as to their priority).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Email</p>
                <h4>Notes</h4>
                <p>Flagged - not a marker that is actionable by a project member (consider shift to project analytics assessment section).</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>E-mails are read by more than one person.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Email</p>
                <h4>Notes</h4>
                <p>Is this evaluatable by an external evaluator?</p>
            </div>
        </div>


        <div class="criterion">
            <div class="revisions">
                <p class="original">If there is a blog, is it is regularly used.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project resources are hosted externally to a single-organisation/institution in a sustainable third-party repository (e.g. SourceForge, GoogleCode, LaunchPad, GitHub) which will live beyond the lifetime of the current project.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Project resources are hosted externally to a single-organisation/institution in a sustainable third-party repository, such as GitHub, or a research software repository which will live beyond the lifetime of the current project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>"third-party repository" does not describe GH or the others well. And a bit about domain-specific or research software-specific repositories as archive locations.</p>
            </div>
        </div>
        
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has a ticketing system.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Issues</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Ticketing system is publicly readable.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Issues</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Ticketing system is searchable.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Issues</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Software describes how to get support (in a README for command-line tools or a Help=>About window in a GUI).</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Source code repository, in a README or similar document, describes how to get support.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Software, as built application, includes how to get support through a Help window or other common interface feature.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Support pointers</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">User doc has page describing how to get support.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Support pointers</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has page describing how to get support.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Support pointers</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Web site has search facility.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Flagged - can we come up with a reason related to project maturity for this criterion?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Web site has site map or index.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Flagged - can we come up with a reason related to project maturity for this criterion?</p>
            </div>
        </div>
    </div> <!-- end Sustainability:Supportability-->

    <h3 id="sustainability-testability">Testability</h3>
    <p>Suggested category grouping: project has unit and integration tests (1); tests are run by a continuous integration (CI) system once committed (2). Include coding standards and autoomated coverage analysis as (3) but less crucial than testing and CI. Reconsider criteria that are commonly provided by a CI system and whether those are suggested criteria on their own merit.</p>
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
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has automated tests to check conformance to coding standards.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Project has Unit Tests where apropriate and they can be run automatically, including by a CI system.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>[SS] The original statement is ambiguous - does it refer to a coding standard such as PEP8 and is then testable with a linter or does it refer to unit testing, etc (as seen in the suggested revision)?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Project has automated tests to check test coverage.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Drop this. IMHO, it's far more important to have tests that are run automatically and by a CI system than to try for some % coverage. Classes that are 90% accessors don't need high coverage while classes that include complex/new algorithms do. </p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has integration tests.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Project has integration tests and they can be run automatically, including by a CI system.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>[SS] For scaffolding, etc, consider splitting this out into two criteria but define the relationship.</p>
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
            </div>
        </div>

        <!-- kokkonen -->
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Project recommends tools to check conformance to coding standards.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>I don't see the value of a project *recommending* tools. Either code is being tested by its developers or it isn't. Perhaps if the software in question is itself a developer tool like a language, it should recommend testing tools, but that is a very special case that doesn't seem applicable here.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Project recommends tools to check test coverage.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Maybe this applies for "Library/Module", but I would deprecate</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Project specifies how to set up external resources e.g. FTP servers, databases for tests.</p>
            </div>
            <div class="metadata">
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Test results are e-mailed to a mailing list.</p>
            </div>
            <div class="metadata">
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Test results are visible publicly.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Is this appropriate at all and if it is a common/recommended practice to deliver test results outside the development team.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Test results are visible to all developers/members.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Tests are automatically run nightly.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Is this kind of statement necessary with CI systems? And would a code repo have any signal to indicate this to an external evaluator?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Tests create their configuration own files, database tables etc.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Tests create their own configuration files, database tables etc.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>There is an automated test for this minimum test coverage level.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Given the other notes for test coverage, deprecate.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">This e-mailing list can be subscribed to by anyone.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>The test results e-mailing list can be subscribed to by anyone</p>
            </div>
            <div class="metadata">
            </div>
        </div>

        <!-- kokkonen -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project measures both conditional and line test coverage levels</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Conditional (branch) coverage is harder to achieve but just as important as line coverage</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Expected test results are based on verifiable criteria.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Just executing a line of code isn't worth much unless the results or side effects are compared to verifiable expected results</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Code is designed to support efficient testing.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>If code isn't designed with testing in mind, verifiable tests can be convoluted or impossible to write.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Tests use mocking technology where appropriate.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Mocking improves the focus, performance, and flexibility of unit tests. Most importantly it supports testing conditions that occur rarely or have perhaps never been observed so far.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Tests cover exceptional conditions as well as expected behavior.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>It's just as important to test for things that are unlikely to occur as for those that are part of nominal behavior.</p>
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
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>An automated build (e.g. Make, ANT, Maven, Gradle, or other language-specific build tool) is used to build any software.</p>
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
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Dependency management is used to automatically download dependencies (e.g. ANT, Ivy, Maven or custom solution).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>This is generally not an option for non-Java compiled code. However, there is a related idea for C and C++...</p>
                <!-- add note for things like python requirements.txt (pip, etc) and update language to refer more broadly to non-Java situations. -->
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
        <!-- gallagher -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Code follows the GNU software guidlines and uses README, NEWS, INSTALL and COPYING files to describe the package (INSTALL includes the build information this case).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>related to previous statement.</p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <!-- end gallagher -->

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

        <!-- gallagher -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Binary and source packages reference thrid-party code (including the acceptable versions) so that commonly-used tools (e.g., yum, apt-get) will automaticlly fetch those source/binary packages</p>
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
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project uses build tools (e.g. automake, etc.) in a way that integrates with linux distro packager's expectations so they can/will build packages for public repos.</p>
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
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project supports common/standard (ad hoc) binary packaing tools (e.g., RPM, python egg). This means that a 'buildable' package provides binaries (or the equivalent) so that it can simply be installed and does not have to be built!</p>
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

        <!-- kokkonen -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Build instructions include platform-dependent details and answers to frequently asked questions.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Build instructions include clear version requirements for external dependencies (unless automated dependency management is provided).</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Usability:Buildability -->

    <h3 id="usability-documentation">Documentation</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Code is documented (comment blocks, etc.)</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>API Docs</p>
                <h4>Notes</h4>
                <p>To allow present/future developers to be able to quickly understand and/or modify the software.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Pre/Post conditions are clearly defined</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>API Docs</p>
                <h4>Notes</h4>
                <p>To inform present/future developers of the expected input and output of the function.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Comment blocks are well-structured and consistent, following language or project standards.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>API Docs</p>
                <h4>Notes</h4>
                <p>Step before auto-generating where comments are clean and consistent across the project.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">API documentation is autogenerated (e.g., by JavaDoc or Doxygen), and documents APIs completely (e.g., configuration files, property names, etc.).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>API Docs</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Does not use terms like “intuitive”, “user friendly”, “easy to use”, “simple” or “obviously”, unless as part of quotes from satisfied users.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Style</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">English language descriptions of commands and errors are provided but only to complement the above.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Style</p>
                <h4>Notes</h4>
                <p>Clearer to state that commands/errors have corresponding plain English descriptions in the docs?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Plain-text files (e.g. READMEs) use indentation and underlining (e.g. === and ---) to structure the text, and avoid TAB character indentation.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Text files for higher-level documentation, such as README or CONTRIBUTING sections, use a common and identifiable markup language.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Repo Doc style</p>
                <h4>Notes</h4>
                <p>So markdown or reStructuredText but keeping it open to new "flavors".</p>
            </div>
        </div>


        <div class="criterion">
            <div class="revisions">
                <p class="original">Further information is suitable for the level of the reader, for each class of user.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Explanations should be free of jargon.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Audience</p>
                <h4>Notes</h4>
                <p>Users can have diverse experiences.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Partitioned into sections for users, user-developers and developers (depending on the software).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Audience</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>States assumed background and expertise of the reader, for each class of user.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Audience</p>
                <h4>Notes</h4>
                <p>This is often implied by the different kinds of documentation made available? Might be better to change to something that reflects "User Guide" or "Developer's Guide".</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Documentation is on the project web site.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>A link to the documentation is contained in the code.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Documentation is on the project website or the project website provides a clear link to an externally-hosted documentation web site.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Doc Management</p>
                <h4>Notes</h4>
                <p>Code and documentation can be separated.</p>
                <p>Consensus for documentation that is hosted by the project or that is hosted on some third-party site such as Read The Docs.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Documentation on the project web site makes it clear what version of the product the documentation applies to.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Doc Management</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Documentation is held under version control alongside any code or other product components.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Doc Management</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>
        <!-- gallagher -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Where available, project takes advantage of public-facing tools' documentation support. For example, github supports a README file that uses Markdown. It's pretty quick to write and is displayed automatically when a person goes to get the source. Maybe this has more to do with 'buildability,' but in some cases it might be all the documentation an initial author writes. </p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Doc management</p>
                <p><a href="#"></a></p>
            </div>
        </div>
        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>The documentation for a specific software release is available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Doc management</p>
            </div>
        </div>
        
        
        <div class="criterion">
            <div class="revisions">
                <p class="original">Consists of clear, step-by-step instructions for use or adoption.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Content</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">For common problems and error messages, the symptoms and step-by-step solutions are provided.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Documentation is updated to reflect new errors and resolution methods identified.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Content</p>
                <h4>Notes</h4>
                <p>New errors and resolutions can be identified over time.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Gives examples of what the user can see at each step, e.g., screen shots or command-line excerpts; installation outcomes; working examples and error examples.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Content</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Lists resources for further information.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Content</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Provides a high-level overview of the product.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Content</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Constraints or restrictions are included in the documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Content</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Quality control information is included in the documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Content</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">States command names and syntax, says what menus to use, lists parameters and error messages exactly as they appear or should be typed; or provides similarly explicit instructions on how to apply product.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Code or GUI examples provided in the documentation reflect the current state of the software, ie. parameter names in the code match those found in the documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Content</p>
                <h4>Notes</h4>
                <p>Rephrasing for clarity?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Uses teletype-style fonts for command line inputs and outputs, source code fragments, function names, class names etc.; uses appropriately styled fonts for key information and special terms or links.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Documentation follows commmon styles for displaying code blocks.</p>
                <p class="revision added"><i class="fa fa-pencil fa-fw"></i>Documentation clearly distinguishses between input and output blocks.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>(Style?)</p>
                <h4>Notes</h4>
                <p>If nothing else, code blocks or inline snippets are rendered with monospaced fonts (which is the searchable term in most font browsers).</p>
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
                <p>Not clear what this is referring to.</p>
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
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>The web application was developed using responsive design principles.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Here referring to the application developed as the code/software deliverable and not a project website. But it also applies to the project website.</p>
                <h4>References</h4>
                <p><a href="#"></a>[ADD: ref to responsive design http://alistapart.com/article/responsive-web-design]</p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Generated data products are organized clearly, with embedded metadata wherever possible.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Generated data products are organized clearly, with associated metadata clearly identifiable.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Step 1: data + metadata.</p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Generated data products and their related metadata are provided in data packages and those data packages are organized clearly.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Step 2: data packages.</p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Lists of resources are neatly presented for easy access, comparison, access to details, and handling of scale. Both filter and scrolling are available; user can control number of items presented.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Unclear what this refers to unless it's a ToC or file browser pane? If yes, needs clearer wording.</p>
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
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>System can be controlled or used by foreign speakers and color-vision-deficient individuals.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Two concepts in the original - localization and accessibility. Splitting into clearer criteria (language may not be high priority for projects (localization is hard) but accessibility (beyond color-blindness) is more than doable with clean markup, etc.</p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>

        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project web site provides localization options, ie support for non-English speakers.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Localization. Open question re: is localization tied to project goals or more generally (reqs from funder, etc) given that it is not always a straightforward task? Applies to Identity, Documentation and other Usability categories.</p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project web site follows established guidelines for web accessibility. </p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Accessibility</p>
                <h4>References</h4>
                <p><a href="#"></a>https://www.w3.org/standards/webdesign/accessibility, WCAG, Section 508</p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Web application follows established guidelines for web accessibility whenever possible.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Accessibility. Note limitations in mapping frameworks which may result in accessibility being tied to color-blind friendly color scheme.</p>
                <h4>References</h4>
                <p><a href="#"></a>https://www.w3.org/standards/webdesign/accessibility</p>
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
    <p>Suggested group ordering: Basic (1), Process (2), Tools (3).</p>
    <div class="criteria">
        <!-- gallagher -->
        <div class="criterion">
            <div class="revisions">
                <p class="original">Software is exposed to a static source code checker (e.g., Coverity)</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Available Tools</p>
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
                <p class="original">Software authors use PKI (e.g., PGP) to sign releases (source and binary) and make the public key available on their website (and/or public key repos).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Basic</p>
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
                <p class="original">Authors are aware of and use public secure coding guidlines for their languages/technology. These include specific guidlines published by CERT and OWASP, cover both languages like C/C++, Java, Perl and technologies like Web services adn XSLT.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Process</p>
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
                <p class="original">Projects have in place (and publicly visable) a security incident response plan.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Process</p>
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
                <p class="original">Authors perform dynamic testing on their software</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Tools</p>
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
                <p class="original">Authors work with an external organization that reviews/tests their software.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Process</p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>

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

    <h3 id="other-performance">Performance</h3>
    <div class="criteria">
        <p>Ed. note: Suggested new category to specifically address performance.</p>
    </div> <!-- end Performance -->

</div> <!-- end guidelines-->


## Use of these Criteria for Assessment ##


## Reuse and Software Progression ##

"Maturity"

Project lifecycle


## Participants ##

<ul>
    <li>Toner, Valerie (NOAA)</li>
    <li>Gallagher, James (OPeNDAP)</li>
    <li>Downs, Robert (CIESIN)</li>
    <li>Wilson, Anne (LASP)</li>
    <li>Kokkonen, Kim (LASP)</li>
    <li>Elliott, Joshua (LASP)</li>
    <li>Bowe, Ryan ()</li>
</ul>

## References ##

<div class="refs">
    <div style="line-height: 1.35; " class="csl-bib-body">
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[1]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“2016 Software Infrastructure for Sustained Innovation (SI2) PI Workshop Report,” Software Infrastructure for Sustained Innovation (SI2) Principal Investigators (PI), Arlington, VA, Feb. 2016.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=report&amp;rft.btitle=2016%20Software%20Infrastructure%20for%20Sustained%20Innovation%20(SI2)%20PI%20Workshop%20Report&amp;rft.place=Arlington%2C%20VA&amp;rft.date=2016-02-16"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[2]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">N. Azizian, S. Sarkani, and T. Mazzuchi, “A Comprehensive Review and Analysis of Maturity Assessment Approaches for Improved Decision Support to Achieve Efficient Defense Acquisition,” in <i>Proceedings of the World Congress on Engineering and Computer Science 2009</i>, San Francisco, 2009.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_id=urn%3Aisbn%3A978-988-18210-2-7&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=proceeding&amp;rft.atitle=A%20Comprehensive%20Review%20and%20Analysis%20of%20Maturity%20Assessment%20Approaches%20for%20Improved%20Decision%20Support%20to%20Achieve%20Efficient%20Defense%20Acquisition&amp;rft.btitle=Proceedings%20of%20the%20World%20Congress%20on%20Engineering%20and%20Computer%20Science%202009&amp;rft.place=San%20Francisco&amp;rft.aufirst=Nazanin&amp;rft.aulast=Azizian&amp;rft.au=Nazanin%20Azizian&amp;rft.au=Shahram%20Sarkani&amp;rft.au=Thomas%20Mazzuchi&amp;rft.date=2009-10-20&amp;rft.isbn=978-988-18210-2-7"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[3]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">R. R. Downs and J. J. Marshall, “A Proposal on Using Reuse Readiness Levels to Measure Software Reusability,” <i>Data Science Journal</i>, vol. 9, 2010.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_id=info%3Adoi%2F10.7916%2FD8ZS2V7W&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.atitle=A%20Proposal%20on%20Using%20Reuse%20Readiness%20Levels%20to%20Measure%20Software%20Reusability&amp;rft.jtitle=Data%20Science%20Journal&amp;rft.volume=9&amp;rft.aufirst=Robert%20R.&amp;rft.aulast=Downs&amp;rft.au=Robert%20R.%20Downs&amp;rft.au=James%20J.%20Marshall&amp;rft.date=2010"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[4]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">D. C. Stig, U. Högman, and D. Bergsjö, “Assessment for the Readiness for Internal Technology Transfer - A Case Study,” 2011.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.atitle=Assessment%20for%20the%20Readiness%20for%20Internal%20Technology%20Transfer%20-%20A%20Case%20Study&amp;rft.aufirst=Daniel%20Corin&amp;rft.aulast=Stig&amp;rft.au=Daniel%20Corin%20Stig&amp;rft.au=Ulf%20H%C3%B6gman&amp;rft.au=Dag%20Bergsj%C3%B6&amp;rft.date=2011"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[5]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“Best Practices Criteria for Free/Libre and Open Source Software (FLOSS) (version 0.8.0),” <i>Linux Foundation</i>. [Online]. Available: https://github.com/linuxfoundation/cii-best-practices-badge/blob/master/doc/criteria.md.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=Best%20Practices%20Criteria%20for%20Free%2FLibre%20and%20Open%20Source%20Software%20(FLOSS)%20(version%200.8.0)&amp;rft.identifier=https%3A%2F%2Fgithub.com%2Flinuxfoundation%2Fcii-best-practices-badge%2Fblob%2Fmaster%2Fdoc%2Fcriteria.md"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[6]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“CLAHub,” <i>Contributor License Agreements on Github</i>. [Online]. Available: https://www.clahub.com/. [Accessed: 24-May-2016].</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=CLAHub&amp;rft.identifier=https%3A%2F%2Fwww.clahub.com%2F"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[7]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">Nadia Eghbal, “Contributing Guides: A Template.” [Online]. Available: https://github.com/nayafia/contributing-template.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=Contributing%20Guides%3A%20A%20Template&amp;rft.identifier=https%3A%2F%2Fgithub.com%2Fnayafia%2Fcontributing-template&amp;rft.aulast=Nadia%20Eghbal&amp;rft.au=Nadia%20Eghbal"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[8]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">C. A. Ehmke, “Contributor Covenant: A Code of Conduct for Open Source Projects.,” 2014. [Online]. Available: http://contributor-covenant.org/.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=Contributor%20Covenant%3A%20A%20Code%20of%20Conduct%20for%20Open%20Source%20Projects.&amp;rft.identifier=http%3A%2F%2Fcontributor-covenant.org%2F&amp;rft.aufirst=Coraline%20Ada&amp;rft.aulast=Ehmke&amp;rft.au=Coraline%20Ada%20Ehmke&amp;rft.date=2014"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[9]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“DASPOS.” [Online]. Available: https://daspos.crc.nd.edu/. [Accessed: 24-May-2016].</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=DASPOS&amp;rft.identifier=https%3A%2F%2Fdaspos.crc.nd.edu%2F"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[10]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“duecredit/duecredit,” <i>duecredit</i>. [Online]. Available: https://github.com/duecredit/duecredit. [Accessed: 24-May-2016].</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=duecredit%2Fduecredit&amp;rft.description=duecredit%20-%20Automated%20collection%20and%20reporting%20of%20citations%20for%20used%20software%2Fmethods%2Fdatasets&amp;rft.identifier=https%3A%2F%2Fgithub.com%2Fduecredit%2Fduecredit"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[11]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“Ecological Studies of Open Source Software Ecosystems.” [Online]. Available: http://informatique.umons.ac.be/genlog/projects/ecos/. [Accessed: 24-May-2016].</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=Ecological%20Studies%20of%20Open%20Source%20Software%20Ecosystems&amp;rft.identifier=http%3A%2F%2Finformatique.umons.ac.be%2Fgenlog%2Fprojects%2Fecos%2F"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[12]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">J. Graybeal, “ESIP Technology Evaluation Framework Final Recommendations,” Jan. 2016.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=report&amp;rft.btitle=ESIP%20Technology%20Evaluation%20Framework%20Final%20Recommendations&amp;rft.aufirst=John&amp;rft.aulast=Graybeal&amp;rft.au=John%20Graybeal&amp;rft.date=2016-01"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[13]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“ESSI-SCOPE Quality Characteristics and their application.” [Online]. Available: http://www.cse.dcu.ie/essiscope/sm2/9126ref.html. [Accessed: 24-May-2016].</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=ESSI-SCOPE%20Quality%20Characteristics%20and%20their%20application&amp;rft.identifier=http%3A%2F%2Fwww.cse.dcu.ie%2Fessiscope%2Fsm2%2F9126ref.html"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[14]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“Google VSAQ: Vendor Security Assessment Questionnaire,” <i>Google VSAQ</i>. [Online]. Available: https://github.com/google/vsaq. [Accessed: 24-May-2016].</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=Google%20VSAQ%3A%20Vendor%20Security%20Assessment%20Questionnaire&amp;rft.description=vsaq%20-%20VSAQ%20is%20an%20interactive%20questionnaire%20application%20to%20assess%20the%20security%20programs%20of%20third%20parties.&amp;rft.identifier=https%3A%2F%2Fgithub.com%2Fgoogle%2Fvsaq"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[15]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">I. Gent, C. Jones, and B. Matthews, “GUIDELINES FOR PERSISTENTLY IDENTIFYING SOFTWARE USING DATACITE: A JISC RESEARCH DATA SPRING PROJECT,” Sep. 2015.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=report&amp;rft.btitle=GUIDELINES%20FOR%20PERSISTENTLY%20IDENTIFYING%20SOFTWARE%20USING%20DATACITE%3A%20A%20JISC%20RESEARCH%20DATA%20SPRING%20PROJECT&amp;rft.aufirst=Ian&amp;rft.aulast=Gent&amp;rft.au=Ian%20Gent&amp;rft.au=Catherine%20Jones&amp;rft.au=Brian%20Matthews&amp;rft.date=2015-09"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[16]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“Home,” <i>Center for Trustworthy Scientific Cyberinfrastructure</i>. [Online]. Available: http://trustedci.org/. [Accessed: 24-May-2016].</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=Home&amp;rft.description=Center%20for%20Trustworthy%20Scientific%20Cyberinfrastructure%2C%20CTSC%2C%20Indiana%20University%2C%20Center%20for%20Applied%20Cybersecurity%20Research%2C%20CACR%2C%20IU%2C%20Von%20Welch%2C%20National%20Science%20Foundation&amp;rft.identifier=http%3A%2F%2Ftrustedci.org%2F"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[17]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“ISO/IEC 25010:2011 - Systems and software engineering -- Systems and software Quality Requirements and Evaluation (SQuaRE) -- System and software quality models,” <i>ISO</i>. [Online]. Available: http://www.iso.org/iso/home/store/catalogue_ics/catalogue_detail_ics.htm?csnumber=35733. [Accessed: 24-May-2016].</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=ISO%2FIEC%2025010%3A2011%20-%20Systems%20and%20software%20engineering%20--%20Systems%20and%20software%20Quality%20Requirements%20and%20Evaluation%20(SQuaRE)%20--%20System%20and%20software%20quality%20models&amp;rft.identifier=http%3A%2F%2Fwww.iso.org%2Fiso%2Fhome%2Fstore%2Fcatalogue_ics%2Fcatalogue_detail_ics.htm%3Fcsnumber%3D35733"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[18]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“NASA Technology Readiness Levels,” 28-Oct-2012. [Online]. Available: https://www.nasa.gov/directorates/heo/scan/engineering/technology/txt_accordion1.html.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=NASA%20Technology%20Readiness%20Levels&amp;rft.identifier=https%3A%2F%2Fwww.nasa.gov%2Fdirectorates%2Fheo%2Fscan%2Fengineering%2Ftechnology%2Ftxt_accordion1.html&amp;rft.date=2012-10-28"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[19]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">Brigitta Urban-Mathieux, “NGDA Lifecycle Maturity Assessment,” <i>GEOPLATFORM.gov</i>. [Online]. Available: https://cms.geoplatform.gov/A-16-NGDA-Theme-Community/LMA.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=NGDA%20Lifecycle%20Maturity%20Assessment&amp;rft.identifier=https%3A%2F%2Fcms.geoplatform.gov%2FA-16-NGDA-Theme-Community%2FLMA&amp;rft.aulast=Brigitta%20Urban-Mathieux&amp;rft.au=Brigitta%20Urban-Mathieux"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[20]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">V. Ratnakar and Y. Gil, “Ontosoft,” <i>Ontosoft</i>. [Online]. Available: http://ontosoft.org/ontology/software/. [Accessed: 24-May-2016].</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=Ontosoft&amp;rft.identifier=http%3A%2F%2Fontosoft.org%2Fontology%2Fsoftware%2F&amp;rft.aufirst=Varun&amp;rft.aulast=Ratnakar&amp;rft.au=Varun%20Ratnakar&amp;rft.au=Yolanda%20Gil"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[21]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“Open Services for Lifecycle Collaboration.” [Online]. Available: http://open-services.net/. [Accessed: 24-May-2016].</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=Open%20Services%20for%20Lifecycle%20Collaboration&amp;rft.identifier=http%3A%2F%2Fopen-services.net%2F"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[22]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“OWASP,” <i>The Open Web Application Security Project</i>. [Online]. Available: https://www.owasp.org/index.php/Main_Page. [Accessed: 24-May-2016].</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=OWASP&amp;rft.identifier=https%3A%2F%2Fwww.owasp.org%2Findex.php%2FMain_Page"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[23]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">M. Petre and G. Wilson, “PLOS/Mozilla Scientific Code Review Pilot: Summary of Findings,” <i>CoRR</i>, vol. abs/1311.2412, 2013.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.atitle=PLOS%2FMozilla%20Scientific%20Code%20Review%20Pilot%3A%20Summary%20of%20Findings&amp;rft.jtitle=CoRR&amp;rft.volume=abs%2F1311.2412&amp;rft.aufirst=Marian&amp;rft.aulast=Petre&amp;rft.au=Marian%20Petre&amp;rft.au=Greg%20Wilson&amp;rft.date=2013"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[24]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“Practices Perfected In OSS Can Reshape Enterprise Development,” <i>The npm Blog</i>. [Online]. Available: http://blog.npmjs.org/post/139373244435/practices-perfected-in-oss-can-reshape-enterprise. [Accessed: 24-May-2016].</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=Practices%20Perfected%20In%20OSS%20Can%20Reshape%20Enterprise%20Development&amp;rft.description=npm%2C%20Inc.%20helps%20more%20than%203%20million%20open%20source%20developers%20build%20communities%2C%20learn%2C%20collaborate%2C%20and%20ultimately%20publish%20software%20that%E2%80%99s%20used%20by%20many%20of%20the%20largest%20companies%20in%20the%20world.%0AI%20believe...&amp;rft.identifier=http%3A%2F%2Fblog.npmjs.org%2Fpost%2F139373244435%2Fpractices-perfected-in-oss-can-reshape-enterprise"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[25]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">K. Fogel, “Producing Open Source Software.” [Online]. Available: http://producingoss.com/en/producingoss.html. [Accessed: 24-May-2016].</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=Producing%20Open%20Source%20Software&amp;rft.identifier=http%3A%2F%2Fproducingoss.com%2Fen%2Fproducingoss.html&amp;rft.aufirst=Karl&amp;rft.aulast=Fogel&amp;rft.au=Karl%20Fogel"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[26]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“RepoGrams/RepoGrams,” <i>RepoGrams</i>. [Online]. Available: https://github.com/RepoGrams/RepoGrams. [Accessed: 24-May-2016].</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=RepoGrams%2FRepoGrams&amp;rft.description=RepoGrams%20-%20A%20tool%20to%20analyze%20and%20compare%20software%20repositories%3A&amp;rft.identifier=https%3A%2F%2Fgithub.com%2FRepoGrams%2FRepoGrams"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[27]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“reproducible-builds.org,” <i>Reproducible Builds</i>. [Online]. Available: https://reproducible-builds.org/. [Accessed: 24-May-2016].</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=reproducible-builds.org&amp;rft.identifier=https%3A%2F%2Freproducible-builds.org%2F"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[28]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">S. Hettrick, “Research Software Sustainability: Report on a Knowledge Exchange Workshop,” The Software Sustainability Institute, Feb. 2016.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=report&amp;rft.btitle=Research%20Software%20Sustainability%3A%20Report%20on%20a%20Knowledge%20Exchange%20Workshop&amp;rft.aufirst=Simon&amp;rft.aulast=Hettrick&amp;rft.au=Simon%20Hettrick&amp;rft.date=2016-02"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[29]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“Reuse Readiness Levels (RRLs),” NASA Earth Science Data Systems - Software Reuse Working Group, Apr. 2010.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=report&amp;rft.btitle=Reuse%20Readiness%20Levels%20(RRLs)&amp;rft.date=2010-04-30"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[30]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">Mike Jackson, Steve Crouch, Rob Baxter, “Software Evaluation: Criteria-based Assessment.” Software Sustainability Institure, Nov-2011.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=document&amp;rft.title=Software%20Evaluation%3A%20Criteria-based%20Assessment&amp;rft.publisher=Software%20Sustainability%20Institure&amp;rft.identifier=http%3A%2F%2Fsoftware.ac.uk%2Fsites%2Fdefault%2Ffiles%2FSSI-SoftwareEvaluationCriteria.pdf&amp;rft.aulast=Mike%20Jackson%2C%20Steve%20Crouch%2C%20Rob%20Baxter&amp;rft.au=Mike%20Jackson%2C%20Steve%20Crouch%2C%20Rob%20Baxter&amp;rft.date=2011-11"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[31]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">Steve Crouch, Mike Jackson, Rob Baxter, “Software Evaluation Guide,” <i>Software Sustainability Institute</i>. [Online]. Available: http://www.software.ac.uk/software-evaluation-guide.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=Software%20Evaluation%20Guide&amp;rft.identifier=http%3A%2F%2Fwww.software.ac.uk%2Fsoftware-evaluation-guide&amp;rft.aulast=Steve%20Crouch%2C%20Mike%20Jackson%2C%20Rob%20Baxter&amp;rft.au=Steve%20Crouch%2C%20Mike%20Jackson%2C%20Rob%20Baxter"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[32]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“Stealing Google’s Coding Practices for Academia,” <i>Stealing Google’s Coding Practices for Academia</i>. .</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=blogPost&amp;rft.title=Stealing%20Google's%20Coding%20Practices%20for%20Academia&amp;rft.identifier=https%3A%2F%2Fda-data.blogspot.com%2F2016%2F04%2Fstealing-googles-coding-practices-for.html"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[33]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“The Open Definition - Open Definition - Defining Open in Open Data, Open Content and Open Knowledge.” [Online]. Available: http://opendefinition.org/. [Accessed: 24-May-2016].</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=The%20Open%20Definition%20-%20Open%20Definition%20-%20Defining%20Open%20in%20Open%20Data%2C%20Open%20Content%20and%20Open%20Knowledge&amp;rft.identifier=http%3A%2F%2Fopendefinition.org%2F"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[34]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">K. D. Welker, “The Software Maintainability Index Revisited,” <i>The Journal of Defense Software Engineering</i>, Aug. 2001.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.atitle=The%20Software%20Maintainability%20Index%20Revisited&amp;rft.jtitle=The%20Journal%20of%20Defense%20Software%20Engineering&amp;rft.aufirst=Kurt%20D.&amp;rft.aulast=Welker&amp;rft.au=Kurt%20D.%20Welker&amp;rft.date=2001-08"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[35]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">C. A. Mattmann, R. R. Downs, J. J. Marshall, N. F. Most, and S. Samadi, “TOOLS TO SUPPORT THE REUSE OF SOFTWARE ASSETS FOR THE NASA EARTH SCIENCE DECADAL SURVEY MISSIONS,” <i>IEEE Geoscience and Remote Sensing Society Newsletter</i>, Mar. 2011.</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.atitle=TOOLS%20TO%20SUPPORT%20THE%20REUSE%20OF%20SOFTWARE%20ASSETS%20FOR%20THE%20NASA%20EARTH%20SCIENCE%20DECADAL%20SURVEY%20MISSIONS&amp;rft.jtitle=IEEE%20Geoscience%20and%20Remote%20Sensing%20Society%20Newsletter&amp;rft.aufirst=Chris%20A.&amp;rft.aulast=Mattmann&amp;rft.au=Chris%20A.%20Mattmann&amp;rft.au=Robert%20R.%20Downs&amp;rft.au=James%20J.%20Marshall&amp;rft.au=Neal%20F.%20Most&amp;rft.au=Shahin%20Samadi&amp;rft.date=2011-03"></span>
      <div style="clear: left; " class="csl-entry">
        <div style="float: left; padding-right: 0.5em;text-align: right; width: 2em;" class="csl-left-margin">[36]</div><div style="margin: 0 .4em 0 2.5em;" class="csl-right-inline">“Welcome to the Standard Technical Evaluation Process Toolkit,” <i>MITRE STEP Toolkit</i>. [Online]. Available: http://www2.mitre.org/work/sepo/toolkits/STEP/. [Accessed: 24-May-2016].</div>
      </div>
      <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=Welcome%20to%20the%20Standard%20Technical%20Evaluation%20Process%20Toolkit&amp;rft.identifier=http%3A%2F%2Fwww2.mitre.org%2Fwork%2Fsepo%2Ftoolkits%2FSTEP%2F"></span>
    </div>
</div>





