# Contents

## Jupyter Notebook files

Use [`minnie_plotly_and_vtk_visualizer.ipynb`](https://github.com/shandran/minnie-volume/blob/main/notebooks/minnie_plotly_and_vtk_visualizer.ipynb) to generate a 2D and 3D interactive views of one or more cells of interest from the minnie mm^3 volume. Uses matplotlib, plotly, and vtk/openGL visualization methods. See an example visualization below.

![vtk visualization of neurons in the minnie volume](img/864691135081699319_864691135628037572_864691135724244139_864691136134568075_864691136577483540.png "vtk visualization of neurons in the minnie volume")

Use [`aibs_metamodel_celltypes_v661_v2_layer_positions.ipynb`](https://github.com/shandran/minnie-volume/blob/main/notebooks/aibs_metamodel_celltypes_v661_v2_layer_positions.ipynb) to filter root ids of interest by cell classification (excitatory and inhibitory), and subclasses, such as layer location for pyramidal neurons and connectivity type for interneurons. 

See [`chandelier`](https://github.com/shandran/minnie-volume/tree/main/notebooks/chandelier) folder for visualization notebooks and renderings of select Chandelier cells in the volume, highlighting the synaptic sites on to the initial axon segment of target pyramidal neurons.

![Chandelier-target neuron rendering](chandelier/img/chand_864691135349628119_target_864691135616427625.png "Chandelier-target neuron rendering")

Use [`pyvista_decimate_mesh_cell_bodies_minnie.ipynb`](https://github.com/shandran/minnie-volume/blob/main/notebooks/pyvista_decimate_mesh_cell_bodies_minnie.ipynb) to decimate cell meshes from the minnie volume. Default decimation setting is 95%. You must first download the meshes to your local drive using the `minnie_plotly_and_vtk_visualizer.ipynb` notebook. Decimated files will be saved in the '/dec' subdirectory. Note that astrocyte meshes may take several hours to decimate. Most other cell types will only take minutes.

Use [`vtk_decimated_cell_meshes_minnie.ipynb`](https://github.com/shandran/minnie-volume/blob/main/notebooks/vtk_decimated_cell_meshes_minnie.ipynb) to generate a 3D interactive view of one or more cells of interest using decimated meshes from the minnie mm^3 volume. Uses  vtk/openGL and has a save view function. See an example visualization below.

![vtk visualization of decimated meshes of astrocytes, neurons, and vascular cells in the minnie volume](img/minnie_astro_neuro_vasc_2024_09_23_1232_14.png "vtk visualization of decimated meshes of astrocytes, neurons, and vascular cells in the minnie volume")
