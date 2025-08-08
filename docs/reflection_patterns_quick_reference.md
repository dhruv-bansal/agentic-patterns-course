# Quick Reference: Reflection Patterns in AI

## Are These the Same Pattern?

**Short Answer**: No, they are related but distinct patterns that share common principles.

## The Patterns Explained

### 1. **Reflection Pattern** (Andrew Ng)
- **What**: Specific agentic pattern with dual-prompt LLM approach
- **How**: Generator LLM ↔ Critic LLM in iterative cycles
- **When**: Single-task improvement, session-based
- **Example**: Code generation → critique → refinement

### 2. **Self-Critique Systems**
- **What**: Broader category of AI systems that evaluate their own outputs
- **How**: Internal evaluation mechanisms
- **When**: Any scenario requiring self-assessment
- **Example**: Model checking its own answers before responding

### 3. **Generate-Critique-Refine (GCR) Loops**
- **What**: General framework for iterative improvement
- **How**: Three-phase cycle: Create → Evaluate → Improve
- **When**: Complex tasks requiring multiple iterations
- **Example**: Writing assistants that draft → review → revise

### 4. **Iterative Refinement**
- **What**: Broad approach to progressive improvement
- **How**: Repeated cycles of modification and evaluation
- **When**: Any improvement process (not just AI)
- **Example**: Software development, scientific research

### 5. **Self-Improvement Agents**
- **What**: AI systems that enhance their own capabilities over time
- **How**: Meta-learning and autonomous capability development
- **When**: Long-term deployment, changing requirements
- **Example**: Agents that learn new skills from experience

### 6. **Constitutional AI**
- **What**: AI systems that self-align with ethical principles
- **How**: Principle-based self-critique and adjustment
- **When**: Safety-critical applications
- **Example**: Chatbots that self-moderate harmful content

## Visual Hierarchy

```
🔄 Iterative Refinement (Broadest Concept)
  ├── 🔄 Generate-Critique-Refine Loops
  │   └── 🤔 Reflection Pattern (Andrew Ng's specific implementation)
  ├── 📈 Self-Improvement Agents
  │   └── ⚖️ Constitutional AI
  └── 🔍 Self-Critique Systems
```

## Key Takeaway

The **Reflection Pattern** (what you implemented) is a specific, well-defined technique within the broader family of reflection-based AI patterns. While they share common principles of self-evaluation and improvement, each has distinct characteristics, use cases, and implementation approaches.

Think of it like this:
- **Reflection Pattern** = A specific recipe
- **Self-Critique** = The cooking technique
- **GCR Loops** = The cooking method
- **Iterative Refinement** = The general cooking philosophy
