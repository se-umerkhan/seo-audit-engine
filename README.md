# SEO Audit Engine
**From Websites to SEO Insights**

SEO Audit Engine is an n8n-powered website auditing workflow that scrapes website content, evaluates its SEO, and emails a structured audit report.

Submit a website for analysis and receive actionable findings without manually reviewing every page.

## Demo

*Add your workflow demo video or screenshots here.*

## Features

- **Website Scraping:** Extract website content for SEO analysis.
- **SEO Evaluation:** Analyze extracted content for potential SEO issues.
- **Automated Reporting:** Generate findings through an automated workflow.
- **Email Delivery:** Send the audit results directly to the configured email address.

## Workflow

1. Submit a website URL through the configured input.
2. Scrape the website and extract relevant content.
3. Pass the extracted data through the SEO analysis process.
4. Compile the analysis into an audit report.
5. Email the results to the configured recipient.

## Architecture

Website Input → n8n → Web Scraping → SEO Analysis → Report Generation → Email Delivery

## Tech Stack

- **n8n:** Workflow automation and orchestration
- **Web Scraping:** Website content extraction
- **LLM / AI Integration:** SEO analysis, if configured in the workflow
- **Email Integration:** Automated report delivery

## Getting Started

1. Import `Workflow/SEO_Audit_Engine.json` into your n8n instance.
2. Configure the credentials required by the workflow.
3. Set up the website input and email recipient.
4. Configure any required scraping or AI services.
5. Test the workflow with a website you own or have permission to audit.
6. Verify the analysis and email delivery.

See `Manual.md` for setup and execution instructions.

## License

Released under the MIT License. See `LICENSE` for details.

## About

An n8n automation project that turns website content into emailed SEO audit reports, reducing repetitive manual review.
