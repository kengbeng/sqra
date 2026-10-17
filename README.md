# SQRA

SQRA is a lightweight, client-side web application for semi-quantitative assessment of workplace chemical exposures. It lets safety teams record work activities, select or enter chemicals, and evaluate exposure-factor indices to compute a standardized risk score. Based on hazard and exposure inputs, the tool indicates when industrial hygiene (IH) monitoring or subject-matter expert (SME) review is recommended and generates printable/exportable assessment reports for documentation and follow-up. Assessments are stored locally in the browser (IndexedDB); SQRA is intended for screening and internal decision-support and is not a substitute for professional occupational-hygiene advice or regulatory compliance.

## What this tool does

The application helps users:

- Create and manage chemical exposure assessments
- Record work activity, department, location, and process details
- Add chemicals and exposure information
- Assess hazard level and exposure factors
- Determine whether IH monitoring or SME review is required
- Review the highest calculated risk for each assessment
- Generate an assessment report for documentation and review

## Features

- Local browser-based workflow with no backend required
- Assessment register for tracking multiple records
- Chemical lookup and manual entry options
- Risk-scoring logic based on hazard and exposure factors
- IH monitoring and SME status tracking
- Report generation for printing or sharing
- Data stored locally in the browser using IndexedDB

## Project structure

- `index.html` – main application and user interface
- `README.md` – project overview and usage notes

## How to use

Because this is a static HTML application, you can run it directly in a browser.

### Option 1: Open directly

Open `index.html` in any modern web browser.

### Option 2: Serve locally

From the repository directory, run a simple local web server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Typical workflow

1. Create a new assessment in the register view.
2. Enter the activity details (department, location, process, and dates).
3. Add chemicals relevant to the task.
4. Complete exposure and hazard inputs for each chemical.
5. Review the calculated risk and required monitoring steps.
6. Generate the report for documentation or approval.

## Notes

- The application stores assessment data in the browser storage of the device running it.
- This is intended as a practical tool for local or internal use rather than a multi-user web application.
- The tool is focused on screening and decision support for chemical exposure assessment activities.

## Intended use

This project supports semi-quantitative chemical exposure risk screening, especially in occupational hygiene and health and safety processes. It is most useful for:

- Risk screening of work tasks involving chemicals
- Identifying when further IH monitoring is needed
- Determining whether SME input is required
- Maintaining structured assessment records in a lightweight application

## Repository description

Semi-Quantitative chemical exposure screening and reporting.

## Summary

SQRA is a lightweight, static web application for chemical exposure screening and documentation. It is designed to help users assess risk, identify follow-up requirements, and maintain assessment records in a simple browser-based workflow.
