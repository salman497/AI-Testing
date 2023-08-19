
# LLM

::: mermaid 
flowchart LR 

A[Whole Internet]
B[GPUs]
C[Pattern]
D((User Input))
D2[(Large Lang Model)]
subgraph Training Stage
A  --> B --> | 6 month | C -->| 700 GB| D2 
end
D2 --> ChatGPT
D2 --> Bard
D2 --> ...
D --> D2 