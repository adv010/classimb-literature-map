
Collecting a list of papers here that I came across during my thesis. Extensive notes from my Mendeley to be imported here in the future. Mix of insights from 3D backbones for Object Detection & SSL/SSDA/UDA approaches for 3D SSOD.

1. BADet : **Boundary-Aware 3D Object Detection from Point Clouds**


Insight - _During proposal generation, proposals produced do not align well with the GTs. Plus, authors propose to consider the proposals not as independent, but as spatially correlated with each other by trating these correlations using a Graph, using a GNN to learn the neighborhood_


Interest areas - Region Feature Aggregation Module :How do they capture the features?

2.  **3D Object Detection Based on Attention and Multi-Scale Feature Fusion**


Insight - From Related Works, a good writeup on how point clouds represented in feature space and what SECOND,PV-RCNN do
_Voxel-based approaches typically discretize point clouds into equally spaced grids and then perform object detection using 3D convolutional neural networks. VoxelNet [5] was the first to encode point clouds as voxel representations and used PointNet to transform all points within each voxel into a single feature representation. However, there are many voxels in the space that do not contain point clouds, such that the voxels in the whole space are sparse, and feature extraction using traditional convolutional neural networks is inefficient. To reduce the computational cost, SECOND [16] introduces a 3D sparse convolution operation to achieve efficient 3D convolutional processing.  PV-RCNN [17] extends the SECOND by adding key point cloud branches to retain the structural information of the 3D point cloud and integrates multi-scale voxel features into the key points, generates region suggestions in the BEV image, and further extracts feature from the key points for each 3D region through a region of interest (ROI) pooling operation for anchor refinement. Since the interaction of point cloud features and voxel features in PV-RCNN takes a long time, a detector using only 3D voxel features is proposed in the Voxel R-CNN [18] using a voxel ROI pooling operation to extract region features from 3D voxel features only for further refinement of the anchor. Centerpoint [19] proposes an anchor-free method, which treats the detection target as a key point and enables the network to learn the direction of the object better, compared to the anchor-based method._

