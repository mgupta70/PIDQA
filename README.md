# PIDQA

PIDQA is a novel question–answering dataset built for querying Piping and Instrumentation Diagrams (P&IDs). It contains 64,000 QA pairs spanning 500 P&ID sheets from the [Dataset-P&ID](https://drive.google.com/drive/u/1/folders/1gMm_YKBZtXB3qUKUpI-LF1HE_MgzwfeR) collection (Click [here](https://arxiv.org/pdf/2109.03794) for the source paper of Dataset-P&ID). Each question is accompanied by a syntactically correct Cypher query for graph-based reasoning.

### 📊 Dataset Statistics

| Question Type         | # Questions per Sheet | Total (500 Sheets) |
|-----------------------|-----------------------|--------------------|
| Simple Counting       | 32                    | 16,000             |
| Spatial Counting      | 32                    | 16,000             |
| Spatial Connections   | 32                    | 16,000             |
| Value-Based Queries   | 32                    | 16,000             |
| **Total**             | **128**               | **64,000**         |


### 🔍 Key Features:
1. Symbols are named as numbers ranging from 1 to 32

| <img src="https://github.com/mgupta70/PID-KnowledgeGraph-demo/blob/main/media/one_shot_symbols.png" width="500"/> |
|:--:|
| Symbols |


### Demo
Click [here](https://pid-knowledgegraph-demo.streamlit.app/) to check out a minimalistic demo where you can ask these 4 types of questions to a P&ID or visit: https://pid-knowledgegraph-demo.streamlit.app/




