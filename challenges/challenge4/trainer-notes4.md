## Challenge 4: Advanced RAG - Trainer Notes

### Challenge Objective

Enhance RAG implementation to handle complex documents with tables, images, and mixed content using Azure AI Document Intelligence.

### Key Features

1. Document Processing

   - OCR capabilities
   - Table extraction
   - Image processing
   - Markdown conversion

2. Enhanced RAG Pipeline
   - Custom document loader
   - Advanced text splitting
   - Image-text integration
   - Multimodal prompting

### Technologies Used

- Azure AI Document Intelligence
- Custom ITSARAG modules
- Azure OpenAI for image description
- Advanced vector indexing

### Implementation Flow

1. Document loading and parsing
2. Image extraction and description
3. Text chunking with context
4. Vector store integration
5. Multimodal retrieval

### Success Criteria

- Successful processing of complex documents
- Accurate table and image handling
- Improved answer quality with multimodal context

### Trainer Notes

- Explain the importance of document structure
- Highlight multimodal capabilities
- Guide through custom module usage
- Document Intelligence works better with markdown than with JSON