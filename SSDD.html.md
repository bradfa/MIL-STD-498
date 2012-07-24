# 1. Scope.

This section shall be divided into the following paragraphs.

## 1.1 Identification.

This paragraph shall contain a full identification of the system to
which this document applies, including, as applicable,
identification number(s), title(s), abbreviation(s), version
number(s), and release number(s).

## 1.2 System overview.

This paragraph shall briefly state the purpose of the system to
which this document applies. It shall describe the general nature
of the system; summarize the history of system development,
operation, and maintenance; identify the project sponsor, acquirer,
user, developer, and support agencies; identify current and planned
operating sites; and list other relevant documents.

## 1.3 Document overview.

paragraph shall summarize the purpose and contents of this document
and shall describe any security or privacy considerations
associated with its use.

# 2. Referenced documents.

This section shall list the number, title, revision, and date of
all documents referenced in this document. This section shall also
identify the source for all documents not available through normal
Government stocking activities.

# 3. System-wide design decisions.

This section shall be divided into paragraphs as needed to present
system-wide design decisions, that is, decisions about the system's
behavioral design (how it will behave, from a user's point of view,
in meeting its requirements, ignoring internal implementation) and
other decisions affecting the selection and design of system
components. If all such decisions are explicit in the requirements
or are deferred to the design of the system components, this
section shall so state. Design decisions that respond to
requirements designated critical, such as those for safety,
security, or privacy, shall be placed in separate subparagraphs. If
a design decision depends upon system states or modes, this
dependency shall be indicated. Design conventions needed to
understand the design shall be presented or referenced. Examples of
system-wide design decisions are the following:

Design decisions regarding inputs the system will accept and
outputs it will produce, including interfaces with other systems,
configuration items, and users (4.3.x of this DID identifies topics
to be considered in this description). If part or all of this
information is given in Interface Design Descriptions (IDDs), they
may be referenced.
Design decisions on system behavior in response to each input or
condition, including actions the system will perform, response
times and other performance characteristics, description of
physical systems modeled, selected equations/algorithms/ rules, and
handling of unallowed inputs or conditions.
Design decisions on how system databases/data files will appear to
the user (4.3.x of this DID identifies topics to be considered in
this description). If part or all of this information is given in
Database Design Descriptions (DBDDs), they may be referenced.
Selected approach to meeting safety, security, and privacy
requirements.
Design and construction choices for hardware or hardware-software
systems, such as physical size, color, shape, weight, materials,
and markings.
Other system-wide design decisions made in response to
requirements, such as selected approach to providing required
flexibility, availability, and maintainability.
# 4. System architectural design.

This section shall be divided into the following paragraphs to
describe the system architectural design. If part or all of the
design depends upon system states or modes, this dependency shall
be indicated. If design information falls into more than one
paragraph, it may be presented once and referenced from the other
paragraphs. Design conventions needed to understand the design
shall be presented or referenced.   
Note: For brevity, this section is written in terms of organizing a
system directly into Hardware Configuration Items (HWCIs), Computer
Software Configuration Items (CSCIs), and manual operations, but
should be interpreted to cover organizing a system into subsystems,
organizing a subsystem into HWCIs, CSCIs, and manual operations, or
other variations as appropriate.

## 4.1 System components.

This paragraph shall:

Identify the components of the system (HWCIs, CSCIs, and manual
operations). Each component shall be assigned a project-unique
identifier. Note: a database may be treated as a CSCI or as part of
a CSCI.
Show the static (such as "consists of") relationship(s) of the
components. Multiple relationships may be presented, depending on
the selected design methodology.
State the purpose of each component and identify the system
requirements and system-wide design decisions allocated to it.
(Alternatively, the allocation of requirements may be provided in
5.a.)
Identify each component's development status/type, if known (such
as new development, existing component to be reused as is, existing
design to be reused as is, existing design or component to be
reengineered, component to be developed for reuse, component
planned for Build N, etc.) For existing design or components, the
description shall provide identifying information, such as name,
version, documentation references, location, etc.
For each computer system or other aggregate of computer hardware
resources identified for use in the system, describe its computer
hardware resources (such as processors, memory, input/output
devices, auxiliary storage, and communications/ network equipment).
Each description shall, as applicable, identify the configuration
items that will use the resource, describe the allocation of
resource utilization to each CSCI that will use the resource (for
example, 20% of the resource's capacity allocated to CSCI 1, 30% to
CSCI 2), describe the conditions under which utilization will be
measured, and describe the characteristics of the resource:
Descriptions of computer processors shall include, as applicable,
manufacturer name and model number, processor speed/capacity,
identification of instruction set architecture, applicable
compiler(s), word size (number of bits in each computer word),
character set standard (such as ASCII, EBCDIC), and interrupt
capabilities.
Descriptions of memory shall include, as applicable, manufacturer
name and model number and memory size, type, speed, and
configuration (such as 256K cache memory, 16MB RAM (4MB x 4)).
Descriptions of input/output devices shall include, as applicable,
manufacturer name and model number, type of device, and device
speed/capacity.
Descriptions of auxiliary storage shall include, as applicable,
manufacturer name and model number, type of storage, amount of
installed storage, and storage speed.
Descriptions of communications/network equipment, such as modems,
network interface cards, hubs, gateways, cabling, high speed data
lines, or aggregates of these or other components, shall include,
as applicable, manufacturer name and model number, data transfer
rates/capacities, network topologies, transmission techniques, and
protocols used.
Each description shall also include, as applicable, growth
capabilities, diagnostic capabilities, and any additional hardware
capabilities relevant to the description.
Present a specification tree for the system, that is, a diagram
that identifies and shows the relationships among the planned
specifications for the system components.
## 4.2 Concept of execution.

This paragraph shall describe the concept of execution among the
system components. It shall include diagrams and descriptions
showing the dynamic relationship of the components, that is, how
they will interact during system operation, including, as
applicable, flow of execution control, data flow, dynamically
controlled sequencing, state transition diagrams, timing diagrams,
priorities among components, handling of interrupts,
timing/sequencing relationships, exception handling, concurrent
execution, dynamic allocation/deallocation, dynamic
creation/deletion of objects, processes, tasks, and other aspects
of dynamic behavior.

## 4.3 Interface design.

This paragraph shall be divided into the following subparagraphs to
describe the interface characteristics of the system components. It
shall include both interfaces among the components and their
interfaces with external entities such as other systems,
configuration items, and users. Note: There is no requirement for
these interfaces to be completely designed at this level; this
paragraph is provided to allow the recording of interface design
decisions made as part of system architectural design. If part or
all of this information is contained in Interface Design
Descriptions (IDDs) or elsewhere, these sources may be referenced.

### 4.3.1 Interface identification and diagrams.

This paragraph shall state the project-unique identifier assigned
to each interface and shall identify the interfacing entities
(systems, configuration items, users, etc.) by name, number,
version, and documentation references, as applicable. The
identification shall state which entities have fixed interface
characteristics (and therefore impose interface requirements on
interfacing entities) and which are being developed or modified
(thus having interface requirements imposed on them). One or more
interface diagrams shall be provided, as appropriate, to depict the
interfaces.

### 4.3.x (Project unique identifier of interface).

This paragraph (beginning with 4.3.2) shall identify an interface
by project unique identifier, shall briefly identify the
interfacing entities, and shall be divided into subparagraphs as
needed to describe the interface characteristics of one or both of
the interfacing entities. If a given interfacing entity is not
covered by this SSDD (for example, an external system) but its
interface characteristics need to be mentioned to describe
interfacing entities that are, these characteristics shall be
stated as assumptions or as "When [the entity not covered] does
this, [the entity that is covered] will ...." This paragraph may
reference other documents (such as data dictionaries, standards for
protocols, and standards for user interfaces) in place of stating
the information here. The design description shall include the
following, as applicable, presented in any order suited to the
information to be provided, and shall note any differences in these
characteristics from the point of view of the interfacing entities
(such as different expectations about the size, frequency, or other
characteristics of data elements):

Priority assigned to the interface by the interfacing entity(ies)
Type of interface (such as real-time data transfer,
storage-and-retrieval of data, etc.) to be implemented
Characteristics of individual data elements that the interfacing
entity(ies) will provide, store, send, access, receive, etc., such
as:
1.  Names/identifiers
    1.  Project-unique identifier
    2.  Non-technical (natural-language) name
    3.  DoD standard data element name
    4.  Technical name (e.g., variable or field name in code or
        database)
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

Sources (setting/sending entities) and recipients (using/receiving
entities)
1.  Names/identifiers
    1.  Project-unique identifier to be used for traceability
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
# 5. Requirements traceability.

This paragraph shall contain:

Traceability from each system component identified in this SSDD to
the system requirements allocated to it. (Alternatively, this
traceability may be provided in 4.1.)
Traceability from each system requirement to the system components
to which it is allocated.
# 6. Notes.

This section shall contain any general information that aids in
understanding this document (e.g., background information,
glossary, rationale). This section shall contain an alphabetical
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



