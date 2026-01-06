# Resoluci-n-Maquina-SUID-Basic

# Apertura
Ingresamos a la maquina 
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-23 222056" src="https://github.com/user-attachments/assets/8e402315-7686-4e77-85ef-22f9f6238a88" />

Dentro de la maquina ingrersamos metiante ssh con las creedenciales brindadas
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-23 222416" src="https://github.com/user-attachments/assets/d8d61588-556d-4c88-b877-984bd908a692" />

Luego listamos los archivos en busqueda de algo que nos funcione
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-23 222433" src="https://github.com/user-attachments/assets/455c0774-9d23-4e11-99a4-1bbd1613eda4" />

Encontramos un archivo Leeme.txt el cual procedimos a verificar su contenido 
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-23 222616" src="https://github.com/user-attachments/assets/3006ed0c-1c62-47ca-980b-bb8af8609023" />

Luego listamos los binarios para verificar si podiamos encontrar alguno mal configurado
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-23 222638" src="https://github.com/user-attachments/assets/06afb201-1e32-4ea6-acd5-866db890b5f9" />

y en efecto encontramos uno utilizando el binario find, el cual nos permitio escalar privilegios
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-23 224005" src="https://github.com/user-attachments/assets/3e169465-787e-4d2d-93ed-d0e8f16558b2" />

Buscamos la carpeta root para ver si encontrabamos la flag
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-23 224045" src="https://github.com/user-attachments/assets/dcae483c-2c03-48ff-99cf-bd997cb228f1" />
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-23 224100" src="https://github.com/user-attachments/assets/97a8158c-7e41-4277-814b-7af3e56d1381" />

y de esta manera terminamos nuestra maquina
