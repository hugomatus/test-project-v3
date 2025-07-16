# Architectural Templates

This directory contains reusable architectural templates for common patterns and components.

## Available Templates

- `api-template.yaml` - RESTful API service template
- `microservice-template.yaml` - Complete microservice with observability

## Template Usage

Templates use Go template syntax with variables that can be customized:

```yaml
# Example template usage
name: "{{.ServiceName}}"
port: "{{.Port | default \"8080\"}}"
```

## Custom Templates

Add your own templates following the same structure:
1. Define metadata and description
2. Specify architectural patterns
3. Include configuration variables
4. Document dependencies and relationships

*Powered by BluePrintIQ Template Engine*
