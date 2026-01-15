# Sendazi API Documentation

Official API documentation for Sendazi - a powerful SMS and Voice campaign management platform.

## Features

- 📱 **SMS Campaigns** - Send bulk SMS messages with scheduling and recurring options
- 📞 **Voice Campaigns** - Automated voice broadcasts with text-to-speech
- 👥 **Contact Management** - Organize contacts into groups for targeted messaging
- 🏷️ **Sender IDs** - Custom sender IDs for professional branding
- 📝 **Message Templates** - Reusable templates with dynamic placeholders
- 🔑 **API Access** - Full programmatic access via REST API

## Documentation Structure

```
├── index.mdx                      # Homepage
├── quickstart.mdx                 # Getting started guide
├── guides/                        # Conceptual guides
│   ├── campaigns.mdx
│   ├── contacts.mdx
│   ├── sender-ids.mdx
│   └── templates.mdx
├── api-reference/                 # API documentation
│   ├── introduction.mdx
│   ├── openapi.json              # OpenAPI specification
│   ├── sms-campaigns/            # SMS campaign endpoints
│   ├── voice-campaigns/          # Voice campaign endpoints
│   ├── contacts/                 # Contact endpoints
│   ├── groups/                   # Group endpoints
│   ├── sender-ids/               # Sender ID endpoints
│   ├── message-templates/        # Template endpoints
│   ├── user/                     # Account endpoints
│   ├── api-keys/                 # API key management
│   ├── payments/                 # Payment verification
│   └── dashboard/                # Dashboard & packages
└── docs.json                      # Mintlify configuration
```

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation locally:

```bash
npm i -g mint
```

Run the development server:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Deployment

Changes pushed to the main branch are automatically deployed via the Mintlify GitHub app.

## API Base URL

```
https://sendazi.com/api/v1
```

## Authentication

All API endpoints require Bearer token authentication:

```bash
Authorization: Bearer YOUR_API_KEY
```

## Support

- 📧 Email: support@sendazi.com
- 📖 Docs: https://docs.sendazi.com
- 🌐 Dashboard: https://sendazi.com

## License

MIT
