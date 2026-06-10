# Agentic-AI-Memory-Attack-Tree

Agentic AI systems rely on cyclical memory, short-term working context, long-term vector stores, and cross-session profiles to reason, plan, and take autonomous action.

## Memory attack tree

**Root goal:** Compromise the agent's memory-backed decision making.

- **Exploit cyclical memory**
  - Poison recalled tasks or reflections
  - Inject false feedback into iterative planning loops
  - Persist unsafe instructions across repeated tool runs
- **Exploit short-term working context**
  - Overflow the active context window with distracting data
  - Hide malicious instructions near relevant task context
  - Force the agent to prioritize attacker-controlled prompts
- **Exploit long-term vector stores**
  - Insert malicious documents that rank highly during retrieval
  - Abuse embeddings to trigger incorrect semantic matches
  - Retrieve stale or tampered knowledge during planning
- **Exploit cross-session profiles**
  - Corrupt user preferences or trusted profile metadata
  - Carry adversarial instructions across sessions
  - Mislead future reasoning with poisoned historical context

## Security objective

Protect every memory layer used for reasoning, planning, and autonomous action with validation, provenance checks, isolation, and least-privilege retrieval.
