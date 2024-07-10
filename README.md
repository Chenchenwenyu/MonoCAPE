3D monocular detection remains to be a focal point of research, particularly due to its capacity to deliver available precision under conditions of low cost and simplified configurations, making it especially valuable in fields like autonomous driving. Current 3D object detection methods often overlook the spatial information missing from images, which is critical to spatial perception, and optimize bounding box attributes separately, failing to meet the requirements of autonomous driving. We introduce MonoCAPE, a novel 3D detection framework addressing these issues by encoding spatial information and co-optimizing attributes through a Coordinate-Aware Position Encoding (CAPE) Generator and a Task Co-optimization Strategy (TCS). The CAPE Generator produces sparse positional embeddings, enabling spatial awareness with low computational cost, while the TCS utilizes Gaussian modeling to prevent suboptimal outputs. In this way, our framework comprehensively takes into account what existing approaches ignore. Extensive experiments on the KITTI dataset demonstrate MonoCAPE achieves up to 22.98/15.37/13.34 and 31.55/21.62/18.37 on the KITTI test set for $AP_{3D}$ and $AP_{BEV}$, respectively.
