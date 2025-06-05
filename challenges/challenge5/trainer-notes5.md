## Challenge 5: Multi-Source, Multi-Agent - Trainer Notes

### Challenge Objective

Create a multi-agent system that can handle multiple data sources (documents and SQL database) and coordinate responses.

### Key Components

1. Agent Architecture

   - Assistant Agent (coordinator)
   - RAG Agent (document queries)
   - Stock Agent (SQL queries)

2. Data Integration
   - SQL Database setup
   - Stock data import
   - LangGraph implementation

### Technologies Used

- LangGraph
- SQLAlchemy
- Azure SQL Database
- Custom RAG solution from Challenge 4

### Implementation Steps

1. SQL data import and setup
2. Stock agent creation with SQL toolkit
3. Multi-agent orchestration
4. Decision tree implementation

### Success Criteria

- Working multi-agent system
- Successful data source integration
- Accurate query routing
- Coordinated responses

### Trainer Notes

- Explain agent coordination concepts
- Help with SQL connectivity issues
- Guide through LangGraph implementation
