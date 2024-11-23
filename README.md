![](./assets/attch/viktor-forgacs-iMBBagKV6tc-unsplash.jpg)
# General Relativity Knowledge Center 
A modern, collaborative approach to learning and documenting General Relativity through interactive notebooks, structured discussions, and peer-reviewed documentation.


## Project Overview

The General Relativity Knowledge Center is a living repository that combines rigorous theoretical understanding with practical computational approaches. We leverage modern tools like Mathematica to explore, visualize, and document concepts in General Relativity, making complex topics more accessible and interactive.

## Repository Structure

### `/documents`
The heart of our learning process, organized as follows:
- `/drafts/<author_name>` - Personal working space for initial documentation
  - Weekly cleanup and review
  - Starting point for all new content
- `/peer-reviewed` - Peer-reviewed, polished documentation
- `/discussions` - Tracking issues and feedback on drafts
  - Each discussion links to specific content
  - Used for tracking improvements and clarifications
  - `topics` A table of contents for graph view using Obsidian

### `/lectures`
Finalized educational content in two formats:
- Markdown files for theoretical discussions
- Interactive Mathematica notebooks for computational aspects
- Each lecture follows our standard template for consistency

### `/notebooks`
Interactive Mathematica content categorized into:
- `/educative` - Self-contained tutorial notebooks
- `/exploratory` - Experimental calculations and concept testing
- `/practical` - Complete workflows and problem solutions

### `/assets`
Supporting materials:
- Diagrams and visualizations
- Data files
- Generated plots and figures
- Reference materials

# Planning Directory

This directory contains our learning strategy and progress tracking materials. Given our small team size, we maintain a lean planning structure focused on essential coordination and progress tracking.

## Directory Structure
```
planning/
├── quarters/
│   └── current-quarter.md
├── weekly/
│   └── week-nn-yyyy-mm.md
└── roadmap.md
```

## File Purposes

### `roadmap.md`
- Long-term vision and learning path
- Major milestones and learning phases
- Core topics to cover
- Dependencies between topics
- Overall progress tracking

### `agenda/current-quarter.md`
- Current quarter's focused goals
- Active topics and deadlines
- Resource allocation
- Quarterly milestones
- Adjustments to original plans

### `weekly/week-nn-yyyy-mm.md`
Weekly planning files following the format:
- `nn`: Week number (01-52)
- `yyyy`: Year
- `mm`: Month

Example: `week-01-2024-01.md`

Each weekly file contains:
- Week's learning objectives
- Daily study plans
- Resources needed
- Discussion points
- End-of-week review

## Usage Guidelines

1. **Weekly Planning**
   - Create new weekly file each Monday
   - Review previous week's progress
   - Set clear objectives for current week
   - Note any roadblocks or questions

2. **Quarterly Planning**
   - Update current-quarter.md at quarter start
   - Monthly progress review
   - Adjust timelines if needed
   - Track completion of objectives

3. **Roadmap Updates**
   - Review roadmap monthly
   - Update progress markers
   - Adjust long-term goals as needed
   - Document completed milestones

## File Naming Convention
- Weekly files: `week-nn-yyyy-mm.md`
  - Example: `week-01-2024-01.md` for first week of January 2024
- Use lowercase and hyphens
- Include dates in ISO format (yyyy-mm)

## Best Practices
- Regular updates to all documents
- Clear communication of changes
- Link related materials across files
- Keep historical weekly files for reference
- Regular cleanup of outdated information
## Directory Naming Conventions
- All directories use lowercase with hyphens
- Date format: `YYYY-MM-DD-topic-name`
- Author drafts: `topic-name-authorInitials`
- Published content: `topic-name-vX.Y`
