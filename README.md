# SaveGate Documentation

Official documentation for [SaveGate.ai](https://savegate.ai) - Your gateway to all LLM AI models with a single API.

**Live Documentation:** [docs.savegate.ai](https://docs.savegate.ai)

## About SaveGate

SaveGate is a unified API gateway that provides access to 50+ AI models from leading providers including Anthropic, OpenAI, Google, Meta, and Mistral. Save 30-50% on costs with unlimited TPM/RPM and a single API key.

## Documentation Structure

### Getting Started
- **Introduction** - Overview of SaveGate and key features
- **Quickstart** - 5-minute setup guide with code examples
- **Authentication** - API key management and security best practices

### Core Concepts
- **Models** - Complete catalog of 50+ supported models
- **Pricing** - Transparent pricing with 30-50% savings comparison
- **Rate Limits** - Unlimited rate limits and performance metrics

### SDK Integration
- **LiteLLM** - Complete LiteLLM SDK integration guide
- **OpenAI SDK** - OpenAI SDK for Python and Node.js
- **Anthropic SDK** - Anthropic Claude SDK integration
- **Python Examples** - Python code examples
- **Node.js Examples** - Node.js code examples

### Guides
- **Migration** - Migrate from OpenAI, Anthropic, Google, and other providers
- **Streaming** - Implement real-time streaming responses
- **Error Handling** - Production error handling and retry logic
- **Best Practices** - Security, performance, and cost optimization

### API Reference
- **Chat Completions** - Main chat endpoint with full documentation
- **Completions** - Legacy completions endpoint
- **Embeddings** - Generate embeddings for semantic search and RAG
- **Models** - List available models

### Examples
- **Basic Chat** - Build a chatbot with conversation history
- **Streaming** - Real-time streaming implementation
- **Function Calling** - Tool/function calling with external APIs
- **Multi-Model** - Use multiple models for optimization

## Local Development

### Prerequisites

- Node.js v16 or higher
- npm or yarn

### Installation

Install the Mintlify CLI to preview documentation changes locally:

```bash
npm i -g mint
```

### Running Locally

Run the development server from the docs directory:

```bash
mint dev
```

View your local preview at `http://localhost:3000`

The preview auto-reloads when you save changes to any documentation files.

### Project Structure

```
docs/
├── docs.json              # Mintlify configuration
├── index.mdx             # Homepage
├── quickstart.mdx        # Quickstart guide
├── authentication.mdx    # Authentication docs
├── concepts/             # Core concept pages
│   ├── models.mdx
│   ├── pricing.mdx
│   └── rate-limits.mdx
├── sdk/                  # SDK integration guides
│   ├── litellm.mdx
│   ├── openai.mdx
│   ├── anthropic.mdx
│   ├── python.mdx
│   └── nodejs.mdx
├── guides/               # How-to guides
│   ├── migration.mdx
│   ├── streaming.mdx
│   ├── error-handling.mdx
│   └── best-practices.mdx
├── api-reference/        # API documentation
│   ├── chat-completions.mdx
│   ├── completions.mdx
│   ├── embeddings.mdx
│   └── models.mdx
└── examples/             # Code examples
    ├── basic-chat.mdx
    ├── streaming.mdx
    ├── function-calling.mdx
    └── multi-model.mdx
```

## Deployment

This documentation is automatically deployed to [docs.savegate.ai](https://docs.savegate.ai) via Mintlify.

### Deployment Process

1. Push changes to the `main` branch
2. Mintlify automatically builds and deploys
3. Changes are live within minutes

### Custom Domain

The documentation is hosted at `docs.savegate.ai` with SSL automatically provisioned.

## Contributing

### Documentation Guidelines

- Use clear, concise language
- Include code examples in multiple languages where applicable
- Follow the existing structure and formatting
- Test all code examples before committing

### Making Changes

1. Create a new branch for your changes
2. Make your edits to the `.mdx` files
3. Test locally with `mint dev`
4. Submit a pull request

### Code Examples

When adding code examples:
- Use `<CodeGroup>` for multiple language examples
- Use `<Tabs>` for different approaches
- Include comments for clarity
- Test all code to ensure it works

## Troubleshooting

### Common Issues

**Dev environment not running:**
```bash
mint update
```

**Page loads as 404:**
- Ensure you're in the directory with `docs.json`
- Check that the file path matches the navigation in `docs.json`

**Build errors:**
- Validate your MDX syntax
- Check for unclosed tags
- Ensure all links are valid

## Resources

- [SaveGate Website](https://savegate.ai)
- [SaveGate Dashboard](https://savegate.ai/signin)
- [GitHub](https://github.com/savegate)
- [Contact Support](mailto:contact@savegate.ai)
- [Mintlify Documentation](https://mintlify.com/docs)

## License

© 2025 SaveGate.ai. All rights reserved.
