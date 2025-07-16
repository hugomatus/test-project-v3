# Architectural Specifications

This directory contains versioned architectural specifications for this project.

## File Naming Convention

- `baseline.yaml` - Current baseline architectural specification
- `components/` - Individual component specifications
- `history/` - Historical specifications and diffs

## Specification Format

All specifications use YAML format with the following structure:

```yaml
version: "1.0.0"
metadata:
  name: "Example Architecture"
  description: "Description of the architecture"
  created_at: "2024-01-01T00:00:00Z"
  
architecture:
  components: []
  relationships: []
  patterns: []
```

## Workflow

1. **Generate**: Use BluePrintIQ to generate specifications from natural language
2. **Review**: Examine the generated specifications for accuracy
3. **Commit**: Commit approved specifications to Git
4. **Implement**: Use specifications to guide implementation
5. **Evolve**: Update specifications as the architecture evolves

---

*Managed by BluePrintIQ - Git-Native Architectural Intelligence*
