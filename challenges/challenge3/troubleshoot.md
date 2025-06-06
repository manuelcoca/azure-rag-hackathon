## Troubleshooting: Required Python Libraries

### Libs

To ensure your code runs correctly, please make sure you have the following Python libraries installed:

- `azure-storage-blob`
- `unstructured[pdf]`

You can install them using pip:

```sh
pip install azure-storage-blob "unstructured[pdf]"
```

### Embedding model missing

- Embedding model 'text-embedding-ada-002' was missing and not deployed in Azure AI Foundry -> deploy manually

### AI-Search index "itsarag-ch3-001"

- Search index must be created manually called "itsarag-ch3-001"

![Search Index Fields](search-index-fields.png)