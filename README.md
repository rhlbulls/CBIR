# CBIR

Content-based image retrieval

Aim:
Extract query image's feature, and retrieve similar ones from image database


Abstract:

In CBIR (Content-Based Image Retrieval), visual features such as shape, color and texture are extracted to characterize images. Each of the features is represented using one or more feature descriptors. During the retrieval, features and descriptors of the query are compared to those of the images in the database in order to rank each indexed image according to its distance to the query. In biometrics systems images used as patterns (e.g. fingerprint, iris, hand etc.) are also represented by feature vectors. The candidate's patterns are then retrieved from the database by comparing the distance of their feature vectors. The feature extraction methods for these applications are discussed.

Stages involved in CBIR:

Preprocessing:
The images from the database are first processed in order to extract the features, which describe its contents. The processing involves filtering, normalization, segmentation, and object identification. The output of this stage is a set of significant regions and objects.

Feature extraction:
Features such as shape, texture, color, etc. that are used to describe the content of the image are extracted. All the feature vectors are then combined to form feature fusion.

Image Retrieval:
The similarity is measured in the feature vectors, which are coordinated with images extracted through query. The system displays top 10 images from the database that are closest to the query image based on Euclidean distance.




