# 1. Scope.

This section shall be divided into the following paragraphs.

## 1.1 Identification.

This paragraph shall contain a full identification of the database
to which this document applies, including, as applicable,
identification number(s), title(s), abbreviation(s), version
number(s), and release number(s).

## 1.2 Database overview.

This paragraph shall briefly state the purpose of the database to
which this document applies. It shall describe the general nature
of the database; summarize the history of its development, use, and
maintenance; identify the project sponsor, acquirer, user,
developer, and support agencies; identify current and planned
operating sites; and list other relevant documents.

## 1.3 Document overview.

This paragraph shall summarize the purpose and contents of this
document and shall describe any security or privacy considerations
associated with its use.

# 2. Referenced documents.

This section shall list the number, title, revision, and date of
all documents referenced in this manual. This section shall also
identify the source for all documents not available through normal
Government stocking activities.

# 3. Database-wide design decisions.

This section shall be divided into paragraphs as needed to present
database-wide design decisions, that is, decisions about the
database's behavioral design (how it will behave, from a user's
point of view, in meeting its requirements, ignoring internal
implementation) and other decisions affecting further design of the
database. If all such decisions are explicit in the system or CSCI
requirements, this section shall so state. Design decisions that
respond to requirements designated critical, such as those for
safety, security, or privacy, shall be placed in separate
subparagraphs. If a design decision depends upon system states or
modes, this dependency shall be indicated. If some or all of the
design decisions are described in the documentation of a custom or
commercial database management system (DBMS), they may be
referenced from this section. Design conventions needed to
understand the design shall be presented or referenced. Examples of
database-wide design decisions are the following:

Design decisions regarding queries or other inputs the database
will accept and outputs (displays, reports, messages, responses,
etc.) it will produce, including interfaces with other systems,
HWCIs, CSCIs, and users (5.x.d of this DID identifies topics to be
considered in this description). If part or all of this information
is given in Interface Design Descriptions (IDDs), they may be
referenced.
Design decisions on database behavior in response to each input or
query, including actions, response times and other performance
characteristics, selected equations/algorithms/rules, disposition,
and handling of unallowed inputs
Design decisions on how databases/data files will appear to the
user (4.x of this DID identifies topics to be considered in this
description)
Design decisions on the database management system to be used
(including name, version/release) and the type of flexibility to be
built into the database for adapting to changing requirements
Design decisions on the levels and types of availability, security,
privacy, and continuity of operations to be offered by the database
Design decisions on database distribution (such as client/server),
master database file updates and maintenance, including maintaining
consistency, establishing/ reestablishing and maintaining
synchronization, enforcing integrity and business rules
Design decisions on backup and restoration including data and
process distribution strategies, permissible actions during backup
and restoration, and special considerations for new or non-standard
technologies such as video and sound
Design decisions on repacking, sorting, indexing, synchronization,
and consistency including automated disk management and space
reclamation considerations, optimizing strategies and
considerations, storage and size considerations, and population of
the database and capture of legacy data
# 4. Detailed design of the database.

This section shall be divided into paragraphs as needed to describe
the detailed design of the database. The number of levels of design
and the names of those levels shall be based on the design
methodology used. Examples of database design levels include
conceptual, internal, logical, and physical. If part or all of the
design depends upon system states or modes, this dependency shall
be indicated. Design conventions needed to understand the design
shall be presented or referenced.   
Note: This DID uses the term "data element assembly" to mean any
entity, relation, schema, field, table, array, etc., that has
structure (number/order/grouping of data elements) at a given
design level (e.g., conceptual, internal, logical, physical) and
the term "data element" to mean any relation, attribute, field,
cell, data element, etc. that does not have structure at that
level.

## 4.x (Name of database design level).

This paragraph shall identify a database design level and shall
describe the data elements and data element assemblies of the
database in the terminology of the selected design method. The
information shall include the following, as applicable, presented
in any order suited to the information to be provided:

Characteristics of individual data elements in the database design,
such as:
1.  Names/identifiers
    1.  Project-unique identifier
    2.  Non-technical (natural-language) name
    3.  DoD standard data element name
    4.  Technical name (e.g., field name in the database)
    5.  Abbreviation or synonymous names

2.  Data type (alphanumeric, integer, etc.)
3.  Size and format (such as length and punctuation of a character
    string)
4.  Units of measurement (such as meters, dollars, nanoseconds)
5.  Range or enumeration of possible values (such as 0-99)
6.  Accuracy (how correct) and precision (number of significant
    digits)
7.  Priority, timing, frequency, volume, sequencing, and other
    constraints, such as whether the data element may be updated and
    whether business rules apply
8.  Security and privacy constraints
9.  Sources (setting/sending entities) and recipients
    (using/receiving entities)

Characteristics of data element assemblies (records, messages,
files, arrays, displays, reports, etc.) in the database design,
such as:
1.  Names/identifiers
    1.  Project-unique identifier
    2.  Non-technical (natural language) name
    3.  Technical name (e.g., record or data structure name in code or
        database)
    4.  Abbreviations or synonymous names

2.  Data elements in the assembly and their structure (number,
    order, grouping)
3.  Medium (such as disk) and structure of data elements/assemblies
    on the medium
4.  Visual and auditory characteristics of displays and other
    outputs (such as colors, layouts, fonts, icons and other display
    elements, beeps, lights)
5.  Relationships among assemblies, such as sorting/access
    characteristics
6.  Priority, timing, frequency, volume, sequencing, and other
    constraints, such as whether the assembly may be updated and
    whether business rules apply
7.  Security and privacy constraints
8.  Sources (setting/sending entities) and recipients
    (using/receiving entities)

# 5. Detailed design of software units used for database access or manipulation.

This section shall be divided into the following paragraphs to
describe each software unit used for database access or
manipulation. If part or all of this information is provided
elsewhere, such as in a Software Design Description (SDD), the SDD
for a customized DBMS, or the user manual of a commercial DBMS,
that information may be referenced rather than repeated here. If
part or all of the design depends upon system states or modes, this
dependency shall be indicated. If design information falls into
more than one paragraph, it may be presented once and referenced
from the other paragraphs. Design conventions needed to understand
the design shall be presented or referenced.

## 5.x (Project-unique identifier of a software unit, or designator for a group of software units).

This paragraph shall identify a software unit by project-unique
identifier and shall describe the unit. The description shall
include the following information, as applicable. Alternatively,
this paragraph may designate a group of software units and identify
and describe the software units in subparagraphs. Software units
that contain other software units may reference the descriptions of
those units rather than repeating information.

Unit design decisions, if any, such as algorithms to be used, if
not previously selected
Any constraints, limitations, or unusual features in the design of
the software unit
The programming language to be used and rationale for its use if
other than the specified CSCI language
If the software unit consists of or contains procedural commands
(such as menu selections in a database management system (DBMS) for
defining forms and reports, on-line DBMS queries for database
access and manipulation, input to a graphical user interface (GUI)
builder for automated code generation, commands to the operating
system, or shell scripts), a list of the procedural commands and a
reference to user manuals or other documents that explain them
If the software unit contains, receives, or outputs data, a
description of its inputs, outputs, and other data elements and
data element assemblies, as applicable. Data local to the software
unit shall be described separately from data input to or output
from the software unit. Interface characteristics may be provided
here or by referencing Interface Design Description(s). If a given
interfacing entity is not covered by this DBDD (for example, an
external system) but its interface characteristics need to be
mentioned to describe software units that are, these
characteristics shall be stated as assumptions or as "When [the
entity not covered] does this, [the software unit] will...." This
paragraph may reference other documents (such as data dictionaries,
standards for protocols, and standards for user interfaces) in
place of stating the information here. The design description shall
include the following, as applicable, presented in any order suited
to the information to be provided, and shall note any differences
in these characteristics from the point of view of the interfacing
entities (such as different expectations about the size, frequency,
or other characteristics of data elements):
Project-unique identifier for the interface
Identification of the interfacing entities (software units,
configuration items, users, etc.) by name, number, version, and
documentation references, as applicable
Priority assigned to the interface by the interfacing entity(ies)
Type of interface (such as real-time data transfer,
storage-and-retrieval of data, etc.) to be implemented
Characteristics of individual data elements that the interfacing
entity(ies) will provide, store, send, access, receive, etc.
Paragraph 4.x.a of this DID identifies topics to be covered in this
description.
Characteristics of data element assemblies (records, messages,
files, arrays, displays, reports, etc.) that the interfacing
entity(ies) will provide, store, send, access, receive, etc.
Paragraph 4.x.b of this DID identifies topics to be covered in this
description.
Characteristics of communication methods that the interfacing
entity(ies) will use for the interface, such as:
1.  Project-unique identifier(s)
2.  Communication links/bands/frequencies/media and their
    characteristics
3.  Message formatting
4.  Flow control (such as sequence numbering and buffer allocation)
5.  Data transfer rate, whether periodic/aperiodic, and interval
    between transfers
6.  Routing, addressing, and naming conventions
7.  Transmission services, including priority and grade
8.  Safety/security/privacy considerations, such as encryption,
    user authentication, compartmentalization, and auditing

Characteristics of protocols that the interfacing entity(ies) will
use for the interface, such as:
1.  Project-unique identifier(s)
2.  Priority/layer of the protocol
3.  Packeting, including fragmentation and reassembly, routing, and
    addressing
4.  Legality checks, error control, and recovery procedures
5.  Synchronization, including connection establishment,
    maintenance, termination
6.  Status, identification, and any other reporting features

Other characteristics, such as physical compatibility of the
interfacing entity(ies) (dimensions, tolerances, loads, voltages,
plug compatibility, etc.)
If the software unit contains logic, the logic to be used by the
software unit, including, as applicable:
1.  Conditions in effect within the software unit when its
    execution is initiated
2.  Conditions under which control is passed to other software
    units
3.  Response and response time to each input, including data
    conversion, renaming, and data transfer operations
4.  Sequence of operations and dynamically controlled sequencing
    during the software unit's operation, including:
    1.  The method for sequence control
    2.  The logic and input conditions of that method, such as timing
        variations, priority assignments
    3.  Data transfer in and out of memory
    4.  The sensing of discrete input signals, and timing relationships
        between interrupt operations within the software unit

5.  Exception and error handling

# 6. Requirements traceability.

This section shall contain:

1.  Traceability from each database or other software unit covered
    by this DBDD to the system or CSCI requirements it addresses.
2.  Traceability from each system or CSCI requirement that has been
    allocated to a database or other software unit covered in this DBDD
    to the database or other software units that address it.

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



