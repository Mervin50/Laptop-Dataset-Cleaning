# Laptop-Dataset-Cleaning

Laptop data cleaning

<img width="1377" height="256" alt="image" src="https://github.com/user-attachments/assets/e0792fa5-defa-412d-b7ae-5ecbc07f1af4" />


Size of the laptops table’s data (in kilobytes) from the sql_cx_live database

<img width="182" height="58" alt="image" src="https://github.com/user-attachments/assets/123dfac9-e11c-430e-99ed-5857365eb970" />


Alter unamed column to Company

<img width="1281" height="266" alt="image" src="https://github.com/user-attachments/assets/cd70c17f-47f8-4271-a16c-01fd84640ba8" />


Updating the laptops table by removing the text 'GB' from all values in the Ram column that contain 'GB'

<img width="1327" height="272" alt="image" src="https://github.com/user-attachments/assets/3ff92ba1-83ee-4fcd-b436-2b8f2b91fd5a" />


Removes 'GB' from all Ram values in the laptops table and then changes the Ram column’s data type to an integer 

<img width="1312" height="242" alt="image" src="https://github.com/user-attachments/assets/458487c4-c196-4406-bfa3-9b78bb2a2b63" />


Updating each row’s Weight in laptops by removing 'kg' from the Weight column using a subquery that matches rows by index

<img width="1422" height="347" alt="image" src="https://github.com/user-attachments/assets/a2620e2b-0189-4d07-ba62-b67a43e50bf1" />


 Rounding all Price values in the laptops table to the nearest whole number and then changes the Price column’s data type to an integer.

<img width="1297" height="272" alt="image" src="https://github.com/user-attachments/assets/f6c27f76-c35a-430a-a124-5ee312073bf3" />


Selecting each laptop’s OpSys and classifies it into os_brand as macos, windows, linux, N/A, or other based on pattern matching.

<img width="222" height="278" alt="image" src="https://github.com/user-attachments/assets/0a0d64d4-4ad6-4e69-b9cf-de1b65a0d8f0" />


Updating the OpSys column in the laptops table by standardizing its values to macos, windows, linux, N/A, or other based on pattern matching.

<img width="1272" height="253" alt="image" src="https://github.com/user-attachments/assets/c0129141-ffeb-4544-a5f2-9a3a267e47aa" />


Adding two new columns, gpu_brand and gpu_name, to the laptops table right after the Gpu column.

<img width="1428" height="287" alt="image" src="https://github.com/user-attachments/assets/1b2d9808-c029-4e43-bb44-333cd8b14b26" />


Filling gpu_brand with the first word of Gpu and gpu_name with the remaining text for rows where those columns are NULL or empty.

<img width="1402" height="252" alt="image" src="https://github.com/user-attachments/assets/89e6f760-9370-4de7-99ef-0a98d3469a2f" />


Adding three new columns to the laptops table: cpu_brand, cpu_name, and cpu_speed (a decimal) right after the Cpu column.

<img width="1423" height="251" alt="image" src="https://github.com/user-attachments/assets/3aa38ed6-f8fb-45f4-8469-6c3ad7bc830f" />


Updates the laptops table by extracting cpu_brand as the first word of Cpu, cpu_speed as the numeric GHz value, and cpu_name as the remaining text of the Cpu column.

<img width="1422" height="251" alt="image" src="https://github.com/user-attachments/assets/01ff0d99-a43c-424b-b17b-fa39f5abb918" />


Droping the Cpu column, previews width and height extracted from ScreenResolution, and then adds resolution_width and resolution_height columns to the laptops table.

<img width="1421" height="246" alt="image" src="https://github.com/user-attachments/assets/08e25ab5-b92b-4044-a915-8e17a0cf6a5b" />


Updating resolution_width and resolution_height from ScreenResolution and then adds a touchscreen column to the laptops table.
































