graph TD
A[Book Scan] --> B[OCR]
B --> C[Text Chunking]
C --> D[Sentence-BERT]
D --> E[Pinecone DB]
E --> F[Question Matching]
