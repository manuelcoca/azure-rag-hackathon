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

### Additional Training Points

Deployments:

- AI Foundry and model deployment can be different, if model is not available in users foundry location
- In this case, data will be processed in different region
- Deployed model is hosted and managed by Azure Machine Learning service.

Foundry deployment types:

- Global: Process anywhere, highest throughput, best availability
- Data Zone: Process within specific zones (EU/US), balanced quotas
- Regional: Process in specific region, lowest latency

Serverless vs Managed Compute:

- Serverless: Auto-scaling, pay-per-use, ideal for RAG's variable workloads
- Managed: Fixed resources/costs, better for consistent high volume

Model Comparison:

- GPT4o: Powerful, expensive, vision+text, high token limits
- Phi-3: Lightweight, cheaper, text-only, basic tasks
- Recommend GPT-3.5-Turbo for simple RAG: Good cost/performance balance

Key Teaching Focus:

- Emphasize cost implications of model choice
- Demonstrate auto-scaling benefits for RAG
- Show token usage monitoring
