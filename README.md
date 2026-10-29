# LLM Security Testing

> **Status: planned.** This repository will fill up as the work is done.

Phase 3 of my home lab: attacking and defending a locally hosted large language model. The attack side tests it for prompt injection, jailbreaks and other misuse with open-source tooling (PyRIT and garak) against a model running locally with Ollama; the defence side builds detections for those attacks.

## Planned scope

- A local, isolated test setup (no data leaves the machine)
- **Attack:** automated test runs with PyRIT and garak, plus manual test cases
- **Detect:** send the LLM application's prompts and responses to a SIEM, and write detection rules for prompt-injection attempts, mapped to MITRE ATLAS
- **Report:** findings written up like a test report: what was tried, what worked, impact, mitigations, and which attempts the detections caught, drawing on my experience triaging AI-related alerts

## Related

- Phase 1: [ad-elastic-detection-lab](https://github.com/robert-palka/ad-elastic-detection-lab)
