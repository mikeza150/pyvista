import pyvista as pv

plotter = pv.Plotter()

# สร้าง rack 3D เป็นกล่อง
rack = pv.Cube(center=(0, 0, 1), x_length=0.6, y_length=1.0, z_length=2.0)
plotter.add_mesh(rack, color='gray', opacity=0.5)
