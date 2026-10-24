# SEO Audit Engine Manual

## Overview

SEO Audit Engine automates website content extraction, SEO analysis, and email-based report delivery using n8n.

## Requirements

- A running n8n instance
- Access to the scraping service or method used in the workflow
- AI provider credentials, if required
- Email credentials for sending audit reports

## Setup

### 1. Import the Workflow

1. Open your n8n instance.
2. Import `Workflow/SEO_Audit_Engine.json`.
3. Review the workflow nodes and connections.

### 2. Configure Credentials

Set up the credentials required by your workflow, including:

- Scraping service or API access, if applicable
- AI provider credentials, if applicable
- Email account credentials

Ensure each relevant node references the correct credentials.

### 3. Configure Inputs

Check the workflow's website URL input and email recipient settings. Confirm that the input format matches what the workflow expects.

### 4. Execute the Workflow

1. Provide a valid website URL.
2. Run the workflow.
3. Monitor node execution for errors.
4. Verify that the website content is extracted and analyzed.
5. Check the configured inbox for the generated report.

## Output

The workflow emails the SEO audit results produced by its configured analysis steps. The exact findings and report format depend on the implemented extraction and analysis logic.

## Troubleshooting

| Issue | What to Check |
|---|---|
| Scraping fails | Verify the URL, site accessibility, and scraping configuration. |
| Analysis fails | Check the extracted data and AI credentials, if used. |
| Email is not delivered | Verify email credentials, recipient address, and node execution. |
| Incomplete results | Review extraction limits, page coverage, and analysis inputs. |

## Notes

- Some websites restrict automated access or require JavaScript rendering.
- Audit results depend on the pages and content successfully extracted.
- Review findings before making SEO changes.
- Do not assume a successful content scrape constitutes a complete technical SEO audit.

## License

Released under the MIT License. See `LICENSE` for details.
