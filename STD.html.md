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

# 2. Referenced documents.

This section shall list the number, title, revision, and date of
all documents referenced in this document. This section shall also
identify the source for all documents not available through normal
Government stocking activities.

# 3. Test preparations.

This section shall be divided into the following paragraphs. Safety
precautions, marked by WARNING or CAUTION, and security and privacy
considerations shall be included as applicable.

## 3.x (Project unique identifier of a test).

This paragraph shall identify a test by project-unique identifier,
shall provide a brief description, and shall be divided into the
following subparagraphs. When the information required duplicates
information previously specified for another test, that information
may be referenced rather than repeated.

### 3.x.1 Hardware preparation.

This paragraph shall describe the procedures necessary to prepare
the hardware for the test. Reference may be made to published
operating manuals for these procedures. The following shall be
provided, as applicable:

1.  The specific hardware to be used, identified by name and, if
    applicable, number
2.  Any switch settings and cabling necessary to connect the
    hardware
3.  One or more diagrams to show hardware, interconnecting control,
    and data paths
4.  Step-by-step instructions for placing the hardware in a state
    of readiness

### 3.x.2 Software preparation.

This paragraph shall describe the procedures necessary to prepare
the item(s) under test and any related software, including data,
for the test. Reference may be made to published software manuals
for these procedures. The following information shall be provided,
as applicable:

1.  The specific software to be used in the test
2.  The storage medium of the item(s) under test (e.g., magnetic
    tape, diskette)
3.  The storage medium of any related software (e.g., simulators,
    test drivers, databases)
4.  Instructions for loading the software, including required
    sequence
5.  Instructions for software initialization common to more than
    one test case

### 3.x.3 Other pre test preparations.

This paragraph shall describe any other pre-test personnel actions,
preparations, or procedures necessary to perform the test.

# 4. Test descriptions.

This section shall be divided into the following paragraphs. Safety
precautions, marked by WARNING or CAUTION, and security and privacy
considerations shall be included as applicable.

## 4.x (Project unique identifier of a test).

This paragraph shall identify a test by project unique identifier
and shall be divided into the following subparagraphs. When the
required information duplicates information previously provided,
that information may be referenced rather than repeated.

### 4.x.y (Project-unique identifier of a test case).

This paragraph shall identify a test case by project unique
identifier, state its purpose, and provide a brief description. The
following subparagraphs shall provide a detailed description of the
test case.

#### 4.x.y.1 Requirements addressed.

This paragraph shall identify the CSCI or system requirements
addressed by the test case. (Alternatively, this information may be
provided in 5.a.)

#### 4.x.y.2 Prerequisite conditions.

This paragraph shall identify any prerequisite conditions that must
be established prior to performing the test case. The following
considerations shall be discussed, as applicable:

1.  Hardware and software configuration
2.  Flags, initial breakpoints, pointers, control parameters, or
    initial data to be set/reset prior to test commencement
3.  Preset hardware conditions or electrical states necessary to
    run the test case
4.  Initial conditions to be used in making timing measurements
5.  Conditioning of the simulated environment
6.  Other special conditions peculiar to the test case

#### 4.x.y.3 Test inputs.

This paragraph shall describe the test inputs necessary for the
test case. The following shall be provided, as applicable:

1.  Name, purpose, and description (e.g., range of values,
    accuracy) of each test input
2.  Source of the test input and the method to be used for
    selecting the test input
3.  Whether the test input is real or simulated
4.  Time or event sequence of test input
5.  The manner in which the input data will be controlled to:
    1.  Test the item(s) with a minimum/reasonable number of data types
        and values
    2.  Exercise the item(s) with a range of valid data types and
        values that test for overload, saturation, and other "worst case"
        effects
    3.  Exercise the item(s) with invalid data types and values to test
        for appropriate handling of irregular inputs
    4.  Permit retesting, if necessary


#### 4.x.y.4 Expected test results.

This paragraph shall identify all expected test results for the
test case. Both intermediate and final test results shall be
provided, as applicable.

#### 4.x.y.5 Criteria for evaluating results.

This paragraph shall identify the criteria to be used for
evaluating the intermediate and final results of the test case. For
each test result, the following information shall be provided, as
applicable:

1.  The range or accuracy over which an output can vary and still
    be acceptable
2.  Minimum number of combinations or alternatives of input and
    output conditions that constitute an acceptable test result
3.  Maximum/minimum allowable test duration, in terms of time or
    number of events
4.  Maximum number of interrupts, halts, or other system breaks
    that may occur
5.  Allowable severity of processing errors
6.  Conditions under which the result is inconclusive and re
    testing is to be performed
7.  Conditions under which the outputs are to be interpreted as
    indicating irregularities in input test data, in the test
    database/data files, or in test procedures
8.  Allowable indications of the control, status, and results of
    the test and the readiness for the next test case (may be output of
    auxiliary test software)
9.  Additional criteria not mentioned above.

#### 4.x.y.6 Test procedure.

This paragraph shall define the test procedure for the test case.
The test procedure shall be defined as a series of individually
numbered steps listed sequentially in the order in which the steps
are to be performed. For convenience in document maintenance, the
test procedures may be included as an appendix and referenced in
this paragraph. The appropriate level of detail in each test
procedure depends on the type of software being tested. For some
software, each keystroke may be a separate test procedure step; for
most software, each step may include a logically related series of
keystrokes or other actions. The appropriate level of detail is the
level at which it is useful to specify expected results and compare
them to actual results. The following shall be provided for each
test procedure, as applicable:

Test operator actions and equipment operation required for each
step, including commands, as applicable, to:
1.  Initiate the test case and apply test inputs
2.  Inspect test conditions
3.  Perform interim evaluations of test results
4.  Record data
5.  Halt or interrupt the test case
6.  Request data dumps or other aids, if needed
7.  Modify the database/data files
8.  Repeat the test case if unsuccessful
9.  Apply alternate modes as required by the test case
10. Terminate the test case

Expected result and evaluation criteria for each step
If the test case addresses multiple requirements, identification of
which test procedure step(s) address which requirements.
(Alternatively, this information may be provided in 5.)
Actions to follow in the event of a program stop or indicated
error, such as:
1.  Recording of critical data from indicators for reference
    purposes
2.  Halting or pausing time sensitive test support software and
    test apparatus
3.  Collection of system and operator records of test results

Procedures to be used to reduce and analyze test results to
accomplish the following, as applicable:
1.  Detect whether an output has been produced
2.  Identify media and location of data produced by the test case
3.  Evaluate output as a basis for continuation of test sequence
4.  Evaluate test output against required output

#### 4.x.y.7 Assumptions and constraints.

This paragraph shall identify any assumptions made and constraints
or limitations imposed in the description of the test case due to
system or test conditions, such as limitations on timing,
interfaces, equipment, personnel, and database/data files. If
waivers or exceptions to specified limits and parameters are
approved, they shall be identified and this paragraph shall address
their effects and impacts upon the test case.

# 5. Requirements traceability.

This paragraph shall contain:

1.  Traceability from each test case in this STD to the system or
    CSCI requirements it addresses. If a test case addresses multiple
    requirements, traceability from each set of test procedure steps to
    the requirement(s) addressed. (Alternatively, this traceability may
    be provided in 4.x.y.1.)
2.  Traceability from each system or CSCI requirement covered by
    this STD to the test case(s) that address it. For CSCI testing,
    traceability from each CSCI requirement in the CSCI's Software
    Requirements Specification (SRS) and associated Interface
    Requirements Specifications (IRSs). For system testing,
    traceability from each system requirement in the system's
    System/Subsystem Specification (SSS) and associated IRSs. If a test
    case addresses multiple requirements, the traceability shall
    indicate the particular test procedure steps that address each
    requirement.

# 6. Notes.

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



