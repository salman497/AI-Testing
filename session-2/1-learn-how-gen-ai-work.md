

:::

# When is Gen AI
::: mermaid 
sequenceDiagram
    participant User
    participant API
    participant Tokenizer
    participant Embeddings
    participant LLM as Large Language Model
    participant Output
    
    User->>API: Input Text
    API->>Tokenizer: Send Text
    Tokenizer->>API: Tokens
    API->>Embeddings: Send Tokens
    Embeddings->>API: Embeddings Vector
    API->>LLM: Send Embeddings
    LLM->>API: Prediction Logits
    API->>Output: Generate Text
    Output->>User: Generated Text

:::