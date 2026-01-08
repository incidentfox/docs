# IncidentFox Documentation

Documentation for IncidentFox - AI-powered incident investigation and infrastructure automation.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation locally:

```bash
npm i -g mint
```

Run at the root of the documentation:

```bash
mint dev
```

View at `http://localhost:3000`.

## Publishing

Changes are deployed automatically after pushing to the default branch.

## Documentation Structure

```
/
├── index.mdx              # Landing page
├── quickstart.mdx         # Quick start guide
├── how-it-works.mdx       # Architecture overview
├── configuration/         # Configuration guides
│   ├── overview.mdx
│   ├── agents.mdx
│   ├── tools.mdx
│   └── prompts.mdx
├── integrations/          # Trigger integrations
│   ├── slack.mdx
│   ├── github.mdx
│   ├── pagerduty.mdx
│   └── incident-io.mdx
├── data-sources/          # Data source connections
│   ├── coralogix.mdx
│   ├── snowflake.mdx
│   ├── aws.mdx
│   └── ...
├── tools/                 # Tools catalog
│   ├── kubernetes.mdx
│   ├── aws.mdx
│   └── ...
└── api-reference/         # API documentation
    ├── agent/
    └── config/
```

## Contact

For questions, contact [support@incidentfox.ai](mailto:support@incidentfox.ai)
