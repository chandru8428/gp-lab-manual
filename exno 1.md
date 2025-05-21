# EXP-01: Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine.
## Date:05-03-2025
## Aim:
To implement various effects in a material such as emissive, roughness and metallic
properties in Unreal Engine.

## Procedure:
1. Open Unreal Engine and create a new project or open an existing one.
2. In the Content Browser, right-click and select 'Material' to create a new material.
3. Name the material 'expmat' and double-click to open the Material Editor.
4. In the Material Editor, create the following nodes:
 - Constant3Vector: Set a color (e.g., red) and connect it to Base Color.
 - Scalar (Constant): Set to 1.0 and connect to Metallic.
 - Scalar (Constant): Set to 0.2 and connect to Roughness.
 - For Emissive Color, use a Constant3Vector (e.g., bright cyan) multiplied by a Scalar (e.g., 
10) and connect the result to Emissive Color.
5. Apply the material to a mesh in the level to preview the effects

## Output:
![image](https://github.com/user-attachments/assets/545ec00d-f1a2-4efd-a270-76238d86cf7b)
![image](https://github.com/user-attachments/assets/e77065de-6ed7-4af2-bb1b-9ec3b24e0d91)
![image](https://github.com/user-attachments/assets/dd8c0644-d5bd-4bb3-88cf-1b56889430a1)
![image](https://github.com/user-attachments/assets/a608e931-3d4c-4097-9e45-29928ac4862c)
![image](https://github.com/user-attachments/assets/1cfd9233-530f-433b-8b83-ddd9e7f7ef87)
![image](https://github.com/user-attachments/assets/ff9bb027-c5b0-48ec-9752-b0a8d1425890)
![image](https://github.com/user-attachments/assets/eee012a3-ff4c-4c59-b76a-bf4ac6cdc7a3)


## Result:
Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine was done successfully.
