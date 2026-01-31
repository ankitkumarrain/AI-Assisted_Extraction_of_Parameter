# Architectural Extraction

This project is focused on the extraction of RISC-V specifications using advanced Large Language Models (LLMs). The goal is to structure specification data into machine-readable formats.

## Structure

The project contains extraction outputs organized by the LLM used:

- `ClaudeSonnet/`: Extractions generated using Claude Sonnet 4.5.
- `Gemini-3/`: Extractions generated using Gemini 3 Flash.

## Metadata Format

The extractions typically follow a YAML metadata structure. Below is an example based on the "Cache Management Operation (CMO) Extensions" extraction:

```yaml
metadata:
    specification: "RISC-V Privileged Specification"
    section: "19.3.1"
    topic: "Cache Management Operation (CMO) Extensions"
    extraction_date: "2026-01-30"
    llm_used: "Claude Sonnet 4.5"
```

## LLM Specifications

### Gemini 3 Flash
- **Version**: Web (2026 Release)
- **Context Length**: 1 million+ tokens
- **Generative Tier**: Free

### Claude Sonnet 4.5
- **Generative Tier**: Free
