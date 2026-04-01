# 🖥️ Evaluación Formativa - Implementación de Máquinas Virtuales

## 📌 Descripción y Requerimientos
En esta evaluación se documenta el proceso de implementación de dos máquinas virtuales en base a los requerimientos solicitados:
* **Windows Server 2019 edición estándar con GUI** (8GB RAM, 30GB disco y 2 vcpu).
* **Linux (Kali Linux adaptado a modo CLI)** (8GB RAM, 30GB disco y 2 vcpu).

En ambas máquinas se verificó la dirección IP y se habilitaron y comprobaron las opciones de acceso remoto (RDP y SSH).

---

## 🪟 1. Windows Server 2019

### 🔹 Creación de la Máquina Virtual
En las **imágenes 1, 2, 3 y 4** se realiza la creación de la máquina virtual:
* Se inicia el proceso pulsando el botón **"Nueva"** (New) en el menú principal.
* Se le asigna un nombre a la máquina y se escoge la ISO a utilizar de Windows Server 2019.
* Se configuran los recursos para la máquina: 8GB de RAM (8192Mb), 2 vCPU y un disco de 30GB. Al terminar, se pulsa el botón **"Terminar"** (Finish) e iniciamos la máquina.

### 🖼️ Imagen 1
![alt text](WIN_SERVER-LINUX_KALI/image-43.png)
*Acceso al menú principal del software de virtualización para iniciar la creación de una nueva unidad mediante el botón "Nueva" (New).*

### 🖼️ Imagen 2
![alt text](WIN_SERVER-LINUX_KALI/image-40.png)
*Asignación del nombre del sistema y selección de la imagen ISO oficial de Windows Server 2019 para el arranque.*

### 🖼️ Imagen 3
![alt text](WIN_SERVER-LINUX_KALI/image-41.png)
*Personalización del hardware virtual: se asignan los 8GB de memoria RAM y los 2 núcleos de procesamiento (vCPU) requeridos.*

### 🖼️ Imagen 4
![alt text](WIN_SERVER-LINUX_KALI/image-42.png)
*Configuración del almacenamiento virtual con un límite de 30GB. Se confirma el resumen de hardware y se pulsa "Terminar" (Finish) para dejar la máquina lista.*

### 🔹 Instalación y Configuración del Sistema
En las **imágenes 5 a 13** se detalla el despliegue del SO:
* Se configuran parámetros regionales (idioma y teclado) y se pulsa **"Instalar ahora"** (Install now).
* Es crítico seleccionar la versión **"Experiencia de escritorio"** (Desktop Experience) para contar con Interfaz Gráfica (GUI).
* Se utiliza la instalación **"Personalizada"** (Custom) para dar formato al disco de 30GB.
* Tras el reinicio automático, se establece la contraseña del Administrador y se pulsa **"Finalizar"** (Finish).

### 🖼️ Imagen 5
![alt text](WIN_SERVER-LINUX_KALI/image-44.png)
*Ajuste de preferencias regionales (idioma, moneda y teclado) antes de iniciar la carga del instalador y pulsar "Siguiente" (Next).*

### 🖼️ Imagen 6
![alt text](WIN_SERVER-LINUX_KALI/image-45.png)
*Confirmación del inicio de la instalación mediante el botón "Instalar ahora" (Install now).*

### 🖼️ Imagen 7
![alt text](WIN_SERVER-LINUX_KALI/image-46.png)
*Selección obligatoria de la versión con "Experiencia de escritorio" (Desktop Experience), garantizando la interfaz gráfica (GUI) requerida.*

### 🖼️ Imagen 8
![alt text](WIN_SERVER-LINUX_KALI/image-47.png)
*Lectura y aceptación de los términos de licencia de software de Microsoft para proceder.*

### 🖼️ Imagen 9
![alt text](WIN_SERVER-LINUX_KALI/image-48.png)
*Selección de la instalación "Personalizada: instalar solo Windows (avanzado)" (Custom: Install Windows only (advanced)).*

### 🖼️ Imagen 10
![alt text](WIN_SERVER-LINUX_KALI/image-49.png)
*Gestión de particiones: se selecciona el espacio de 30GB y se pulsa "Siguiente" (Next).*

### 🖼️ Imagen 11
![alt text](WIN_SERVER-LINUX_KALI/image-50.png)
*Monitoreo del progreso de instalación del sistema.*

### 🖼️ Imagen 12
![alt text](WIN_SERVER-LINUX_KALI/image-51.png)
*Pantalla de reinicio automático del sistema.*

### 🖼️ Imagen 13
![alt text](WIN_SERVER-LINUX_KALI/image-52.png)
*Fase final: establecimiento de contraseña del Administrador.*

### 🔹 Verificación y Servicios

### 🖼️ Imagen 14
![alt text](WIN_SERVER-LINUX_KALI/image-53.png)

### 🖼️ Imagen 15
![alt text](WIN_SERVER-LINUX_KALI/image-54.png)

### 🖼️ Imagen 16
![alt text](WIN_SERVER-LINUX_KALI/image-55.png)

### 🖼️ Imagen 17
![alt text](WIN_SERVER-LINUX_KALI/image-56.png)

---

## 🐉 2. Linux (Kali Linux - modo CLI)

### 🔹 Creación de la Máquina Virtual

### 🖼️ Imagen 1
![alt text](WIN_SERVER-LINUX_KALI/image-57.png)

### 🖼️ Imagen 2
![alt text](WIN_SERVER-LINUX_KALI/image-58.png)

### 🖼️ Imagen 3
![alt text](WIN_SERVER-LINUX_KALI/image-59.png)

### 🖼️ Imagen 4
![alt text](WIN_SERVER-LINUX_KALI/image-60.png)

### 🔹 Instalación

### 🖼️ Imagen 5
![alt text](WIN_SERVER-LINUX_KALI/image-61.png)

### 🖼️ Imagen 6
![alt text](WIN_SERVER-LINUX_KALI/image-62.png)

### 🖼️ Imagen 7
![alt text](WIN_SERVER-LINUX_KALI/image-63.png)

### 🖼️ Imagen 8
![alt text](WIN_SERVER-LINUX_KALI/image-64.png)

### 🖼️ Imagen 9
![alt text](WIN_SERVER-LINUX_KALI/image-67.png)

### 🖼️ Imagen 10
![alt text](WIN_SERVER-LINUX_KALI/image-66.png)

### 🖼️ Imagen 11
![alt text](WIN_SERVER-LINUX_KALI/image-68.png)

### 🖼️ Imagen 12
![alt text](WIN_SERVER-LINUX_KALI/image-70.png)

### 🖼️ Imagen 13
![alt text](WIN_SERVER-LINUX_KALI/image-71.png)

### 🖼️ Imagen 14
![alt text](WIN_SERVER-LINUX_KALI/image-72.png)

### 🖼️ Imagen 15
![alt text](WIN_SERVER-LINUX_KALI/image-73.png)

### 🖼️ Imagen 16
![alt text](WIN_SERVER-LINUX_KALI/image-74.png)

### 🖼️ Imagen 17
![alt text](WIN_SERVER-LINUX_KALI/image-75.png)

### 🖼️ Imagen 18
![alt text](WIN_SERVER-LINUX_KALI/image-76.png)

### 🖼️ Imagen 19
![alt text](WIN_SERVER-LINUX_KALI/image-77.png)

### 🖼️ Imagen 20
![alt text](WIN_SERVER-LINUX_KALI/image-78.png)

### 🖼️ Imagen 21
![alt text](WIN_SERVER-LINUX_KALI/image-79.png)

### 🖼️ Imagen 22
![alt text](WIN_SERVER-LINUX_KALI/image-81.png)

### 🖼️ Imagen 23
![alt text](WIN_SERVER-LINUX_KALI/image-82.png)

### 🖼️ Imagen 24
![alt text](WIN_SERVER-LINUX_KALI/image-83.png)

### 🖼️ Imagen 25
![alt text](WIN_SERVER-LINUX_KALI/image-84.png)

### 🖼️ Imagen 26
![alt text](WIN_SERVER-LINUX_KALI/image-85.png)
