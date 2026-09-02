# AgentXpert
....
**Say goodbye to manual ticket processing!**  
Upload your tickets from Excel/CSV or connect your Jira/Azure DevOps accounts, and let **AgentXpert** handle the rest.

![Logo](https://i.ibb.co/fYfRRbVn/Agent-Xpert-Logo.png)

---

## 🎬 Demo

| Version           | Powered By                                         | Demo Link                                                                                         |
| ----------------- | -------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| **AgentXpert v1** | IBM WatsonX AI & WatsonX Data                      | Watch Demo → [YouTube](https://www.youtube.com/watch?v=eqcUr3dxGKM)                               |
| **AgentXpert v2** | Any OpenAI-Compatible LLM API (bring-your-own-key) | Watch Demo → [Linkedin](https://www.linkedin.com/feed/update/urn:li:ugcPost:7403088225491214337/) |

---

## 🧰 Tech Stack

**Client:** Dash

**Server:** Flask

---

## 🚀 Use Cases

AgentXpert supports multiple practical applications for customer support automation:

- **File Ticket Processing:**  
  Upload Excel, CSV, or text files to process multiple tickets asynchronously for fast and efficient handling.

- **System Integration with Webhooks:**  
  Integrate AgentXpert with your existing ticketing systems such as **Jira** and **Azure DevOps** to enable automated ticket processing using webhooks.

- **MCP Server Integration:**  
  Built the AgentXpert MCP Server to integrate with any MCP-compliant client, enabling enhanced interoperability and automation across platforms.

---

## 🔥 Features

AgentXpert leverages advanced AI models and prompt engineering for each key task:

1. **Ticket Classification:** Prompt Tuned Flan-T5-XL-3B
2. **Subject Identification:** Prompt Engineering with Granite-3B-Code-Instruct
3. **Summarization:** Prompt Engineering with Mixtral-8x7B-Instruct-v0.1
4. **Sentiment Analysis:** Fine Tuned BERT model (nlptown/bert-base-multilingual-uncased-sentiment)
5. **Proposed Solution Generation:** Granite-3-8B-Instruct with RAG technique
6. **Email Generation:** Prompt Engineering with Granite-34B-Code-Instruct

We also provide a feedback option to improve ticket analysis continuously as part of AgentXpert's future enhancements.

### 📚 RAG Configuration (AgentXpert v2)

Version 2 introduces full Retrieval-Augmented Generation support with **4 flexible options**:

| Framework / Platform | Description                                              |
| -------------------- | -------------------------------------------------------- |
| **LangChain**        | Build RAG pipelines using customizable vector stores     |
| **LlamaIndex**       | Powerful tool for indexing and retrieving information    |
| **RAGFlow**          | RAG Engine to create enhanced context layers for LLMs    |
| **AnythingLLM**      | All-in-one platform for AI applications with RAG support |

Select the method that works best for your project!

---

## 📝 Authors

- Github: [@bensaied](https://www.github.com/bensaied)

---

## 💝 Support

If you find this project helpful, please consider leaving a ⭐️!  
If you are interested or have questions, contact us at **ben.saied@proton.me**

---

## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bensaied/)
