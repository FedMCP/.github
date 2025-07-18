# FedMCP - Federal Model Context Protocol

<p align="center">
  <img src="https://github.com/FedMCP/ui/blob/main/public/fedmcp-logo.png" alt="FedMCP Logo" width="200">
</p>

FedMCP is a FedRAMP-aligned superset of the Model Context Protocol that adds audit, redaction, and signature controls to MCP agents for government cloud workloads.

## 🏛️ Overview

FedMCP provides a signed, auditable interchange format for compliance artifacts in government ML deployments. It enables secure, traceable AI workflows that meet FedRAMP High and DoD IL 4/5/6 requirements.

## 🚀 Quick Start

```bash
# Install the Python SDK
pip install fedmcp

# Install the TypeScript SDK  
npm install @fedmcp/sdk

# Install the Go SDK
go get github.com/FedMCP/go-sdk
```

## 📦 Repository Structure

| Repository | Description |
|------------|-------------|
| [core](https://github.com/FedMCP/core) | Protocol specifications and schemas |
| [server](https://github.com/FedMCP/server) | Reference FastAPI implementation |
| [cli](https://github.com/FedMCP/cli) | Command-line tool for artifact management |
| [ui](https://github.com/FedMCP/ui) | Web interface for browsing artifacts |
| [go-sdk](https://github.com/FedMCP/go-sdk) | Go SDK |
| [python-sdk](https://github.com/FedMCP/python-sdk) | Python SDK |
| [typescript-sdk](https://github.com/FedMCP/typescript-sdk) | TypeScript/JavaScript SDK |
| [connectors](https://github.com/FedMCP/connectors) | Connector framework and examples |
| [docs](https://github.com/FedMCP/docs) | Documentation |
| [examples](https://github.com/FedMCP/examples) | Quickstart guides and examples |

## 🔒 Key Features

- **Cryptographic Signatures** - ECDSA P-256 signing for all artifacts
- **Audit Trail** - Immutable audit logs for compliance
- **Multi-Language SDKs** - Go, Python, and TypeScript support
- **FedRAMP Aligned** - Designed for government compliance requirements
- **Extensible** - Plugin architecture for custom artifact types

## 📖 Documentation

- [Getting Started](https://github.com/FedMCP/docs/blob/main/getting-started/quickstart.md)
- [API Reference](https://github.com/FedMCP/server/blob/main/openapi.yaml)
- [Examples](https://github.com/FedMCP/examples)

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](https://github.com/FedMCP/core/blob/main/CONTRIBUTING.md) for details.

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](https://github.com/FedMCP/core/blob/main/LICENSE) file for details.

## 🔗 Links

- [Website](https://fedmcp.org) *(coming soon)*
- [Documentation](https://github.com/FedMCP/docs)
- [Releases](https://github.com/FedMCP/core/releases)

---

*FedMCP is an open source project focused on enabling secure, compliant AI workflows in government environments.*