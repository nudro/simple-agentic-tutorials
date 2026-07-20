# simple-agentic-tutorials
A set of tutorials I'm building to teach myself Agentic AI principles as manually as possible with toy examples. An ongoing project over time. 

Setup: Macbook M3 + `llama.cpp` installation + Jupyter Notebook. PyTorch for Mac, LangChain.

- **Tutorial 1**: The basics of using local `llama.cpp` on your Macbook, loading it in, interpreting the verbose output, understanding how the tokenizer works, what embeddings do, and a tiny experiment walking through a PyTorch transformer from the passing of a toy embedding to the calculated attention scores. We then walk through a tiny Agent by a) building an agent, b) loading a tool (calculator), c) tool routing, d) building the decision prompt, e) LLM planning, f) JSON parsing, and g) tool execution. The notebook ends with understanding the consequences of a tool registry where we segue into baby LangChain.
- **Tutorial 2**: Starts with the LangChain imports and currently begins with the PromptTemplate and what it means. 
