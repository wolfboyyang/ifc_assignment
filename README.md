# Edit IFC File with an Editor

I modified the Hello Reiff IFC example file with VS Code and added a wall, an open element and a window on the wall. I also change to extruded height of the door to make it fix with the door.

## Screenshots
1. [usBIM.Browser](https://www.accasoftware.com/en/bim-viewer)
![](/screenshorts/usBIM.browser.webp)
1. [BIMCollab ZOOM](https://www.bimcollab.com/en/products/bimcollab-zoom)
![](/screenshorts/BIMCollab.webp)
1. [Open IFC Viewer](https://openifcviewer.com/)
![](/screenshorts/openIFCViewer.webp)

## GUID for IFC
I use the script [guid.py](https://github.com/IfcOpenShell/IfcOpenShell/blob/89023df4e588322d61e5f5f0bb08dcab782707f0/src/ifcopenshell-python/ifcopenshell/guid.py) from IfcOpenShell to generate the guid for ifc element and put it into [Jupyter Notebook](/ifcguid.ipynb) to make it easier to use.