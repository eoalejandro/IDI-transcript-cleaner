# IDI-transcript-cleaner
A simple approach to clean and standardized in-depth interview transcripts.

## Features
* Text Corrections . . .
* Timestamp Restructuring . . .
* Safety & Transparency . . . 
  
## Workflow
VTT → R parser → CSV review table → Excel cleanup/coding → Word protocol notes

1. Set up project space
ProjectName_transcript_cleaning/
  input/
    ProjectName_transcript_example.vtt
  output/
  scripts/

2. Use R to convert the VTT to a CSV review table
Let R parse the VTT into rows with:
start time | end time | speaker | transcript text | cleaned text | flags | protocol question
