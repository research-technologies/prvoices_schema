# prvoices_schema
## Introduction
The metadata properties described below relate to the 'Portfolio' item type.  
All fields are multiple unless specified otherwise.   
Fields do not have restrictions unless specified.

## PR Voices Metadata Properties
### Title
- **Type**: Text
- **Editable in workflow**: TRUE
- **Multiple**: FALSE
- **API Code**: dc:attribute:title

### Creators
- **Type**: Author citation [plugin]
- **Editable in workflow**: TRUE
- **Alias of**: Authors
- **API Code**: hres:attribute:authors-citation

### Collaborators
- **Type**: Author citation [plugin]
- **Qualifiers**: Can be one of:
  - Actor
  - Animator
  - Author of introduction
  - Author of screenplay
  - Calligrapher
  - Choreographer
  - Cinematographer
  - Composer
  - Conductor
  - Conference organizer
  - Costume designer
  - Curator
  - Dancer
  - Designer
  - Director
  - Exhibitor
  - Film editor
  - Illustrator
  - Instrumentallist
  - Librettist
  - Lighting designer
  - Lyricist
  - Musician
  - Performer
  - Photographer
  - Printmaker
  - Producer
  - Production personnel
  - Programmer
  - Recording engineer
  - Researcher
  - Set designer
  - Singer
  - Translator
  - Videographer
  - Vocalist
- **Editable in workflow**: TRUE
- **API Code**: hres:attribute:contributors

### Description
- **Type**: Text (paragraph)
- **Editable in workflow**: TRUE
- **Alias of**: Abstract
- **API Code**: hres:aliased-attribute:description

### Context Statement
- **Type**: Text (single line)
- **Editable in workflow**: TRUE
- **API Code**: prvoices:attribute:context-statement

### Keywords
- **Type**: Text (single line)
- **Editable in workflow**: TRUE
- **API Code**: hres:attribute:keywords

### Publisher
- **Type**: Lookup on Publisher object
- **Editable in workflow**: TRUE
- **API Code**: dc:attribute:publisher

### Digital Object Identifier (DOI)
- **Type**: Digital Object Identifier [plugin]
- **Editable in workflow**: TRUE
- **API Code**: hres:attribute:digital-object-identifier-doi

### Web Address (URL)
- **Type**: Web address (URL)
- **Editable in workflow**: TRUE
- **API Code**: std:attribute:url

### Research Area (CREAM only)
- **Type**: Lookup on Subject object
- **Editable in workflow**: TRUE
- **API Code**: dc:attribute:subject

### Funder
- **Type**: Lookup on Funder object
- **Editable in workflow**: TRUE
- **API Code**: hres:attribute:funder

### Date Range of Outputs
- **Type**: Date and time. Precise to day. Entered as range. 
- **Editable in workflow**: TRUE
- **API Code**: prvoices:attribute:portfolio-date-range

### Project
- **Type**: Lookup on Project object
- **Editable in workflow**: TRUE
- **API Code**: std:attribute:project

### Research Group
- **Type**: Lookup on Research Group and Research Group (Past) objects
- **Editable in workflow**: TRUE
- **API Code**: hres:attribute:research-group

### Portfolio Items
- **Type**: Look up on other objects of the following types:
  - Artefact
  - Article
  - Book
  - Book chapter
  - Composition
  - Conference item
  - Dataset
  - Design
  - Devices and products
  - Digital or visual media
  - Exhibition
  - Online educational resource
  - Other
  - Patent
  - Performance
  - Report
  - Software
  - Thesis
  - Website
- **Editable in workflow**: TRUE
- **API Code**: hres:attribute:collection-item

### Related video
- **Type**: Web address (URL)
- **Editable in workflow**: TRUE
- **API Code**: prvoices:attribute:related-video

### Related Output
- **Type**: ???
- **Qualifiers**: Relation can be one of
  - Cites
  - Compiles
  - Continues
  - Describes
  - Documents
  - Has metadata
  - Has part
  - Has version
  - Is cited by
  - Is compiled by
  - Is continued by
  - Is derived from
  - Is described by
  - Is documented by
  - Is identical to
  - Is metadata for
  - Is new version of
  - Is obsoleted by
  - Is original form of
  - Is part of
  - Is previous version of
  - Is referenced by
  - Is required by
  - Is reviewed by
  - Is source of
  - Is supplement to
  - Is supplemented by
  - Is variant form of
  - Is version of
  - Obsoletes
  - References
  - Requires
  - Reviews
- **Editable in workflow**: TRUE
- **API Code**: hres:attribute:related-output

### Files
- **Type**: Attribute group based on type Practice-based output file
- **Editable in workflow**: TRUE
- **API Code**: hres:attribute:practice-based-output-file
- **Sub fields:**
    - **Type**: Image Credit
    - **Editable in workflow**: TRUE
    - **Multiple**: FALSE
    - **API Code**: hres:attribute:image-credit
 
    - **Type**: Measurements
    - **Editable in workflow**: TRUE
    - **Multiple**: FALSE
    - **API Code**: hres:attribute:measurements
 
    - **Type**: Rights
    - **Editable in workflow**: TRUE
    - **Multiple**: FALSE
    - **API Code**: hres:attribute:rights
 
    - **Type**: Media Type
    - **Qualifiers**: Control files
    - **Editable in workflow**: TRUE
    - **Multiple**: FALSE
    - **API Code**: hres:attribute:media-type
 
    - **Type**: License
    - **Editable in workflow**: TRUE
    - **Multiple**: FALSE
    - **API Code**: hres:attribute:license
 
    - **Type**: File Access Level
    - **Editable in workflow**: TRUE
    - **Multiple**: FALSE
    - **API Code**: hres:attribute:file-access-level

### Current Research Institute
- **Type**: Lookup on Research Institute object
- **Editable in workflow**: FALSE
- **Alias of**: Research Institute
- **Multiple**: N/A
- **API Code**: hres:aliased-attribute:current-research-institute

- ### Additional Information
- **Type**: Text (paragraph)
- **Editable in workflow**: TRUE
- **Alias of**: Notes
- **API Code**: hres:aliased-attribute:additional-information

- ### Year
- **Type**: Date and time. Precise to day.
- **Multiple**: N/A
- **Editable in workflow**: FALSE
- **Multiple**: N/A
- **Alias of**: Date
- **API Code**: std:aliased-attribute:year
