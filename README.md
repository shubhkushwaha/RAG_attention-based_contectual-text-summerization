Retrieval-Augmented Generation (RAG)system for hybrid contextual text summarization with attention-based fusion. This system combines BM25 sparse retrieval, dense vector search (FAISS), cross-encoder reranking, and T5-based generation to produce high-quality abstractive summaries.

Key Features

-Hybrid Retrieval**: Combines BM25 (sparse) and FAISS (dense) retrieval for optimal passage selection
- Cross-Encoder Reranking**: MS MARCO-trained cross-encoder for precise relevance scoring
- Attention-Based Fusion**: Custom multi-head cross-attention module for context integration
- Fine-tunable Pipeline**: Complete training infrastructure for domain adaptation
- Interactive Interface**: User-friendly widgets for real-time summarization and testing
- Comprehensive Evaluation**: ROUGE and BERTScore metrics with detailed visualizations
- GPU Optimized**: Efficient memory management and batch processing
