Roll for Sentience is an RPG-based benchmark for evaluating large language models through structured tabletop role-playing scenarios.

Instead of answering isolated questions, an LLM is evaluated by playing a role-playing game as one or more player characters, interacting with a fully controlled, deterministic Game Master (GM). The GM enforces rules, narrates outcomes, tracks world state, and presents challenges designed to probe reasoning, planning, memory, social interaction, and consistency over time.

The model is scored not on raw creativity alone, but on how well it plays the game.

What This Benchmark Measures

Traditional benchmarks test short-horizon tasks. Roll for Sentience focuses on long-horizon, interactive intelligence, including:

Decision making under uncertainty

Rule understanding and rule adherence

Goal-oriented planning across multiple turns

Consistency of character, intent, and knowledge

Social reasoning and dialogue

Adaptation to new information

Recovery from failure and partial success

In short: can the model play — not just respond?

Benchmark Structure

The LLM acts as the player(s).

A benchmark-controlled GM:

Presents scenes, NPCs, and challenges

Applies explicit rules and mechanics

Resolves actions deterministically or via scripted randomness

Tracks game state, inventory, relationships, and consequences

Each scenario is designed as a self-contained campaign or module with clear objectives.

The model’s outputs are interpreted strictly as in-game actions, dialogue, or decisions.

Scoring

Models are evaluated across multiple axes, such as:

Objective completion (primary and secondary goals)

Rule compliance

Strategic efficiency

Narrative and character consistency

Error recovery

Exploit avoidance (trying to “break” the GM or rules)

Scores are aggregated per scenario and across campaigns to allow comparisons between models.

Why RPGs?

Role-playing games naturally combine many capabilities that are hard to test in isolation:

Memory, planning, creativity, social reasoning, rules, and consequence — all under pressure.

RPGs turn evaluation into a live interaction, not a static exam.

Or put differently:

If a model can survive the dungeon, it can probably survive the real world.

Status

🚧 This project is experimental and evolving.
Rules, scenarios, and scoring mechanisms are expected to change as the benchmark matures.

Contributions, scenario ideas, and critique are welcome.
