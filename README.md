# Multimodal Knowledge Graph and GraphRAG Reasoning for Chest X-ray Retrieval and Report Revision

This repository contains the Python notebooks related to the multimodal knowledge graph with GraphRAG reasoning for chest X-ray report generation. <p>
- biomedclip_only_10fold_baselines.ipynb: the implementation of using biomedCLIP for report retrieval. <p>
- hetero_graphsage_10fold_training.ipynb: the implementation of using graphSAGE and the 10-fold cross-validation. <p>
- hetero_non_transformer_gnn_10fold_training.ipynb: the implementation of the non-transformer GNN variants and their 10-fold cross-validation. <p>
- hetero_transformer_gnn_10fold_training.ipynb: the implementation of the transformer GNN variants and their 10-fold cross-validation. <p>
- medgemma_pseudoreport_gnn_inference.ipynb: the implementation of using image prompting the MedGemma model for initial pseudo report and revision by GNN inference. <p>
- radgraph_biomedclip_graphrag_kg.ipynb: the implementation of using RadGraph to extract the radiology entities from the retrieved top-k similar reports and building a knowledge graph using graphRAG. <p>
- retrieval_performance_eval_10fold_all_models.ipynb: the implementation for the 10-fold cross-validation on retrieval performance.
