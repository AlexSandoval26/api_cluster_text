# api_cluster_text
Create a service to cluster comments from a file and return a document with results and additional key results.

# API documentation
Endpoint returning a prediction of cluster for english comments

# Parameters
parameters:
    - name: col
    in: query
    type: text
    required: false
    - name: no_of_clusters
    in: query
    type: number
    required: false
    - name: dataset
    in: formData
    type: file
    required: true

# Responses
responses:
    200:
    description: "application/octet-stream"