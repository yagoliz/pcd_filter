# Pointcloud Filtering

Tool to reduce the size of gigantic .pcd files.

Tested in ubuntu 16.04, with PointCloud Library (PCL) version 1.2

## Compiling
To compile it, open a terminal:

``` bash
mkdir build; cd build
cmake ..
make
```

## Usage
To use the filtering tool
```bash
./pcd_filter <pcd_file> <leaf_size>
```

And the output will be:
```bash
downsampled_pcd.pcd
```