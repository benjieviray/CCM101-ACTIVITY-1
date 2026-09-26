# Storage Types Research

## Comparison of Cloud Storage Types

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| Block Storage | Stores data in fixed-size blocks and provides high-performance storage for applications. | Databases, virtual machines, and applications that require fast disk access. | Amazon EBS |
| File Storage | Stores data as files in a hierarchical folder structure and allows shared access. | Shared files, documents, and applications that need a common file system. | Amazon EFS |
| Object Storage | Stores data as objects together with metadata and a unique identifier. | Large amounts of unstructured data such as images, videos, backups, and documents. | Amazon S3 |

## Why Object Storage is Best for User-Uploaded Images

Object Storage is suitable for millions of user-uploaded images because it is designed to store large amounts of unstructured data. It also provides scalable storage that can be accessed through APIs and is well suited for applications that need to store and retrieve image files.
