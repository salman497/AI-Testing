
# LLM

::: mermaid 
flowchart LR 

A[Whole Internet]
B[GPUs]
C[Pattern]
D((User Input))
D2[(Large Lang Model)]
subgraph Training Stage
A  --> B --> | approx 6 month | C -->| 700 GB| D2 
end
D2 --> ChatGPT
D2 --> Bard
D2 --> ...
D --> D2 
:::

# Table 
| LLM Name | Company Name | Approx. Input Data Size | Approx. Size (GB) |
|---|---|---|---|
| GPT-4 | OpenAI | 500GB-1TB | 175-350GB |
| GPT-3 | OpenAI | 500GB | 175GB |
| PaLM | Google AI | 600PB | 600PB |
| Jurassic-1 Jumbo | Google AI | 1.76TB | 1.76TB |
| Megatron-Turing NLG | Google AI | 500PB | 500PB |
| WuDao 2.0 | Beijing Academy of Artificial Intelligence (BAAI) | 1.76TB | 1.76TB |
| Turing NLG | Microsoft | 100PB | 100PB |
| LaMDA | Google AI | 1.56TB | 1.56TB |
| LLM-X | Hugging Face | Not yet released | Not yet released |
| Jurassic-1 | Google AI | 600GB | 600GB |