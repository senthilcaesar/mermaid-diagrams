graph TD
    Start[START] --> Agent[Agent Node: LLM decides]
    Agent -->|Tool needed| Tools[Tool Executor]
    Tools --> Agent
    Agent -->|Done| End[END]
