# Activity Diagram: Panda Bamboo Jump

Shows the step-by-step flow of a process, including decisions.

```mermaid
flowchart TD
  A([Start]) --> B[Show start screen]
  B --> C{Player presses Play?}
  C -- No --> B
  C -- Yes --> D[Move rocks down]
  D --> E{Panda hit by rock?}
  E -- No --> D
  E -- Yes --> F[Lose a life]
  F --> G{Lives left?}
  G -- Yes --> D
  G -- No --> H[Show Game Over]
  H --> I([End])
```
