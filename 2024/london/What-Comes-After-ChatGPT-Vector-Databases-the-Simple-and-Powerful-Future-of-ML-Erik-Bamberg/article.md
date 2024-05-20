# What comes after ChatGPT? Vector Databases - the Simple and powerful future of ML? - Erik Bamberg, NDC London 2024

- One of the major challenges in the ChatGPT system is the token size.

- The ChatGPT system extensively uses vector databases.

- Database Categories:
    - **Relational**: For structured data and ad-hoc queries.
    - **NoSQL**: Suitable for scale-out operations, document-based, and key-value stores.
    - **Graph**: Ideal for complex relationships, networks, and hierarchical data.
    - **Vector**: Designed for unstructured data and semantic search.

- Unstructured data comprises 80% of the internet. This includes diverse data types like videos, images, PDFs, and other complex formats.

- By leveraging machine learning models, data such as images can be represented numerically through vector embeddings. Nearly any type of data can be converted into embeddings using machine learning models.

![Vector Embedding Image](/2024/london/What-Comes-After-ChatGPT-Vector-Databases-the-Simple-and-Powerful-Future-of-ML-Erik-Bamberg/images/Vector-Embedding-Image.png)

- Common Embedding Models:
    - **Vision:** ResNet, AlexNet
    - **Text**: BERT, DistilBERT
    - **Audio**: Wav2Vec
    - **Source Code**: Code2Vec

![2D Vector Embedding Image](/2024/london/What-Comes-After-ChatGPT-Vector-Databases-the-Simple-and-Powerful-Future-of-ML-Erik-Bamberg/images/2D-Vector-Embedding-Image.png)

![n-Dimensional Vector Embedding Image](/2024/london/What-Comes-After-ChatGPT-Vector-Databases-the-Simple-and-Powerful-Future-of-ML-Erik-Bamberg/images/n-Dimensional-Vector-Embedding-Image.png)

- For a detailed exploration, you can visit projector.tensorflow.org

- Combining the embeddings of unstructured data with structured data elements like year, title, URL, and photographer results in combined data.

- The key task is to find the similarity between embeddings. Techniques such as *cosine similarity*, *Euclidean distance*, and *Jaccard index* are commonly used for this purpose.

![n-Dimensional Vector Embedding Image](/2024/london/What-Comes-After-ChatGPT-Vector-Databases-the-Simple-and-Powerful-Future-of-ML-Erik-Bamberg/images/Vector-Databases-on-Market-Image.png)

![n-Dimensional Vector Embedding Image](/2024/london/What-Comes-After-ChatGPT-Vector-Databases-the-Simple-and-Powerful-Future-of-ML-Erik-Bamberg/images/Weaviate-Image.png)

![n-Dimensional Vector Embedding Image](/2024/london/What-Comes-After-ChatGPT-Vector-Databases-the-Simple-and-Powerful-Future-of-ML-Erik-Bamberg/images/Face-Similarity-Image.png)









