# Load nice colormaps from matplotlib and cmocean in IPython
'''from matplotlib import cm
import cmocean
cmap = [c[:-1] + [i] for i, c
        in enumerate(cmocean.cm.thermal(range(256)).tolist())]
np.savetxt('fiducials_thermal_colormap', cmap, delimiter='\t')'''

# Use SUMA's MakeColorMap to create niml.cmap
'''MakeColorMap -fn fiducials_thermal_colormap -suma_cmap thermal'''

# In SUMA, click "New" by "Cmap" under "Dset Mapping"

# Resources:
* https://matplotlib.org/api/cm_api.html
* https://matplotlib.org/cmocean/
* https://afni.nimh.nih.gov/SUMA
* https://afni.nimh.nih.gov/pub/dist/doc/program_help/MakeColorMap.html
