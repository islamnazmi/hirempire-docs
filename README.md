# Hirempire Documentation

![Hirempire Logo](https://assets-hirempire.s3.us-east-1.amazonaws.com/hirempire-logo-blue.svg)

Welcome to Hirempire's documentation repository. This contains guides for using our AI-powered recruitment platform and API reference for developers.

## 🤝 Contributing

We welcome contributions to improve our documentation. Feel free to:

- Fix typos or errors
- Add examples and clarifications 
- Suggest new content
- Improve existing guides

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview changes locally:

```bash
npm i -g mintlify
```

Run the following command at the root of your documentation (where docs.json is):

```bash
mintlify dev
```

### Publishing Changes

Changes are automatically deployed to production after pushing to the main branch.

#### Troubleshooting

- **Mintlify dev isn't running** - Run `mintlify install` to re-install dependencies
- **Page loads as 404** - Make sure you are running in a folder with `docs.json`
