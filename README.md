# vol2mesh

A mesh generating wrapper in python3. Input is a list of folders containing 3D tiff stack. 

Output is a directory for meshes. Third option is decimation percentage.

Example usage: python3 vol2mesh.py ./data/ ./meshes/ .2


Marching cubes implementation: https://github.com/ilastik/marching_cubes
Mesh decimation implementation: https://github.com/sp4cerat/Fast-Quadric-Mesh-Simplification
Reading TIFFs with tifffile: http://www.lfd.uci.edu/~gohlke/code/tifffile.py.html
