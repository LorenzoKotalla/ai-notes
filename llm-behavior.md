# LLM Behavior

A collection of informal technical observations derived from hands-on interaction with large language models.

## General patterns
- Output quality degrades non-linearly with underspecified prompts
- Structural cues often outweigh semantic detail in guiding responses
- Models implicitly optimize for coherence over factual certainty

## Prompt sensitivity
- Minor lexical changes can shift response strategy
- Explicit constraints reduce variance more reliably than examples alone
- Formatting instructions act as soft control signals

## Safety and refusal dynamics
- Refusal behavior appears highly sensitive to framing
- Intent is often inferred indirectly rather than explicitly stated
- Boundary conditions are context-dependent and not strictly rule-based
