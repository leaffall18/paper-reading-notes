# ReAct: Synergizing Reasoning and Acting in Language Models

## Paper

**Title:** ReAct: Synergizing Reasoning and Acting in Language Models  
**Topic:** LLM Agents, Reasoning, Tool Use

## Why I Read This

This paper is relevant to LLM-based agents because it studies how language models can combine reasoning steps with actions.  
Instead of only generating final answers, the model can reason, interact with external tools or environments, observe results, and continue solving the task.

## Key Idea

The core idea of ReAct is to interleave two types of steps:

- Reasoning: the model thinks about what to do next.
- Acting: the model takes an action, such as searching, using a tool, or interacting with an environment.

This makes the model behavior more interpretable and more useful for multi-step tasks.

## My Understanding

Traditional prompting methods often focus only on reasoning.  
ReAct adds actions into the process, so the model can update its reasoning based on external observations.

This is important for LLM agents because real-world tasks usually require more than one response.  
An agent may need to search information, call tools, check intermediate results, and revise its plan.

## Connection to LLM Agents

ReAct can be seen as an early and important framework for agentic workflows.  
It shows that an LLM can act as a controller that decides what to do next based on both reasoning and feedback from the environment.

This connects to several agent topics:

- Planning
- Tool use
- Observation-based reasoning
- Multi-step task solving
- Agent evaluation

## Questions

- How can ReAct-style agents avoid wrong actions caused by incorrect reasoning?
- How should we evaluate the quality of intermediate reasoning steps?
- Can ReAct be combined with long-term memory or retrieval systems?
- How can this framework be used in recommendation scenarios?

## Personal Notes

I am interested in how ReAct-style reasoning and acting can be combined with recommender systems.  
For example, an agent may first infer a user's intent, then retrieve candidate items, compare options, and explain the final recommendation.

More detailed notes may be added later.
