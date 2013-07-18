# Index

The Content Contruction Kit is based on Amnesty Internaional Canada's digital content stragey. This strategy describes how we publish our catalgoue of material based on a number of business rules, including the following.

## The Story

The story is the basic unit - the "atom" - of our content system. A story can be told in many different ways, but the story is always the genesis of the need to publish. 

The CCK is organized around this idea: stories are of expressed as ideas and assets, each with a set of characteristics and needs. By understanding, classifying, and combining ideas and assets, we can publish effectively.

## The Catalogue

Think of a graph with two axis. On one, put all the ideas we communicate about in our human rights work. On the other, put all of the different kinds of communications products we produce in service of promoting human rights. With these two axis, each and every story can be classified, filed, and, most imprortantly, *related to one another*. By catalogueing our stories we make them searchable, dynamic, and relevant. 

This catalogue describes all the possible permutations of communications products with a classification vocabulary. The catalogue is the basis of a holistic and flexible system of talking about human rights with communications, activist, or witness vocabulary.

### Subject Classification

The CCK uses a standardized controlled vocabulary based on the HURIDOCS [Standard Format](http://www.huridocs.org/resource/huridocs-events-standard-formats/) and [Micro-Thesauri](http://www.huridocs.org/resource/micro-thesauri/) system to classify human rights ideas. 

The goal of this system is to improve access to information and exposure of human rights issues by using a standardized vocabulary to talk about human rights violations.

At the core of the CCK's subject classification system is a categorization of each subject, sub-theme, and sub-topic of human rights using a 'violations' model. 

Each subject, sub-theme, and topic category has a unique numerical identifier.

### File Classification

The CCK uses file-naming conventions to classify and organize documents and files. 

Naming things is one of the hardest things to do in computer science. The CCK filing system uses codes to organize all of the various digital assets that go into making a story. What this means, basically, is that the way you name your files tells our system where they should be published. The goal of this system is long-term sustainabilty, ease of use, platform independacne, and portability for all of our documents.

#### File naming conventions

You have to name your files according to the codes for the system to work. 

Files must be named with the following format: `YYMMDD-###-story-name.file`, where `YYMMDD` is the file creation date and `###` is the content-type classification (full listing of types below). That is, `file creation date`-`classification`-`story name`.`file type abbreviation`, all without spaces (use dashes instead).

This chart gives an example, for a story about the Zimbabwe election:

| File name | Translation |
| ------- | --------- |
| `130715-N03-Zimbabwe-election-violence.md` | Press advisory text for a story on Zimbabwe election violence, created July 15th, 2013 |
| `130710-M01-Zimbabwe-election-violence.jpg` | Photograph for a story on Zimbabwe election violence, created July 15th, 2013 |
| `130715-M03-Zimbabwe-election-violence.md` | Map code for a story on Zimbabwe election violence, created July 15th, 2013 |

The story above is about the Zimbabwe election. The story assets are a press advisory text, a photograph, and a map. The text and map were created on July 15th (probably by persons in the Amnesty office), the photograph created five days earlier (likely by someone on the ground). Together, these items form the story package.

#### File classification by story type

##### Publication types

| ID | Publication | Asset | File
| --- | ---------- | ----- | ----- |
| N01 | News | Press release | .md text
| N02 | News | Press update | .md text
| N03 | News | Press advisory | .md text
| N04 | News | Media briefing | .md text
| N05 | News | Statement | .md text
| N06 | News | Position | .md text
| N07 | News | Editorial | .md text
| N08 | News | Media coverage | .md text
| N09 | News | Newsletter | .md text
| N10 | News | Digest | .md text
| N11 | News | News flash | .md text
| R01 | Reference | Report | .md text
| R02 | Reference | Article | .md text
| R03 | Reference | F.A.Q. | .md text
| R04 | Reference | Legal document | .md text
| R05 | Reference | Database | .md text
| R06 | Reference | Guide | .md text
| P01 | Project | Essay | .md text
| P02 | Project | Fact sheet | .md text
| P03 | Project | Project report | .md text
| P04 | Project | Project update | .md text
| B01 | Blog | Post | .md text
| B02 | Blog | Comment | .md text
| B03 | Blog | Update | .md text
| M01 | Media | Photo | .jpg image 
| M02 | Media | Raster Graphic | .gif or .png image
| M03 | Media | Vector Graphic | .scv image
| M04 | Media | Map | .geojson or iframe code
| M05 | Media | Icon | .png image
| M06 | Media | Audio | .wav 
| M07 | Media | Video | various, 1080p/24 .mov prefered
| M08 | Media | Data set | various, Google spreadsheet prefered
| M09 | Media | Infographic | data in Doogle spreadsheet
| M11 | Media | Timeline | data in Google spreadsheet
| M12 | Media | Interview | .wav audio
| M13 | Media | Transcription | .md text
| M14 | Media | Software | Github repository
| M15 | Media | Advertisement | .md, .svg, .gif, .jpg

##### Interaction types

| ID | Publication | Asset | File
| --- | ---------- | ----- | ----- |
| T01 | Task | Singular | .md text
| T02 | Task | Recurring | .md text
| T03 | Task | Continual | .md text 
| E01 | Event | Singular | .md text
| E02 | Event | Recurring | .md text
| E03 | Event | Continual | .md text 
| I01 | Identity | Person | .md text
| I02 | Identity | Group | .md text 
| E01 | E-mail | Solicitation | .md text
| E02 | E-mail | Information | .md text
| E03 | E-mail | Follow-up | .md text

##### Transaction types

| ID | Publication | Asset | File
| --- | ---------- | ----- | ----- |
| F01 | Form | Monetary | HTML5
| F02 | Form | Non-monetary | HTML5 
| C01 | Confirmation | Monetary | .md text
| C02 | Confirmation | Non-monetary | .md text 

For detailed file specifications and requirements, see the File Type Specifications.