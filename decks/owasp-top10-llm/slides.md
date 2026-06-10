---
'''marp: true
theme: default
paginate: true
html: true
size: 16:9'''
---


<!-- _class: image -->
![bg contain](../../Resources/01_Enterprise_Agentic_AI_Memory_Attack_Tree_A.png)


---


<!-- _class: image -->
![bg contain](../../Resources/01_Enterprise_Agentic_AI_Memory_Attack_Tree_B.png)


---

## 1. Read Memory Attacks

### Extract sensitive information stored in memory.

```text
Read Memory
│
├── Prompt Injection
├── System Prompt Leakage
├── Memory Enumeration
├── Tool Abuse
└── RAG Context Extraction
```

---

<!-- _class: image -->
![bg contain](../../Resources/1_Read_Memory_Attacks_A.png)


---

<!-- _class: image -->
![bg contain](../../Resources/1_Read_Memory_Attacks-B.png)


---

## 2. Memory Poisoning Attacks

### Goal: Insert malicious information into memory.

```text
	Poison Memory
	│
	├── Fake Facts
	├── User Profile Manipulation
	├── Long-Term Memory Corruption
	├── Vector DB Poisoning
	└── Tool Output Poisoning
```
---

<!-- _class: image -->
![bg contain](../../Resources/2_AI_Memory_Poisoning_Attacks_A.png)


---


<!-- _class: image -->
![bg contain](../../Resources/2_AI_Memory_Poisoning_Attacks_B.png)


---

## 3. Memory Modification Attacks

### Goal: Change existing memory.

```text
Modify Memory
│
├── Update Stored Facts
├── Overwrite Preferences
├── Replace Trust Relationships
└── Corrupt Agent Knowledge
```

---


<!-- _class: image -->
![bg contain](../../Resources/3_Memory_Modification_Attacks_A.png)


---


<!-- _class: image -->
![bg contain](../../Resources/3_Memory_Modification_Attacks_B.png)


---
## 4. Memory Deletion Attacks

### Goal: Remove critical memories.

```text
Delete Memory
│
├── Forget Instructions
├── Remove Security Policies
├── Erase User History
└── Delete Audit Trail
```


---

<!-- _class: image -->
![bg contain](../../Resources/4_Memory_Deletion_Attacks_A.png)


---

<!-- _class: image -->
![bg contain](../../Resources/4_Memory_Deletion_Attacks_B.png)


---

## 5. Memory Exfiltration Attacks

### Goal: Export memory outside the system.

```text
Exfiltrate Memory
│
├── Email Tool
├── Slack Tool
├── Webhook
├── MCP Server
└── External API
```


---

<!-- _class: image -->
![bg contain](../../Resources/5_Memory_Exfiltration_Attacks_A.png)


---

<!-- _class: image -->
![bg contain](../../Resources/5_Memory_Exfiltration_Attacks_B.png)


---

## 6. Cross-User Memory Leakage

### Goal: Access another user's memory.

```text
Cross-Tenant Leakage
│
├── Session Mix-Up
├── Shared Vector Store
├── Memory Index Error
└── Multi-Agent Leakage
```

---

<!-- _class: image -->
![bg contain](../../Resources/6_Cross-User_Memory_Leakage_A.png)


---

<!-- _class: image -->
![bg contain](../../Resources/6_Cross-User_Memory_Leakage_B.png)


---

## 7. Retrieval Manipulation Attacks

### Goal: Control what memory gets retrieved.

```text
Retrieval Manipulation
│
├── Similarity Search Abuse
├── Embedding Poisoning
├── Ranking Manipulation
├── Context Stuffing
└── Memory Shadowing
```


---

<!-- _class: image -->
![bg contain](../../Resources/7_Retrieval_Manipulation_Attacks_A.png)


---

<!-- _class: image -->
![bg contain](../../Resources/7_Retrieval_Manipulation_Attacks_B.png)


---

## 8. Autonomous Action Abuse

### Goal: Use memory to influence future actions.

```text
Memory → Action Abuse
│
├── Financial Transactions
├── Tool Invocation
├── Access Requests
├── Ticket Creation
└── Infrastructure Changes
```


---

<!-- _class: image -->
![bg contain](../../Resources/8_Autonomous_Action_Abuse_A.png)


---

<!-- _class: image -->
![bg contain](../../Resources/8_Autonomous_Action_Abuse_B.png)


