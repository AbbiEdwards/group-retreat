# Archiving

## People planning the discussion
- Abbi
- [Anne](https://github.com/pajanne)
- [Mark](https://github.com/markdunning)

## Schedule
- *13:30-14:15* **Internal archiving**
  - What should we keep (clean up)?
  - How should we manage this?
- *16:45-17:30* **External archiving: submissions to public repositories**
  - What should we archive?
  - Where should we archive? (GEO vs ArrayExpress)
  - How can we improve the process?
  - How to reduce the effort required?

## Prep Meetings
- Monday 20th Feb 2016 @ 12:30am
- Monday 13th Feb 2017 @ 11:00am

## Bullet points
### Internal
- Keeping track of path to archive
  - Add path into Redmine when archiving projects
  - Report to generate from Redmine: all archived projects with their link to archive
- Readme file inside project folder as well as uploaded into Redmine
- Software file with version at bottom of all reports as well as software version of the generation of fastq
- Every project runs in a Docker container
- What do we keep? All analysis or only the last one? Need for cleanup stage.

### External
- Internal archive to record what has been done or use existing external ones?
- Lab notebook does not always record everything
- Add extra comments when samples submitted? Maybe better at project level, metadata same as plate layout in Redmine but not always the same version as the one in LIMS
- How should we gather the metadata for each project?
  - When? As early as possible
  - Do we need an extra database for metadata or in spreadsheet attached to Redmine?

#### What do we need to record?
- Wet-lab from bench scientist
- Sequencing library from genomics
- Analysis from bioinformatics

#### When to record?
- At submission when scientists should know everything.

#### Reducing efforts
- Generate submission spreadsheet using a script need to be more generic and robust, and in version control

### Open questions
- How to motivate bioinformatics core to follow good practice? Set up a check list for some else to verify a project status.
- Store metadata locally and generate automatically the GO submission. OR Create GO submission at the end of every project.
- Guidance on preferences for submitting to GO vs ArrayExpress
  - ArrayExpress more stringent, able to submit BAM files
- How to find the fastq based of sample names?
