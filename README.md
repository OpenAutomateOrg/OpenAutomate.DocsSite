# OpenAutomate Documentation Site

[![Built with Mintlify](https://img.shields.io/badge/Built%20with-Mintlify-blue)](https://mintlify.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

The official documentation website for OpenAutomate - an open-source business process automation management platform. This documentation provides comprehensive guides, tutorials, and reference materials for users, developers, and administrators.

## 🚀 About OpenAutomate

OpenAutomate is a cost-effective alternative to commercial automation solutions, built with:
- **Python** for automation execution
- **ASP.NET Core** for backend services
- **Next.js** for the frontend interface

The platform enables organizations to create, deploy, monitor, and manage automation processes without vendor lock-in or expensive licensing costs.

## 📚 Documentation Structure

This documentation site covers:

### Getting Started
- **Introduction** - Platform overview and key concepts
- **Architecture** - System design and component relationships
- **Quick Start** - Get up and running in under 10 minutes
- **Setup** - System requirements and installation guides

### Orchestrator
- **Dashboard** - Web-based control panel for managing automations

### Agent
- **Installation** - Deploy bot agents on your infrastructure

### Developer Guide
- **Getting Started** - Build automation bots using Python SDK
- **Python Templates** - Ready-to-use templates for common scenarios

## 🛠️ Development

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher)
- [Mintlify CLI](https://www.npmjs.com/package/mintlify)

### Local Development

1. **Install Mintlify CLI**
   ```bash
   npm i -g mintlify
   ```

2. **Clone the repository**
   ```bash
   git clone https://github.com/OpenAutomateOrg/OpenAutomate.DocsSite.git
   cd OpenAutomate.DocsSite
   ```

3. **Start the development server**
   ```bash
   mintlify dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to view the documentation site.

### Making Changes

1. Edit the `.mdx` files in the repository
2. The development server will automatically reload with your changes
3. Preview your changes locally before committing

### Project Structure

```
├── docs.json              # Mintlify configuration
├── index.mdx              # Homepage
├── overview.mdx           # Platform overview
├── architecture.mdx       # System architecture
├── quickstart.mdx         # Quick start guide
├── agent/                 # Agent documentation
│   └── installation.mdx
├── developer/             # Developer guides
│   ├── getting-started.mdx
│   └── python-templates.mdx
├── orchestrator/          # Orchestrator documentation
│   └── dashboard.mdx
├── setup/                 # Setup guides
│   ├── requirements.mdx
│   └── installation.mdx
├── images/                # Documentation images
├── logo/                  # Brand assets
└── snippets/              # Reusable content snippets
```

## 🎨 Customization

### Theme Configuration

The site uses a custom theme configured in `docs.json`:
- **Primary Color**: `#FF6B35` (Orange)
- **Light Accent**: `#FF8A65`
- **Dark Accent**: `#E64A19`

### Navigation

Navigation is configured in `docs.json` with tabs for:
- Getting Started
- Orchestrator
- Agent
- Developer Guide

### Branding

- **Logo**: Custom OpenAutomate logos in `/logo/`
- **Favicon**: Custom favicon at `/favicon.svg`
- **Hero Images**: Light/dark mode hero images in `/images/`

## 🚀 Deployment

### Automatic Deployment

This repository is configured for automatic deployment:
1. Push changes to the `main` branch
2. GitHub Actions automatically builds and deploys the site
3. Changes are live within minutes

### Manual Deployment

If you need to deploy manually:
```bash
mintlify build
```

## 🤝 Contributing

We welcome contributions to improve the documentation! Here's how to contribute:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/improve-docs
   ```
3. **Make your changes**
   - Follow the existing documentation style
   - Test locally with `mintlify dev`
   - Ensure all links work correctly
4. **Commit your changes**
   ```bash
   git commit -m "Improve installation documentation"
   ```
5. **Push to your fork**
   ```bash
   git push origin feature/improve-docs
   ```
6. **Create a Pull Request**

### Writing Guidelines

- Use clear, concise language
- Include code examples where helpful
- Add screenshots for UI-related content
- Follow the existing file naming conventions
- Test all links and code examples

## 🔧 Troubleshooting

### Common Issues

**Mintlify dev isn't running**
```bash
mintlify install  # Re-install dependencies
```

**Page loads as 404**
- Ensure you're running in a folder with `docs.json`
- Check that the page is listed in the navigation configuration

**Build errors**
- Check for syntax errors in `.mdx` files
- Ensure all referenced images exist
- Verify all internal links are correct

**Reserved path errors**
- Avoid using `/api` paths (reserved by Mintlify)
- Use alternative paths like `/developer/api-reference`

## 📞 Support

- **Documentation Issues**: [Create an issue](https://github.com/OpenAutomateOrg/OpenAutomate.DocsSite/issues)
- **Platform Support**: [support@openautomate.io](mailto:support@openautomate.io)
- **Community**: [Discord](https://discord.gg/hPt44QfY4B)
- **GitHub**: [OpenAutomateOrg](https://github.com/OpenAutomateOrg)

## 📄 License

This documentation is licensed under the [MIT License](LICENSE).

## 🔗 Links

- **Live Documentation**: [docs.openautomate.io](https://docs.openautomate.io)
- **OpenAutomate Platform**: [cloud.openautomate.me](https://cloud.openautomate.me)
- **Main Repository**: [OpenAutomate](https://github.com/OpenAutomateOrg/OpenAutomate)
- **Community**: [Discord Server](https://discord.gg/hPt44QfY4B)
