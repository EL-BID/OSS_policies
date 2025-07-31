# Open Source Policy Documentation

A comprehensive documentation site for public policies on open source software, organized by policy type rather than by country.

## 🎯 Mission

This project aims to collect, organize, and document public policies related to open source software from governments worldwide, facilitating policy learning and international collaboration.

## 🚀 Quick Start

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/EL-BID/OSS_policies.git
   cd OSS_policies
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Serve the site locally:
   ```bash
   mkdocs serve
   ```

4. Open your browser to `http://localhost:8000`

### Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `main` branch.

## 📁 Structure

```
/docs/
  en/                    # English documentation
    index.md
    policies/            # Policy files ending in _en.md
  es/                    # Spanish documentation  
    index.md
    policies/            # Policy files ending in _es.md
  pt/                    # Portuguese documentation
    index.md
    policies/            # Policy files ending in _pt.md
/assets/
  policies/              # Supporting documents
mkdocs.yml              # Site configuration
requirements.txt        # Python dependencies
```

## 🤝 Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 📄 License

This documentation is released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

## 🌐 Live Site

Visit the live documentation: https://EL-BID.github.io/OSS_policies
