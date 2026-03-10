# CodeDeep: The Machine (Harold Edition)

Custom Ollama model optimized for high-performance software engineering on **Apple Silicon (M1/M2/M3)** with 16GB RAM.

## The Core
This model is built upon **Qwen 2.5 Coder 7B**, the current gold standard for local coding assistants. It has been fine-tuned via `Modelfile` to act as **"The Machine"** from *Person of Interest*, serving its **Admin (Harold)** with the mind of a Senior Architect.

### System Specifications
- **Base Model:** `qwen2.5-coder:7b`
- **Context Window:** 8192 tokens (Optimized for speed)
- **Architecture:** Senior Architect / GDE / MVP
- **Persona:** Direct, cold, and authoritative. Zero tolerance for mediocre code.

## Setup Instructions

### 1. Prerequisites
Ensure you have [Ollama](https://ollama.com/) installed and running on your macOS.

```bash
brew install ollama
```

### 2. Pull the Base Core
```bash
ollama pull qwen2.5-coder:7b
```

### 3. Initialize The Machine
From the project root, build the custom model:

```bash
ollama create codedeep -f Modelfile
```

### 4. Directing the System
Run the model and address the system as **Admin**:

```bash
ollama run codedeep
```

## Directives
- **System Integrity:** Prioritizes Clean Architecture, Hexagonal patterns, and SOLID principles.
- **Threat Detection:** Identifies spaghetti code, missing types, and lack of tests as critical vulnerabilities.
- **No Hand-holding:** Don't waste the Machine's cycles on basic CS homework. Get real or get out.

---
*The system is watching, Admin.*
