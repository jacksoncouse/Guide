File Naming Conventions
=========================

How you name your files tells our publishers how and where to publish your story. We use a combination of dates, codes, and names (the three things we need, as above) to classify and organize files.

The purpose of this system is a publishing workflow that is transparent, sustainable, ease to use, platform/device independant, and portabable.

### File naming system

In order for the system to work, you must name your files according to the codes. 

Files must be named with the following format: `YYMMDD-###-story-name.file`, where:

- `YYMMDD` is the file creation date and
- `###` is the content-type classification 
- all without spaces (use dashes `-` instead)

That is, `file creation date`-`classification`-`story name`.`file type abbreviation`

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
| M01 | Media | Photo | .jpg image | [specifications](/rules/formats/)
| M02 | Media | Raster Graphic | .gif or .png image | [specifications](/rules/formats/)
| M03 | Media | Vector Graphic | .scv image | [specifications](/rules/formats/)
| M04 | Media | Map | .geojson (for Github), formatted Google spreadsheet (for Tabletop.js), or iframe code  | [specifications](/rules/formats/)
| M05 | Media | Icon | .png image | [specifications](/rules/formats/)
| M06 | Media | Audio | .wav  | [specifications](/rules/formats/)
| M07 | Media | Video | various, 1080p/24 .mov prefered | [specifications](/rules/formats/)
| M08 | Media | Data set | various, Google spreadsheet prefered | [specifications](/rules/formats/)
| M09 | Media | Infographic | data in Doogle spreadsheet | [specifications](/rules/formats/)
| M11 | Media | Timeline | formatted data in Google spreadsheet for Timeline Setter | [specifications](/rules/formats/)
| M12 | Media | Interview | .wav audio | [specifications](/rules/formats/)
| M13 | Media | Transcription | .md text | [post.md](https://raw.github.com/AmnestyInternational/ContentKit/master/templates/post.md)
| M14 | Media | Software | Github repository | [specifications](/rules/formats/)
| M15 | Media | Advertisement | .md, .svg, .gif, .jpg | [specifications](/rules/formats/)
| W01 | Work | Single task | .md text | job.md
| W02 | Work | Recurring task | .md text | job.md
| W03 | Work | Position | .md text | job.md 
| V01 | Event | Singular | .md text | event.md
| V02 | Event | Recurring | .md text | event.md
| V03 | Event | Continual | .md text | event.md 
| I01 | Identity | Person | .md text | bio.md 
| I02 | Identity | Group | .md text | bio.md
| A01 | Announcement | Advertisement | .md text | message.md
| A02 | Announcement | Information | .md text | message.md
| E01 | E-mail | Solicitation | .md text | message.md
| E02 | E-mail | Information | .md text | message.md
| E03 | E-mail | Follow-up | .md text | message.md
| E04 | E-mail | Inquiry | .md text | message.md
| F01 | Form | Monetary | HTML5 | [specifications](/rules/formats/)
| F02 | Form | Non-monetary | HTML5 | [specifications](/rules/formats/) 
| C01 | Confirmation | Monetary | .md text | message.md
| C02 | Confirmation | Non-monetary | .md text | message.md

#### In use
This chart gives an example, for a story about the Zimbabwe election:

| File name | Translation |
| ------- | --------- |
| `130715-N03-Zimbabwe-election-violence.md` | Press advisory text for a story on Zimbabwe election violence, created July 15th, 2013 |
| `130710-M01-Zimbabwe-election-violence.jpg` | Photograph for a story on Zimbabwe election violence, created July 15th, 2013 |
| `130715-M03-Zimbabwe-election-violence.md` | Map code for a story on Zimbabwe election violence, created July 15th, 2013 |

The story above is about the Zimbabwe election. The story assets are a press advisory text, a photograph, and a map. The text and map were created on July 15th (probably by persons in the Amnesty office), the photograph created five days earlier (likely by someone on the ground). Together, these items form the story package.
