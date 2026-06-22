# Damon OS

Living strategy co-pilot. Read this file to understand the system structure before loading any other file.

## Quick Load (paste into any Claude session)
Read: goals.md + priorities.md + last 3 files in sessions/ + last 7 files in learning/

## Structure
- goals.md — what you're optimizing for (read first)
- values.md — decision filters (context, not hard gates)
- priorities.md — ranked focus this quarter
- domains/professional.md — career targets, constraints
- domains/projects/ — active project status
- sessions/ — auto-written session briefs (append-only)
- decisions/ — fork logs with options, choice, reasoning (append-only)
- decisions/archived/ — branches dead 30+ days
- reviews/ — weekly synthesis from cron
- learning/ — daily signal synthesis from learn engine

## Update Rules
- goals/values/priorities: overwrite when they change
- sessions/ decisions/ reviews/ learning/: NEVER overwrite, append only
- Branch status field in decisions/: update in-place
