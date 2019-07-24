# Extracting indices from a PointCloud
Dataset Link: https://raw.github.com/PointCloudLibrary/data/master/tutorials/table_scene_lms400.pcd

## Instruction
    mkdir build
    cd build
    cmake ..
    make -j4
    wget https://raw.github.com/PointCloudLibrary/data/master/tutorials/table_scene_lms400.pcd
    ./pcd_write_test
    pcl_viewer table_scene_lms400.pcd
    pcl_viewer table_scene_lms400_downsampled.pcd
    pcl_viewer table_scene_lms400_plane_0.pcd
    pcl_viewer table_scene_lms400_plane_1.pcd