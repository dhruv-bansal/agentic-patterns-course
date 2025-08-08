# PlantUML Diagrams for Agentic Patterns

This folder contains PlantUML diagrams that visualize the implementation and flow of the agentic patterns in this course.

## Reflection Pattern Diagrams

### 1. `reflection_pattern.puml` - Sequence Diagram
A detailed sequence diagram showing the interaction flow between:
- User
- Generation Agent (LLM as Generator)
- Reflection Agent (LLM as Critic)
- Chat History storage

**Key Features Illustrated:**
- Iterative generation-reflection cycle
- Memory management with fixed history size
- Stopping conditions (<OK> signal or max steps)
- Dual-agent approach

### 2. `reflection_pattern_class_diagram.puml` - Class Structure
Shows the technical implementation structure including:
- `ReflectionAgent` class and its methods
- `FixedFirstChatHistory` for memory management
- System prompts and external dependencies
- Implementation details and notes

### 3. Algorithm Flow Diagrams
Multiple representations of the reflection pattern algorithm:

- **`reflection_pattern_simple_flowchart.puml`** - Simple flowchart (recommended)
- **`reflection_pattern_activity.puml`** - Activity diagram with swimlanes
- **`reflection_pattern_state.puml`** - State transition diagram
- **`reflection_pattern_flowchart.puml`** - Complex flowchart (may have rendering issues)

Each shows:
- Initialization steps
- Main iteration loop
- Decision points and stopping conditions
- Memory management strategies

## How to View These Diagrams

### Online Viewers:
- [PlantUML Online Server](http://www.plantuml.com/plantuml/uml/)
- [PlantText](https://www.planttext.com/)

### Local Tools:
- PlantUML JAR with Graphviz
- VS Code with PlantUML extension
- IntelliJ IDEA with PlantUML plugin

### Command Line (with PlantUML installed):
```bash
# Generate PNG images
plantuml *.puml

# Generate SVG images
plantuml -tsvg *.puml
```

## About the Reflection Pattern

The Reflection Pattern is one of the four agentic patterns identified by Andrew Ng. It implements a simple but effective self-improvement mechanism where an LLM alternates between:

1. **Generation**: Creating content based on requirements
2. **Reflection**: Critiquing and suggesting improvements
3. **Refinement**: Incorporating feedback for better results

This pattern is particularly effective for:
- Code generation and improvement
- Creative writing enhancement
- Problem-solving refinement
- Quality assurance automation

## References

- [Andrew Ng's Blog on Agentic Patterns](https://www.deeplearning.ai/the-batch/how-agents-can-improve-llm-performance/)
- [Course Repository](https://github.com/neural-maze/agentic-patterns-course)
- [PlantUML Documentation](https://plantuml.com/)
