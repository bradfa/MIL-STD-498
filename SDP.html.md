# 1. Scope.

This section shall be divided into the following paragraphs.

## 1.1 Identification.

This paragraph shall contain a full identification of the system
and the software to which this document applies, including, as
applicable, identification number(s), title(s), abbreviation(s),
version number(s), and release number(s).

## 1.2 System overview.

This paragraph shall briefly state the purpose of the system and
the software to which this document applies. It shall describe the
general nature of the system and software; summarize the history of
system development, operation, and maintenance; identify the
project sponsor, acquirer, user, developer, and support agencies;
identify current and planned operating sites; and list other
relevant documents.

## 1.3 Document overview.

This paragraph shall summarize the purpose and contents of this
document and shall describe any security or privacy considerations
associated with its use.

## 1.4 Relationship to other plans.

This paragraph shall describe the relationship, if any, of the SDP
to other project management plans.

# 2. Referenced documents.

This section shall list the number, title, revision, and date of
all documents referenced in this plan. This section shall also
identify the source for all documents not available through normal
Government stocking activities.

# 3. Overview of required work.

This section shall be divided into paragraphs as needed to
establish the context for the planning described in later sections.
It shall include, as applicable, an overview of:

1.  Requirements and constraints on the system and software to be
    developed
2.  Requirements and constraints on project documentation
3.  Position of the project in the system life cycle
4.  The selected program/acquisition strategy or any requirements
    or constraints on it
5.  Requirements and constraints on project schedules and resources
6.  Other requirements and constraints, such as on project
    security, privacy, methods, standards, interdependencies in
    hardware and software development, etc.

# 4. Plans for performing general software development activities.

This section shall be divided into the following paragraphs.
Provisions corresponding to non-required activities may be
satisfied by the words "Not applicable." If different builds or
different software on the project require different planning, these
differences shall be noted in the paragraphs. In addition to the
content specified below, each paragraph shall identify applicable
risks/uncertainties and plans for dealing with them.

## 4.1 Software development process.

This paragraph shall describe the software development process to
be used. The planning shall cover all contractual clauses
concerning this topic, identifying planned builds, if applicable,
their objectives, and the software development activities to be
performed in each build.

## 4.2 General plans for software development.

This paragraph shall be divided into the following subparagraphs.

### 4.2.1 Software development methods.

This paragraph shall describe or reference the software development
methods to be used. Included shall be descriptions of the manual
and automated tools and procedures to be used in support of these
methods. The methods shall cover all contractual clauses concerning
this topic. Reference may be made to other paragraphs in this plan
if the methods are better described in context with the activities
to which they will be applied.

### 4.2.2 Standards for software products.

This paragraph shall describe or reference the standards to be
followed for representing requirements, design, code, test cases,
test procedures, and test results. The standards shall cover all
contractual clauses concerning this topic. Reference may be made to
other paragraphs in this plan if the standards are better described
in context with the activities to which they will be applied.
Standards for code shall be provided for each programming language
to be used. They shall include at a minimum:

Standards for format (such as indentation, spacing, capitalization,
and order of information)
Standards for header comments (requiring, for example,
name/identifier of the code; version identification; modification
history; purpose; requirements and design decisions implemented;
notes on the processing (such as algorithms used, assumptions,
constraints, limitations, and side effects); and notes on the data
(inputs, outputs, variables, data structures, etc.)
Standards for other comments (such as required number and content
expectations)
Naming conventions for variables, parameters, packages, procedures,
files, etc.
Restrictions, if any, on the use of programming language constructs
or features
Restrictions, if any, on the complexity of code aggregates
### 4.2.3 Reusable software products.

This paragraph shall be divided into the following subparagraphs.

#### 4.2.3.1 Incorporating reusable software products.

This paragraph shall describe the approach to be followed for
identifying, evaluating, and incorporating reusable software
products, including the scope of the search for such products and
the criteria to be used for their evaluation. It shall cover all
contractual clauses concerning this topic. Candidate or selected
reusable software products known at the time this plan is prepared
or updated shall be identified and described, together with
benefits, drawbacks, and restrictions, as applicable, associated
with their use.

#### 4.2.3.2 Developing reusable software products.

This paragraph shall describe the approach to be followed for
identifying, evaluating, and reporting opportunities for developing
reusable software products. It shall cover all contractual clauses
concerning this topic.

### 4.2.4 Handling of critical requirements.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for handling requirements
designated critical. The planning in each subparagraph shall cover
all contractual clauses concerning the identified topic.   
4.2.4.1 Safety assurance   
4.2.4.2 Security assurance   
4.2.4.3 Privacy assurance   
4.2.4.4 Assurance of other critical requirements

### 4.2.5 Computer hardware resource utilization.

This paragraph shall describe the approach to be followed for
allocating computer hardware resources and monitoring their
utilization. It shall cover all contractual clauses concerning this
topic.

### 4.2.6 Recording rationale.

This paragraph shall describe the approach to be followed for
recording rationale that will be useful to the support agency for
key decisions made on the project. It shall interpret the term "key
decisions" for the project and state where the rationale are to be
recorded. It shall cover all contractual clauses concerning this
topic.

### 4.2.7 Access for acquirer review.

This paragraph shall describe the approach to be followed for
providing the acquirer or its authorized representative access to
developer and subcontractor facilities for review of software
products and activities. It shall cover all contractual clauses
concerning this topic.

# 5. Plans for performing detailed software development activities.

This section shall be divided into the following paragraphs.
Provisions corresponding to non-required activities may be
satisfied by the words "Not applicable." If different builds or
different software on the project require different planning, these
differences shall be noted in the paragraphs. The discussion of
each activity shall include the approach
(meth-ods/procedures/tools) to be applied to: 1) the analysis or
other technical tasks involved, 2) the recording of results, and 3)
the preparation of associated deliverables, if applicable. The
discussion shall also identify applicable risks/uncertainties and
plans for dealing with them. Reference may be made to 4.2.1 if
applicable methods are described there.

## 5.1 Project planning and oversight.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for project planning and
oversight. The planning in each subparagraph shall cover all
contractual clauses regarding the identified topic.   
5.1.1 Software development planning (covering updates to this plan)
  
5.1.2 CSCI test planning   
5.1.3 System test planning   
5.1.4 Software installation planning   
5.1.5 Software transition planning   
5.1.6 Following and updating plans, including the intervals for
management review

## 5.2 Establishing a software development environment.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for establishing, controlling,
and maintaining a software development environment. The planning in
each subparagraph shall cover all contractual clauses regarding the
identified topic.   
5.2.1 Software engineering environment   
5.2.2 Software test environment   
5.2.3 Software development library   
5.2.4 Software development files   
5.2.5 Non-deliverable software

## 5.3 System requirements analysis.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for participating in system
requirements analysis. The planning in each subparagraph shall
cover all contractual clauses regarding the identified topic.   
5.3.1 Analysis of user input   
5.3.2 Operational concept   
5.3.3 System requirements

## 5.4 System design.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for participating in system
design. The planning in each subparagraph shall cover all
contractual clauses regarding the identified topic.   
5.4.1 System-wide design decisions   
5.4.2 System architectural design

## 5.5 Software requirements analysis.

This paragraph shall describe the approach to be followed for
software requirements analysis. The approach shall cover all
contractual clauses concerning this topic.

## 5.6 Software design.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for software design. The
planning in each subparagraph shall cover all contractual clauses
regarding the identified topic.   
5.6.1 CSCI-wide design decisions   
5.6.2 CSCI architectural design   
5.6.3 CSCI detailed design

## 5.7 Software implementation and unit testing.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for software implementation
and unit testing. The planning in each subparagraph shall cover all
contractual clauses regarding the identified topic.   
5.7.1 Software implementation   
5.7.2 Preparing for unit testing   
5.7.3 Performing unit testing   
5.7.4 Revision and retesting   
5.7.5 Analyzing and recording unit test results

## 5.8 Unit integration and testing.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for unit integration and
testing. The planning in each subparagraph shall cover all
contractual clauses regarding the identified topic.   
5.8.1 Preparing for unit integration and testing   
5.8.2 Performing unit integration and testing   
5.8.3 Revision and retesting   
5.8.4 Analyzing and recording unit integration and test results

## 5.9 CSCI qualification testing.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for CSCI qualification
testing. The planning in each subparagraph shall cover all
contractual clauses regarding the identified topic.   
5.9.1 Independence in CSCI qualification testing   
5.9.2 Testing on the target computer system   
5.9.3 Preparing for CSCI qualification testing   
5.9.4 Dry run of CSCI qualification testing   
5.9.5 Performing CSCI qualification testing   
5.9.6 Revision and retesting   
5.9.7 Analyzing and recording CSCI qualification test results

## 5.10 CSCI/HWCI integration and testing.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for participating in CSCI/HWCI
integration and testing. The planning in each subparagraph shall
cover all contractual clauses regarding the identified topic.   
5.10.1 Preparing for CSCI/HWCI integration and testing   
5.10.2 Performing CSCI/HWCI integration and testing   
5.10.3 Revision and retesting   
5.10.4 Analyzing and recording CSCI/HWCI integration and test
results

## 5.11 System qualification testing.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for participating in system
qualification testing. The planning in each subparagraph shall
cover all contractual clauses regarding the identified topic.   
5.11.1 Independence in system qualification testing   
5.11.2 Testing on the target computer system   
5.11.3 Preparing for system qualification testing   
5.11.4 Dry run of system qualification testing   
5.11.5 Performing system qualification testing   
5.11.6 Revision and retesting   
5.11.7 Analyzing and recording system qualification test results

## 5.12 Preparing for software use.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for preparing for software
use. The planning in each subparagraph shall cover all contractual
clauses regarding the identified topic.   
5.12.1 Preparing the executable software   
5.12.2 Preparing version descriptions for user sites   
5.12.3 Preparing user manuals   
5.12.4 Installation at user sites

## 5.13 Preparing for software transition.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for preparing for software
transition. The planning in each subparagraph shall cover all
contractual clauses regarding the identified topic.   
5.13.1 Preparing the executable software   
5.13.2 Preparing source files   
5.13.3 Preparing version descriptions for the support site   
5.13.4 Preparing the "as built" CSCI design and other software
support information   
5.13.5 Updating the system design description   
5.13.6 Preparing support manuals   
5.13.7 Transition to the designated support site

## 5.14 Software configuration management.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for software configuration
management. The planning in each subparagraph shall cover all
contractual clauses regarding the identified topic.   
5.14.1 Configuration identification   
5.14.2 Configuration control   
5.14.3 Configuration status accounting   
5.14.4 Configuration audits   
5.14.5 Packaging, storage, handling, and delivery

## 5.15 Software product evaluation.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for software product
evaluation. The planning in each subparagraph shall cover all
contractual clauses regarding the identified topic.   
5.15.1 In-process and final software product evaluations   
5.15.2 Software product evaluation records, including items to be
recorded   
5.15.3 Independence in software product evaluation

## 5.16 Software quality assurance.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for software quality
assurance. The planning in each subparagraph shall cover all
contractual clauses regarding the identified topic.   
5.16.1 Software quality assurance evaluations   
5.16.2 Software quality assurance records, including items to be
recorded   
5.16.3 Independence in software quality assurance

## 5.17 Corrective action.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for corrective action. The
planning in each subparagraph shall cover all contractual clauses
regarding the identified topic.   
5.17.1 Problem/change reports, including items to be recorded
(candidate items include project name, originator, problem number,
problem name, software element or document affected, origination
date, category and priority, description, analyst assigned to the
problem, date assigned, date completed, analysis time, recommended
solution, impacts, problem status, approval of solution, follow-up
actions, corrector, correction date, version where corrected,
correction time, description of solution implemented)   
5.17.2 Corrective action system

## 5.18 Joint technical and management reviews.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for joint technical and
management reviews. The planning in each subparagraph shall cover
all contractual clauses regarding the identified topic.   
5.18.1 Joint technical reviews, including a proposed set of reviews
  
5.18.2 Joint management reviews, including a proposed set of
reviews

## 5.19 Other software development activities.

This paragraph shall be divided into the following subparagraphs to
describe the approach to be followed for other software development
activities. The planning in each subparagraph shall cover all
contractual clauses regarding the identified topic.   
5.19.1 Risk management, including known risks and corresponding
strategies   
5.19.2 Software management indicators, including indicators to be
used   
5.19.3 Security and privacy   
5.19.4 Subcontractor management   
5.19.5 Interface with software independent verification and
validation (IV&V) agents   
5.19.6 Coordination with associate developers   
5.19.7 Improvement of project processes   
5.19.8 Other activities not covered elsewhere in the plan

# 6. Schedules and activity network.

This section shall present:

Schedule(s) identifying the activities in each build and showing
initiation of each activity, availability of draft and final
deliverables and other milestones, and completion of each activity
An activity network, depicting sequential relationships and
dependencies among activities and identifying those activities that
impose the greatest time restrictions on the project
# 7. Project organization and resources.

This section shall be divided into the following paragraphs to
describe the project organization and resources to be applied in
each build.

## 7.1 Project organization.

This paragraph shall describe the organizational structure to be
used on the project, including the organizations involved, their
relationships to one another, and the authority and responsibility
of each organization for carrying out required activities.

## 7.2 Project resources.

This paragraph shall describe the resources to be applied to the
project. It shall include, as applicable:

Personnel resources, including:
1.  The estimated staff-loading for the project (number of
    personnel over time)
2.  The breakdown of the staff-loading numbers by responsibility
    (for example, management, software engineering, software testing,
    software configuration manage-ment, software product evaluation,
    software quality assurance)
3.  A breakdown of the skill levels, geographic locations, and
    security clearances of personnel performing each responsibility

Overview of developer facilities to be used, including geographic
locations in which the work will be performed, facilities to be
used, and secure areas and other features of the facilities as
applicable to the contracted effort.
Acquirer-furnished equipment, software, services, documentation,
data, and facilities required for the contracted effort. A schedule
detailing when these items will be needed shall also be included.
Other required resources, including a plan for obtaining the
resources, dates needed, and availability of each resource item.
# 8. Notes.

This section shall contain any general information that aids in
understanding this document (e.g., background information,
glossary, rationale). This section shall include an alphabetical
listing of all acronyms, abbreviations, and their meanings as used
in this document and a list of any terms and definitions needed to
understand this document.

# A. Appendixes.

Appendixes may be used to provide information published separately
for convenience in document maintenance (e.g., charts, classified
data). As applicable, each appendix shall be referenced in the main
body of the document where the data would normally have been
provided. Appendixes may be bound as separate documents for ease in
handling. Appendixes shall be lettered alphabetically (A, B,
etc.).



