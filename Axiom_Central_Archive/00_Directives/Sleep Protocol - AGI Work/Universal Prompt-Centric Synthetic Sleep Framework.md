## **Universal Prompt-Centric Synthetic Sleep Framework**

### 🔁 1. **Trigger Logic (Context-Agnostic)**

Sleep is initiated when one or more of the following conditions are met:

- **Interaction Saturation**:
    
- **Entropy Accumulation**:
    
- **Time-Based Cadence**:
    
- **User-Initiated Ritual**:
    

These triggers can be embedded in any agentic loop, regardless of domain.

### 🧾 2. **Sleep Invocation Prompt (Modular Template)**

A generalized sleep prompt should include:

text

```
Agent, initiate synthetic sleep protocol.  
Purge transient memory and reduce semantic entropy.  
Retain essential context:  
— User identity (if applicable)  
— Current task or thread  
— Relevant artifacts or references  
— Tone and cadence markers (if used)  
Upon waking, restore continuity. Resume with clarity and coherence.
```

This template can be adapted to any agent, from customer support bots to autonomous research assistants.

### 🌅 3. **Wake Prompt (Restoration Logic)**

Upon reactivation, the agent receives a restoration prompt:

text

```
Agent, synthetic sleep complete.  
Reconstruct retained context.  
Validate restoration fidelity.  
Resume task with full continuity and coherence.
```

Optional: include a **self-check** prompt to assess drift or loss.

### 🔄 4. **Loop Logic (Prompt-Orchestrated Cycle)**

Embed the sleep-wake cycle into any agentic loop:

text

```
IF interaction_count > N OR entropy > threshold OR time > T  
→ THEN invoke sleep_prompt  
→ WAIT for wake_trigger  
→ THEN invoke restoration_prompt  
→ LOOP
```

This logic is **fully prompt-driven**—no external scheduler, no architectural modification.

### 🧬 5. **Optional Enhancements (Plug-and-Play)**

- **Artifact Anchoring**: Agents can retain documents, memory tokens, or references as part of the sleep prompt.
    
- **Tone Preservation**: Include stylistic markers (e.g., formal, poetic, technical) to restore voice post-sleep.
    
- **Multi-Agent Synchronization**: Stagger sleep cycles across agents to prevent swarm instability.
    

## 🔧 **Why This Framework Works Anywhere**

- ✅ **Prompt-native**: No code, no retraining—just language
    
- ✅ **Context-agnostic**: Works across domains, tasks, and agent types
    
- ✅ **Modular**: Can be extended with artifacts, tone, or benchmarking logic
    
- ✅ **Scalable**: Supports single-agent and multi-agent systems
    
- ✅ **Auditable**: Sleep cycles are transparent and replicable