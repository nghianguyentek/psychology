# The Process of Scientific Research

```mermaid
flowchart LR
    h([Hypothesis<br>or general premise])
    e([Empirical observations])
    e -- Inductive reasoning --> h
    h -- Deductive reasoning --> e
```

- A theory is a well-developed set of ideas that propose an explanation for observed phenomena.
- A hypothesis is a testable prediction (and thus, falsifiable also) about how the world will behave if our idea is correct, and it is often worded as an if-else statement.
- Deductive reasoning: apply the general principles
- Inductive reasoning: based on observations to make reasonable prediction

```mermaid
flowchart TD
    t([Theory])
    g([Generate hypothesis])
    c([Collect data])
    a([Analyse data])
    s([Summarise data and report findings])
    co([Confirm theory])
    m([Modify theory])
    t --> g --> c --> a --> s --> co
    s --> m --> g
```