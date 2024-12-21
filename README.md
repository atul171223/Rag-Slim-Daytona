# Rag-Slim

- SLIM models: Structured Language Instruction Models from LLMWare
- Designed for AI agents and function calling tasks
- Generate structured outputs for complex automation workflows
- Multi-step, multi-process, and multi-model LLM-based
- Consists of 10 models: addition, arithmetic, comparison, concatenation, division, function-calling, multiplication, subtraction, sentiment-tool, variable assignment
- Slim-sentiment-tool: A notable example, a 4_K_M quantized GGUF version of slim-sentiment
- Specialized decoder-based LLMs, fine-tuned for function calling
- Fast and efficient inference
- Parallelizable for multi-model concurrent deployment on CPUs

---

## 🚀 Getting Started  

### Open Using Daytona  

1. **Install Daytona**: Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/).  
2. **Create the Workspace**:  
   ```bash  
   daytona create https://github.com/atul171223/Rag-Slim-Daytona
   ```  

3. **Start the Application**:  
   ```bash
   streamlit run app.py
   ```

---

### Prerequisites  

 **Install Dependencies**:  
   Ensure you have Python installed and run the following command to install the required libraries:  
   ```bash
   pip install -r requirements.txt
   ```

---
