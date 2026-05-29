Traceback (most recent call last):
  File "/home/namthanh5555/Downloads/.venv/lib/python3.13/site-packages/langchain_community/vectorstores/faiss.py", line 56, in dependable_faiss_import
    import faiss
ModuleNotFoundError: No module named 'faiss'

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "/home/namthanh5555/Downloads/UI/app.py", line 13, in <module>
    from imurtrack_ai.chatbot import get_answer
  File "/home/namthanh5555/Downloads/UI/imurtrack_ai/chatbot.py", line 47, in <module>
    vectorstore = FAISS.from_documents(
        documents=splits,
        embedding=embeddings,
        distance_strategy=DistanceStrategy.COSINE,
    )
  File "/home/namthanh5555/Downloads/.venv/lib/python3.13/site-packages/langchain_core/vectorstores/base.py", line 814, in from_documents
    return cls.from_texts(texts, embedding, metadatas=metadatas, **kwargs)
           ~~~~~~~~~~~~~~^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/home/namthanh5555/Downloads/.venv/lib/python3.13/site-packages/langchain_community/vectorstores/faiss.py", line 1044, in from_texts
    return cls.__from(
           ~~~~~~~~~~^
        texts,
        ^^^^^^
    ...<4 lines>...
        **kwargs,
        ^^^^^^^^^
    )
    ^
  File "/home/namthanh5555/Downloads/.venv/lib/python3.13/site-packages/langchain_community/vectorstores/faiss.py", line 996, in __from
    faiss = dependable_faiss_import()
  File "/home/namthanh5555/Downloads/.venv/lib/python3.13/site-packages/langchain_community/vectorstores/faiss.py", line 58, in dependable_faiss_import
    raise ImportError(
    ...<3 lines>...
    )
ImportError: Could not import faiss python package. Please install it with `pip install faiss-gpu` (for CUDA supported GPU) or `pip install faiss-cpu` (depending on Python version).
