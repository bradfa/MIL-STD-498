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

This paragraph shall describe the relationship, if any, of the STP
to related project management plans.

# 2. Referenced documents.

This section shall list the number, title, revision, and date of
all documents referenced in this plan. This section shall also
identify the source for all documents not available through normal
Government stocking activities.

# 3. Software test environment.

This section shall be divided into the following paragraphs to
describe the software test environment at each intended test site.
Reference may be made to the Software Development Plan (SDP) for
resources that are described there.

## 3.x (Name of test site(s)).

This paragraph shall identify one or more test sites to be used for
the testing, and shall be divided into the following subparagraphs
to describe the software test environment at the site(s). If all
tests will be conducted at a single site, this paragraph and its
subparagraphs shall be presented only once. If multiple test sites
use the same or similar software test environments, they may be
discussed together. Duplicative information among test site
descriptions may be reduced by referencing earlier descriptions.

### 3.x.1 Software items.

This paragraph shall identify by name, number, and version, as
applicable, the software items (e.g., operating systems, compilers,
communications software, related applications software, databases,
input files, code auditors, dynamic path analyzers, test drivers,
preprocessors, test data generators, test control software, other
special test software, post processors) necessary to perform the
planned testing activities at the test site(s). This paragraph
shall describe the purpose of each item, describe its media (tape,
disk, etc.), identify those that are expected to be supplied by the
site, and identify any classified processing or other security or
privacy issues associated with the software items.

### 3.x.2 Hardware and firmware items.

This paragraph shall identify by name, number, and version, as
applicable, the computer hardware, interfacing equipment,
communications equipment, test data reduction equipment, apparatus
such as extra peripherals (tape drives, printers, plotters), test
message generators, test timing devices, test event records, etc.,
and firmware items that will be used in the software test
environment at the test site(s). This paragraph shall describe the
purpose of each item, state the period of usage and the number of
each item needed, identify those that are expected to be supplied
by the site, and identify any classified processing or other
security or privacy issues associated with the items.

### 3.x.3 Other materials.

This paragraph shall identify and describe any other materials
needed for the testing at the test site(s). These materials may
include manuals, software listings, media containing the software
to be tested, media containing data to be used in the tests, sample
listings of outputs, and other forms or instructions. This
paragraph shall identify those items that are to be delivered to
the site and those that are expected to be supplied by the site.
The description shall include the type, layout, and quantity of the
materials, as applicable. This paragraph shall identify any
classified processing or other security or privacy issues
associated with the items.

### 3.x.4 Proprietary nature, acquirer's rights, and licensing.

This paragraph shall identify the proprietary nature, acquirer's
rights, and licensing issues associated with each element of the
software test environment.

### 3.x.5 Installation, testing, and control.

This paragraph shall identify the developer's plans for performing
each of the following, possibly in conjunction with personnel at
the test site(s):

1.  Acquiring or developing each element of the software test
    environment
2.  Installing and testing each item of the software test
    environment prior to its use
3.  Controlling and maintaining each item of the software test
    environment

### 3.x.6 Participating organizations.

This paragraph shall identify the organizations that will
participate in the testing at the test sites(s) and the roles and
responsibilities of each.

### 3.x.7 Personnel.

This paragraph shall identify the number, type, and skill level of
personnel needed during the test period at the test site(s), the
dates and times they will be needed, and any special needs, such as
multishift operation and retention of key skills to ensure
continuity and consistency in extensive test programs.

### 3.x.8 Orientation plan.

This paragraph shall describe any orientation and training to be
given before and during the testing. This information shall be
related to the personnel needs given in 3.x.7. This training may
include user instruction, operator instruction, maintenance and
control group instruction, and orientation briefings to staff
personnel. If extensive training is anticipated, a separate plan
may be developed and referenced here.

### 3.x.9 Tests to be performed.

This paragraph shall identify, by referencing section 4, the tests
to be performed at the test site(s).

# 4. Test identification.

This section shall be divided into the following paragraphs to
identify and describe each test to which this STP applies.

## 4.1 General information.

This paragraph shall be divided into subparagraphs to present
general information applicable to the overall testing to be
performed.

### 4.1.1 Test levels.

This paragraph shall describe the levels at which testing will be
performed, for example, CSCI level or system level.

### 4.1.2 Test classes.

This paragraph shall describe the types or classes of tests that
will be performed (for example, timing tests, erroneous input
tests, maximum capacity tests).

### 4.1.3 General test conditions.

This paragraph shall describe conditions that apply to all of the
tests or to a group of tests. For example: "Each test shall include
nominal, maximum, and minimum values;" "each test of type x shall
use live data;" "execution size and time shall be measured for each
CSCI." Included shall be a statement of the extent of testing to be
performed and rationale for the extent selected. The extent of
testing shall be expressed as a percentage of some well defined
total quantity, such as the number of samples of discrete operating
conditions or values, or other sampling approach. Also included
shall be the approach to be followed for retesting/regression
testing.

### 4.1.4 Test progression.

In cases of progressive or cumulative tests, this paragraph shall
explain the planned sequence or progression of tests.

### 4.1.5 Data recording, reduction, and analysis.

This paragraph shall identify and describe the data recording,
reduction, and analysis procedures to be used during and after the
tests identified in this STP. These procedures shall include, as
applicable, manual, automatic, and semi-automatic techniques for
recording test results, manipulating the raw results into a form
suitable for evaluation, and retaining the results of data
reduction and analysis.

## 4.2 Planned tests.

This paragraph shall be divided into the following subparagraphs to
describe the total scope of the planned testing.

### 4.2.x (Item(s) to be tested).

This paragraph shall identify a CSCI, subsystem, system, or other
entity by name and project unique identifier, and shall be divided
into the following subparagraphs to describe the testing planned
for the item(s). (Note: the "tests" in this plan are collections of
test cases. There is no intent to describe each test case in this
document.)

#### 4.2.x.y (Project-unique identifier of a test).

This paragraph shall identify a test by project unique identifier
and shall provide the information specified below for the test.
Reference may be made as needed to the general information in 4.1.

1.  Test objective
2.  Test level
3.  Test type or class
4.  Qualification method(s) as specified in the requirements
    specification
5.  Identifier of the CSCI requirements and, if applicable,
    software system requirements addressed by this test.
    (Alternatively, this information may be provided in Section 6.)
6.  Special requirements (for example, 48 hours of continuous
    facility time, weapon simulation, extent of test, use of a special
    input or database)
7.  Type of data to be recorded
8.  Type of data recording/reduction/analysis to be employed
9.  Assumptions and constraints, such as anticipated limitations on
    the test due to system or test conditions--timing, interfaces,
    equipment, personnel, database, etc.
10. Safety, security, and privacy considerations associated with
    the test

# 5. Test schedules.

This section shall contain or reference the schedules for
conducting the tests identified in this plan. It shall include:

A listing or chart depicting the sites at which the testing will be
scheduled and the time frames during which the testing will be
conducted
A schedule for each test site depicting the activities and events
listed below, as applicable, in chronological order with supporting
narrative as necessary:
1.  On site test period and periods assigned to major portions of
    the testing
2.  Pretest on site period needed for setting up the software test
    environment and other equipment, system debugging, orientation, and
    familiarization
3.  Collection of database/data file values, input values, and
    other operational data needed for the testing
4.  Conducting the tests, including planned retesting
5.  Preparation, review, and approval of the Software Test Report
    (STR)

# 6. Requirements traceability.

This paragraph shall contain:

Traceability from each test identified in this plan to the CSCI
requirements and, if applicable, software system requirements it
addresses. (Alternatively, this traceability may be provided in
4.2.x.y and referenced from this paragraph.)
Traceability from each CSCI requirement and, if applicable, each
software system requirement covered by this test plan to the
test(s) that address it. The traceability shall cover the CSCI
requirements in all applicable Software Requirements Specifications
(SRSs) and associated Interface Requirements Specifications (IRSs),
and, for software systems, the system requirements in all
applicable System/ Subsystem Specifications (SSSs) and associated
system-level IRSs.
# 7. Notes.

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



