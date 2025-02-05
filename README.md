# **Spur Gear Generator**

## **Overview**
This **Spur Gear Generator** is a FreeCAD-based tool that allows users to create customizable spur gears with adjustable parameters such as **teeth count, module, thickness, and bore diameter**. The script provides a simple GUI using **PySide2** (Qt for Python) and dynamically updates the 3D model within FreeCAD.

## **Features**
- **Graphical User Interface (GUI)** for easy gear customization  
- **Live updates** when parameters are changed  
- **Precise involute tooth generation** using FreeCAD  
- **Customizable parameters:**  
  - Number of teeth  
  - Module (size of gear teeth)  
  - Gear thickness  
  - Bore diameter  

## **Requirements**
Before using the Spur Gear Generator, ensure you have the following installed:
- **FreeCAD** (latest version recommended)
- **Python 3.x**
- **PySide2** (for GUI)

### **Installing Dependencies**
```sh
pip install PySide2
```
*(No need to install FreeCAD via pip; just download and install it manually.)*

## **Usage**
1. Open **FreeCAD**  
2. Load the `spur_gear_generator.py` script in FreeCAD’s Python console or execute it from an external script  
3. A GUI window will appear, allowing parameter adjustments  
4. The gear model updates dynamically in FreeCAD as values are modified  

### **Example Code Snippet**
```python
tool = SpurGearGenerator()  # Launch the GUI
```

## **Example Output**
![Example Gear](![Screenshot (349)](https://github.com/user-attachments/assets/1ef96d5e-8020-4aec-ad8d-806d2b62fad5)
) *(Attach a preview of the generated gear.)*

## **Contributing**
Contributions are welcome! Feel free to submit issues, suggest improvements, or create pull requests.

## **License**
This project is licensed under the **MIT License**.

