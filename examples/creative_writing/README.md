# Creative Writing Example

## Description

This example demonstrates using AlphaEvolve to generate original and insightful text based on a specific creative prompt. The core idea is to evolve programs that can produce text which scores highly on criteria such as originality, depth, non-obviousness, and the ability to challenge assumptions.

The initial prompt guides the generation process towards uncovering "insightful, non-obvious, deeply hidden, counterintuitive, or subversive observations." The `evaluator.py` script (currently a placeholder) is designed to score the generated text based on these qualities.

## How to Run

To run this example, you will typically execute the main AlphaEvolve script, pointing it to the configuration file for this example:

```bash
python -m alphaevolve.main --config examples/creative_writing/config.yaml
```

*(Note: This command assumes AlphaEvolve is installed and accessible in your Python environment.)*

## Expected Output/Behavior

The evolution process will iteratively generate and evaluate programs that produce text. Over generations, the system aims to find programs that generate text with increasingly higher scores from the evaluator.

The output will consist of:
- Logs detailing the evolutionary process, including scores of generated text.
- Checkpoints of the evolutionary state.
- The best programs discovered during the evolution.

The final output should be a piece of text that is highly rated by the evaluator for its originality and insightful nature, as per the initial prompt's requirements. Since the current `evaluator.py` is a basic placeholder, the "quality" in this example will be based on simple keyword matching. A more sophisticated LLM-based evaluator would be needed for true qualitative assessment.
