# Grpassign3
group assignment 3 BDS
For this assignment, the purpose was to utilize RAG to extract information from a document or documents. To do this, the group decided to build a Q&A system, which would retrive information from a scientific article on Deep Learning and thereby attempt to answer queries based on this document.
In the notebook we loaded the paper "Deep Learning review and the discussion of its future" as a pdf file, split it into smaller chunks, embedded them and stored the in a database using Chroma. Then we utilized a GPT model, to answer our queries. The gpt-model as setup to answer the question in a specific way based on our prompt engineering. 
