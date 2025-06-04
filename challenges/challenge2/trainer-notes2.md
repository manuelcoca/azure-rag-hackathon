## Challenge 2: Play with Azure AI Foundry - Trainer Notes

### Challenge Objective

Introduce participants to Azure AI Foundry and implement basic RAG functionality using the UI.

### Key Steps

1. Project Setup

   - Create AI Foundry project
   - Deploy required LLM models (GPT4o and Phi-3)
   - Test vanilla models in playground

2. RAG Implementation
   - Deploy embedding model and Azure AI Search
   - Import sample documents
   - Create vector index
   - Test RAG-enhanced responses

### Technologies Used

- Azure OpenAI GPT4o
- Phi-3-medium-128k-instruct
- Azure AI Search
- Azure Blob Storage

### Important Discussion Points

- Serverless vs Managed Compute
- Model cost comparisons
- RAG vs vanilla model responses
- Vector search configuration

### Success Criteria

- Working Azure AI Foundry setup
- Successful document indexing
- Improved answer quality with RAG

### Trainer Notes

- Monitor token quotas and costs
- Compare answer quality between models
- Highlight importance of proper indexing
- Watch for CORS and firewall configuration issues
