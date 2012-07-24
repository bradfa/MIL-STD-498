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
all documents referenced in this specification. This section shall
also identify the source for all documents not available through
normal Government stocking activities.

# 3. Requirements.

This section shall be divided into the following paragraphs to
achieve delivery of the software and to establish the requirements
that another body of software must meet to be considered a valid
copy of the CSCI.   
Note: In past versions of this DID, Section 3 required a
presentation of the software design describing the "as built"
software. That approach was modeled on hardware development, in
which the product specification presents the final design as the
requirement to which hardware items must be manufactured. For
software, however, this approach does not apply. Software
"manufacturing" consists of electronic duplication of the software
itself, not recreation from design, and the validity of a
"manufactured" copy is determined by comparison to the software
itself, not to a design description. This section therefore
establishes the software itself as the criterion that must be
matched for a body of software to be considered a valid copy of the
CSCI. The updated software design has been placed in Section 5
below, not as a requirement, but as information to be used to
modify, enhance, or otherwise support the software. If any portion
of this specification is placed under acquirer configuration
control, it should be limited to Section 3. It is the software
itself that establishes the product baseline, not a description of
the software's design.

## 3.1 Executable software.

This paragraph shall provide, by reference to enclosed or otherwise
provided electronic media, the executable software for the CSCI,
including any batch files, command files, data files, or other
software files needed to install and operate the software on its
target computer(s). In order for a body of software to be
considered a valid copy of the CSCI's executable software, it must
be shown to match these files exactly.

## 3.2 Source files.

This paragraph shall provide, by reference to enclosed or otherwise
provided electronic media, the source files for the CSCI, including
any batch files, command files, data files, or other files needed
to regenerate the executable software for the CSCI. In order for a
body of software to be considered a valid copy of the CSCI's source
files, it must be shown to match these files exactly.

## 3.3 Packaging requirements.

This paragraph shall state the requirements, if any, for packaging
and marking copies of the CSCI.

# 4. Qualification provisions.

This paragraph shall state the method(s) to be used to demonstrate
that a given body of software is a valid copy of the CSCI. For
example, the method for executable files might be to establish that
each executable file referenced in 3.1 has an identically-named
counterpart in the software in question and that each such
counterpart can be shown, via bit-for-bit comparison, check sum, or
other method, to be identical to the corresponding executable file.
The method for source files might be comparable, using the source
files referenced in 3.2.

# 5. Software support information.

This section shall be divided into the following paragraphs to
provide information needed to support the CSCI.

## 5.1 "As built" software design.

This paragraph shall contain, or reference an appendix or other
deliverable document that contains, information describing the
design of the "as built" CSCI. The information shall be the same as
that required in a Software Design Description (SDD), Interface
Design Description (IDD), and Database Design Description (DBDD),
as applicable. If these documents or their equivalents are to be
delivered for the "as built" CSCI, this paragraph shall reference
them. If not, the information shall be provided in this document.
Information provided in the headers, comments, and code of the
source code listings may be referenced and need not be repeated in
this section. If the SDD, IDD, or DBDD is included in an appendix,
the paragraph numbers and page numbers need not be changed.

## 5.2 Compilation/build procedures.

This paragraph shall describe, or reference an appendix that
describes, the compilation/build process to be used to create the
executable files from the source files and to prepare the
executable files to be loaded into firmware or other distribution
media. It shall specify the compiler(s)/assembler(s) to be used,
including version numbers; other hardware and software needed,
including version numbers; any settings, options, or conventions to
be used; and procedures for compiling/assembling, linking, and
building the CSCI and the software system/subsystem containing the
CSCI, including variations for different sites, configurations,
versions, etc. Build procedures above the CSCI level may be
presented in one SPS and referenced from the others.

## 5.3 Modification procedures.

This paragraph shall describe procedures that must be followed to
modify the CSCI. It shall include or reference information on the
following, as applicable:

1.  Support facilities, equipment, and software, and procedures for
    their use
2.  Databases/data files used by the CSCI and procedures for using
    and modifying them
3.  Design, coding, and other conventions to be followed
4.  Compilation/build procedures if different from those above
5.  Integration and testing procedures to be followed

## 5.4 Computer hardware resource utilization.

This paragraph shall describe the "as built" CSCI's measured
utilization of computer hardware resources (such as processor
capacity, memory capacity, input/output device capacity, auxiliary
storage capacity, and communications/ network equipment capacity).
It shall cover all computer hardware resources included in
utilization requirements for the CSCI, in system-level resource
allocations affecting the CSCI, or in the software development
plan. If all utilization data for a given computer hardware
resource is presented in a single location, such as in one SPS,
this paragraph may reference that source. Included for each
computer hardware resource shall be:

The CSCI requirements or system-level resource allocations being
satisfied. (Alternatively, the traceability to CSCI requirements
may be provided in 6.c.)
The assumptions and conditions on which the utilization data are
based (for example, typical usage, worst-case usage, assumption of
certain events)
Any special considerations affecting the utilization (such as use
of virtual memory, overlays, or multiprocessors or the impacts of
operating system overhead, library software, or other
implementation overhead)
The units of measure used (such as percentage of processor
capacity, cycles per second, bytes of memory, kilobytes per second)
The level(s) at which the estimates or measures have been made
(such as software unit, CSCI, or executable program)
# 6. Requirements traceability.

This section shall provide:

Traceability from each CSCI source file to the software unit(s)
that it implements.
Traceability from each software unit to the source files that
implement it.
Traceability from each computer hardware resource utilization
measurement given in 5.4 to the CSCI requirements it addresses.
(Alternatively, this traceability may be provided in 5.4.)
Traceability from each CSCI requirement regarding computer hardware
resource utilization to the utilization measurements given in 5.4.
# 7. Notes.

This section shall contain any general information that aids in
understanding this specification (e.g., background information,
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



