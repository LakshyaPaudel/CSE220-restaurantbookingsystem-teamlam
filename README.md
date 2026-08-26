# Restaurant Booking System

## Project Information

- **Course:** CSE-220 Principles of Software Engineering
- **Lesson:** Lesson 8 - Software Project Management
- **Project:** Restaurant Booking System
- **Team:** Team LAM
- **University:** International American University
- **Professor:** Gaman Aryal

## Project Overview

The Restaurant Booking System is a proposed software system designed to simplify restaurant table reservations. Customers can register, log in, search restaurants, view restaurant information and available tables/time slots, make reservations, view or modify reservations, cancel reservations, and log out securely. Restaurant staff can manage tables, reservations, and restaurant schedules.

The project follows an Agile Scrum approach with two sprints. Trello is used for project management, while GitHub is used for documentation, version control, branches, commits, and Pull Requests.

## Team Members and Branches

- **Anish Shrestha** - Requirements, backlog, and assigned development/testing tasks  
  Branch: `anish_shrestha`
- **Lakshya Paudel** - UML design, development, and assigned testing tasks  
  Branch: `lakshya_paudel`
- **Mandip Kushwaha** - Trello/GitHub coordination, development, and assigned testing tasks  
  Branch: `mandip_kushwaha`

## Repository Structure

```text
CSE220-restaurantbookingsystem-teamlam
|
|-- requirements
|   |-- V-1.0
|   |   |-- functional-requirements.docx
|   |   |-- non-functional-requirements.docx
|   |   |-- stakeholder-analysis.docx
|   |   `-- requirement-gathering-techniques.docx
|   `-- V-1.1
|       |-- functional-requirements.docx
|       `-- README.md
|
|-- design
|   |-- V-1.0
|   |   |-- use-case-diagram.png
|   |   |-- class-diagram.png
|   |   |-- sequence-diagram-make-reservation.png
|   |   |-- sequence-diagram-cancel-reservation.png
|   |   |-- activity-diagram-make-reservation.png
|   |   |-- activity-diagram-manage-reservation.png
|   |   `-- README.md
|   `-- V-1.1
|       `-- README.md
|
|-- testing
|   |-- V-1.0
|   |   |-- test-cases.xlsx
|   |   `-- test-matrix.xlsx
|   `-- V-1.1
|       `-- README.md
|
|-- project-management
|   |-- product-backlog.xlsx
|   |-- sprint1-tasks.xlsx
|   |-- sprint2-tasks.xlsx
|   |-- gantt-chart.png
|   |-- version-control-document.md
|   |-- product-backlog-screenshot.png
|   |-- detailed-trello-card.png
|   |-- sprint1-trello-screenshots
|   `-- sprint2-trello-screenshots
|
`-- README.md
```

## Folder Description

### `requirements/`
Contains the versioned functional requirements, non-functional requirements, stakeholder analysis, and requirement-gathering documentation.

### `design/`
Contains the UML diagrams used in the report: Use Case, Class, Sequence, and Activity diagrams.

### `testing/`
Contains the test-case workbook/template and the testing summary matrix. The source report provides summary testing totals but does not provide the detailed row-by-row test cases, so the test-case workbook must be completed with the team's actual executed test cases before final submission.

### `project-management/`
Contains the product backlog, Sprint 1 and Sprint 2 task sheets, Trello evidence, Gantt chart, and Version Control Document.

## Agile Process

The project is organized into two Agile sprints:

- **Sprint 1:** US-01 to US-06 - core customer booking functionality.
- **Sprint 2:** US-07 to US-13 - reservation management and restaurant operations.

## Version Naming Convention

- `V-1.0` - Initial version
- `V-1.1` - Minor revision or correction
- `V-2.0` - Major revision

Original artifacts should be preserved. Revised artifacts should be saved in the appropriate new version folder instead of replacing the previous version.

## GitHub Workflow

1. Pull the latest `main` branch.
2. Work on an individual branch.
3. Make changes to the assigned artifact.
4. Commit with a meaningful ID-based message.
5. Push the individual branch.
6. Create a Pull Request from the individual branch to `main`.
7. Another team member reviews the Pull Request.
8. Approved changes are merged into `main`.

## Commit Message Examples

```text
[US-01] Add customer registration documentation
[FR-01] Update functional requirements v1.1
[TC-001] Add test case for customer registration
[T-101] Complete restaurant search task
[BUG-001] Fix duplicate reservation issue
```

## Pull Request Requirement

Each team member should create at least one Pull Request from their individual branch to `main`. Each PR should include a meaningful title, description, related IDs, a list of changes, and a checklist. The team should review and merge approved Pull Requests.

## Project Status

The repository contains the initial project artifacts extracted or prepared from the submitted Restaurant Booking System report. Any placeholder marked for team completion should be replaced with the team's genuine project evidence before final submission.
