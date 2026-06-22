# Prompt Engineering Toolkit 🎯

Systematic prompt engineering with chain-of-thought, few-shot selection, self-consistency, and A/B testing.

## Techniques

- **Chain-of-Thought**: Step-by-step reasoning
- **Few-Shot Selection**: Dynamic example selection
- **Self-Consistency**: Multi-path voting
- **Prompt Optimization**: Bayesian search over templates
- **A/B Testing**: Statistical significance testing

## Quick Start

```python
from prompt_eng import PromptOptimizer

optimizer = PromptOptimizer(model="gpt-4o")
best_prompt = optimizer.optimize(
    task="classification",
    train_data=examples,
    metric="accuracy",
    n_trials=50,
)
```

## License

MIT