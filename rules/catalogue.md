# Index

The Content Contruction Kit is based on Amnesty Internaional Canada's digital content stragey. This strategy describes how we publish our catalgoue of material based on a number of business rules, including the following.

## The Story

The story is the basic unit - the _"atom"_ - of our content system. A story can be told in many different ways, but the story is always the genesis of the need to publish. Like an atom, a story is a complete unit made up of a few simple parts (we call them assets) that combine and relate to one another. The CCK is organized around this idea: stories are of expressed as ideas and assets, each with a set of characteristics and needs. The grand narrative we are telling about Amnesty International and human rights is made of stories.

## The Catalogue

The catalogue organizes our public communications by idea, type, and time. The catalogue puts all of the atoms in all their correct places.

Think of a graph. On one axis, we plot all of the ideas we communicate about in our human rights work. On another axis, we plot all of the different kinds of communications products we produce. On the third axis, we plot time. This is how the CCK catalogue works: we organize and encode include all of our publishing work, each and every story classified, filed, and, most imprortantly, *related to one another*. By catalogueing our stories we make them searchable, dynamic, and relevant. 

### Subject Classification

The CCK will use a metadata system based on the HURIDOCS [Standard Format](http://www.huridocs.org/resource/huridocs-events-standard-formats/) [Micro-Thesauri](http://www.huridocs.org/resource/micro-thesauri/) to classify human rights ideas and attach those ideas to documents. This system uses a "violations" model and unique numerical identifier to classify human rights issues.

The purpose adopting of this system is to create a standardized, open, and complete vocabulary for classifying human rights violations, thereby increaing access to information and exposure of human rights issues.

### File Classification

Naming things is one of the hardest things to do in computer science, and it gets especially tricky when many different people and machines are involved. The system we use is based on a simple, but strict, file-naming conventions. We use a combination of dates, codes, and names (the three things we need, as above) to classify and organize files.

What this means, basically, is that the way you name your files tells our system where they should be published. The purpose of this system is a publishing workflow that is sustainable, ease to use, platform/device independant, and portabable.

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

#### File classification by story and asset type

| ID | Story | Asset | File | Template
| --- | :----------: | :-----: | :-----: | :----
| N01 | News | Press release | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| N02 | News | Press update | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| N03 | News | Press advisory | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| N04 | News | Media briefing | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| N05 | News | Statement | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| N06 | News | Position | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| N07 | News | Editorial | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| N08 | News | Media coverage | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| N09 | News | Newsletter | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| N10 | News | Digest | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| N11 | News | News flash | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| R01 | Reference | Report | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| R02 | Reference | Article | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| R03 | Reference | F.A.Q. | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| R04 | Reference | Legal document | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| R05 | Reference | Database | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| R06 | Reference | Guide | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| P01 | Project | Essay | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| P02 | Project | Fact sheet | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| P03 | Project | Project report | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| P04 | Project | Project update | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| B01 | Blog | Post | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| B02 | Blog | Comment | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| B03 | Blog | Update | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| M01 | Media | Photo | .jpg image | to [specifications](/file-formats.md)
| M02 | Media | Raster Graphic | .gif or .png image | to [specifications](/file-formats.md)
| M03 | Media | Vector Graphic | .scv image | to [specifications](/file-formats.md)
| M04 | Media | Map | .geojson (for Github), formatted Google spreadsheet (for Tabletop.js), or iframe code  | to [specifications](/file-formats.md)
| M05 | Media | Icon | .png image | to [specifications](/file-formats.md)
| M06 | Media | Audio | .wav  | to [specifications](/file-formats.md)
| M07 | Media | Video | various, 1080p/24 .mov prefered | to [specifications](/file-formats.md)
| M08 | Media | Data set | various, Google spreadsheet prefered | to [specifications](/file-formats.md)
| M09 | Media | Infographic | data in Doogle spreadsheet | to [specifications](/file-formats.md)
| M11 | Media | Timeline | formatted data in Google spreadsheet for Timeline Setter | to [specifications](/file-formats.md)
| M12 | Media | Interview | .wav audio | to [specifications](/file-formats.md)
| M13 | Media | Transcription | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| M14 | Media | Software | Github repository | to [specifications](/file-formats.md)
| M15 | Media | Advertisement | .md, .svg, .gif, .jpg | to [specifications](/file-formats.md)
| W01 | Work | Single task | .md text | job.md
| W02 | Work | Recurring task | .md text | job.md
| W03 | Work | Position | .md text | job.md 
| V01 | Event | Singular | .md text | event.md
| V02 | Event | Recurring | .md text | event.md
| V03 | Event | Continual | .md text | event.md 
| I01 | Identity | Person | .md text | bio.md 
| I02 | Identity | Group | .md text | bio.md
| E01 | E-mail | Solicitation | .md text | message.md
| E02 | E-mail | Information | .md text | message.md
| E03 | E-mail | Follow-up | .md text | message.md
| F01 | Form | Monetary | HTML5 | to [specifications](/file-formats.md)
| F02 | Form | Non-monetary | HTML5 | to [specifications](/file-formats.md) 
| C01 | Confirmation | Monetary | .md text | message.md
| C02 | Confirmation | Non-monetary | .md text | message.md

For detailed file specifications and requirements, see the [File Type Specifications](/file-formats.md).
