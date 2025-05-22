# EXP-01: Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine.

## Date: 5-3-2025

## Aim:

To implement various effects in a material such as emissive, roughness and metallic
properties in Unreal Engine.

## Procedure

Create a New Material:

Open Unreal Engine. In the Content Browser, right-click and select Material. Name it M_EffectsDemo. Apply Base Color:

Open the material. Add a Vector Parameter or Constant3Vector node and connect it to the Base Color input. Add Emissive Effect:

Add a Multiply node. Connect a Constant3Vector (for emissive color) and a Scalar Parameter (for intensity). Connect the result to the Emissive Color input. Control Roughness:

Add a Scalar Parameter node and connect it to the Roughness input. Lower values = shinier surface, higher values = rougher surface. Control Metallic Property:

Add a Scalar Parameter node and connect it to the Metallic input. 0 = non-metal, 1 = fully metallic. Save and Apply Material:

Save the material. Apply it to any mesh in the scene (like a sphere or cube) to preview the results.

## Output

![image](https://github.com/user-attachments/assets/d8949bd2-c2d9-4007-a487-bef0efc17a3d)

![image](https://github.com/user-attachments/assets/bc295942-d2cd-4b4d-bd65-78d677bb3692)


## Result

Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine was done successfully.

## Result:
Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine was done successfully.
