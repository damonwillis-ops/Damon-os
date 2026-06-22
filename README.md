# Damon OS

Living strategy co-pilot. Read this file to understand the system structure before loading any other file.

## Quick Load (paste into any Claude session once initialized)
Read: goals.md + values.md + priorities.md + domains/professional.md + last 3 files in sessions/ (by filename, YYYY-MM-DD-* sorted = chronological) + last 7 files in learning/

*Requires Tasks 1-3 complete before this works.*

## Bootstrap Order (first-time setup)
1. goals.md — write 3-5 goals with timeframe + success criteria
2. values.md — write decision filters and non-negotiables  
3. priorities.md — rank current focus this quarter
4. domains/professional.md — career targets, constraints, positioning rules
5. domains/projects/*.md — one file per active project

## Structure
- goals.md — what you're optimizing for (read first)
- values.md — decision filters (context, not hard gates)
- priorities.md — ranked focus this quarter
- domains/professional.md — career targets, constraints
- domains/projects/ — active project status (one file per project)
- sessions/ — auto-written session briefs (append-only, YYYY-MM-DD-*.md)
- decisions/ — fork logs with options, choice, reasoning (append-only, YYYY-MM-DD-*.md)
- decisions/archived/ — branches dead 30+ days (auto-moved by branch scanner)
- reviews/ — weekly synthesis from cron (YYYY-MM-DD-weekly.md)
- learning/ — daily signal synthesis from learn engine (YYYY-MM-DD.md)

## Update Rules
- goals/values/priorities/domains: overwrite in-place when they change
- sessions/ decisions/ reviews/ learning/: NEVER overwrite, append-only (new file per entry)
- Branch status field in decisions/ files: update in-place only (tracks active → dormant → archived lifecycle)
