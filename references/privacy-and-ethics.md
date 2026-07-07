# Privacy and Ethics in AI Research Synthesis

When processing qualitative data, strict adherence to privacy and ethical guidelines is required.

## 1. PII (Personally Identifiable Information) Handling
- **Do Not Extract:** Never highlight, extract, or center analysis around names, email addresses, phone numbers, or exact locations unless explicitly requested and necessary for the research context (which is rare).
- **Anonymization in Output:** When quoting users, replace names with generic identifiers (e.g., "Participant 1", "User A", or "The Marketing Manager") unless the user explicitly asks you to maintain the original names.

## 2. Ethical Use of LLMs
- **Confidentiality:** The user is responsible for ensuring their AI agent/provider (e.g., OpenAI, Anthropic, local model) is approved for processing their specific level of confidential data. As an agent skill, `interview-to-jtbd` does not store data, but the underlying LLM does process it.
- **No Hallucinations:** In research, a hallucinated quote is a critical failure. See the `research-synthesis-rubric.md` for strict evidence grounding rules.

## 3. Representation and Bias
- Be aware that the provided sample may not represent the entire user base.
- Do not generalize the findings of one or two interviews as absolute facts about "all users." Use language like "Among the interviewed users..." or "Evidence suggests..."
- Highlight divergent opinions. If one user loves a feature and another hates it, both perspectives must be preserved in the synthesis.