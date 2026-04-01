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
*Selección de la instalación "Personalizada: instalar solo Windows (avanzado)" (Custom: Install Windows only (advanced)). Opción necesaria para realizar una instalación limpia desde cero.*

### 🖼️ Imagen 10
![alt text](WIN_SERVER-LINUX_KALI/image-49.png)
*Gestión de particiones: se selecciona el espacio de 30GB y se pulsa "Siguiente" (Next) para que el sistema cree las unidades necesarias.*

### 🖼️ Imagen 11
![alt text](WIN_SERVER-LINUX_KALI/image-50.png)
*Monitoreo del progreso: el sistema copia archivos e instala características y actualizaciones en el disco duro.*

### 🖼️ Imagen 12
![alt text](WIN_SERVER-LINUX_KALI/image-51.png)
*Pantalla de reinicio automático del sistema tras completar la carga de archivos. Se puede pulsar "Reiniciar ahora" (Restart now) para agilizar.*

### 🖼️ Imagen 13
![alt text](WIN_SERVER-LINUX_KALI/image-52.png)
*Fase final: establecimiento de una contraseña segura para la cuenta de Administrador y pulsado del botón "Finalizar" (Finish).*

### 🔹 Verificación y Servicios
En las **imágenes 14 a 17** se valida la conectividad:
* Se usa la lupa de búsqueda de la barra de tareas, se escribe `cmd` para abrir el Símbolo del Sistema y se verifica la IP con `ipconfig`.
* Se busca en la lupa "Configuración de Escritorio remoto" (Remote Desktop settings) para habilitar el servicio.

### 🖼️ Imagen 14
![alt text](WIN_SERVER-LINUX_KALI/image-53.png)
*Uso del Símbolo del Sistema (CMD), abierto buscando `cmd` en la lupa de Windows, para obtener la dirección IP local mediante el comando `ipconfig`.*

### 🖼️ Imagen 15
![alt text](WIN_SERVER-LINUX_KALI/image-54.png)
*Habilitación del servicio de Escritorio Remoto (RDP) buscando "Configuración de Escritorio remoto" en la lupa de Windows y activando el interruptor.*

### 🖼️ Imagen 16
![alt text](WIN_SERVER-LINUX_KALI/image-55.png)
*Comprobación visual del estado del servicio, confirmando que se encuentra activo y escuchando correctamente.*

### 🖼️ Imagen 17
![alt text](WIN_SERVER-LINUX_KALI/image-56.png)
*Configuración avanzada: se activa la Autenticación a Nivel de Red (NLA) para seguridad y se verifica que esté habilitado.*

---

## 🐉 2. Linux (Kali Linux - modo CLI)

### 🔹 Creación de la Máquina Virtual
Proceso de creación mediante el botón **"Nueva"** (New), asignando 8GB RAM, 2 vCPU y 30GB de disco utilizando la ISO de Kali Linux.

### 🖼️ Imagen 1
![alt text](WIN_SERVER-LINUX_KALI/image-57.png)
*Inicio del asistente de creación de nueva máquina virtual pulsando el botón "Nueva" (New) en el menú principal.*

### 🖼️ Imagen 2
![alt text](WIN_SERVER-LINUX_KALI/image-58.png)
*Identificación de la máquina como "Kali Linux" y vinculación de su imagen ISO correspondiente.*

### 🖼️ Imagen 3
![alt text](WIN_SERVER-LINUX_KALI/image-59.png)
*Asignación de recursos de hardware: 8GB de RAM y 2 vCPU para garantizar el rendimiento.*

### 🖼️ Imagen 4
![alt text](WIN_SERVER-LINUX_KALI/image-60.png)
*Confirmación del disco de 30GB y pulsado de "Terminar" (Finish). La máquina se inicia para arrancar el instalador.*

### 🔹 Instalación y Configuración del Sistema
Se opta por **"Graphical Install"** por ser intuitivo. Se configuran idioma, país y teclado según la necesidad del entorno. Se realiza un particionado guiado para utilizar la totalidad del disco.

### 🖼️ Imagen 5
![alt text](WIN_SERVER-LINUX_KALI/image-61.png)
*Elección del modo "Graphical Install" en el menú de arranque, facilitando la configuración visual del sistema.*

### 🖼️ Imagen 6
![alt text](WIN_SERVER-LINUX_KALI/image-62.png)
*Configuración del idioma principal del sistema. Se escoge el de preferencia y se pulsa "Continue".*

### 🖼️ Imagen 7
![alt text](WIN_SERVER-LINUX_KALI/image-63.png)
*Selección de la ubicación geográfica o país para configurar los espejos de red y zona horaria.*

### 🖼️ Imagen 8
![alt text](WIN_SERVER-LINUX_KALI/image-64.png)
*Configuración del mapeado de teclado para asegurar la correcta entrada de caracteres y comandos.*

### 🖼️ Imagen 9
![](WIN_SERVER-LINUX_KALI/image-67.png)
*Proceso automático (Detect and mount installation media) donde el sistema detecta y escanea los medios de instalación (ISO) para cargar los componentes necesarios.*

### 🖼️ Imagen 10
![alt text](WIN_SERVER-LINUX_KALI/image-66.png)
*Definición del nombre de la máquina (Hostname) para su identificación en la red y pulsado de "Continue".*

### 🖼️ Imagen 11
![alt text](WIN_SERVER-LINUX_KALI/image-68.png)
*Configuración del nombre de dominio (Domain name) en la red, seguido de pulsar "Continue" para avanzar.*

### 🖼️ Imagen 12
![alt text](WIN_SERVER-LINUX_KALI/image-70.png)
*Creación del nombre real y nombre de usuario estándar del sistema (Full name for the new user).*

### 🖼️ Imagen 13
![alt text](WIN_SERVER-LINUX_KALI/image-71.png)
*Establecimiento y confirmación de la contraseña de usuario para el acceso al sistema.*

### 🖼️ Imagen 14
![alt text](WIN_SERVER-LINUX_KALI/image-72.png)
*Ajuste de la zona horaria (Configure the clock) correspondiente a la ubicación física seleccionada anteriormente.*

### 🖼️ Imagen 15
![alt text](WIN_SERVER-LINUX_KALI/image-73.png)
*Inicio del particionado: se selecciona el método "Guiado - utilizar todo el disco" (Guided - use entire disk).*

### 🖼️ Imagen 16
![alt text](WIN_SERVER-LINUX_KALI/image-74.png)
*Selección del disco virtual de 30GB creado en VirtualBox como destino de la instalación.*

### 🖼️ Imagen 17
![alt text](WIN_SERVER-LINUX_KALI/image-75.png)
*Esquema de partición: se escoge "Todos los archivos en una sola partición" (All files in one partition).*

### 🖼️ Imagen 18
![alt text](WIN_SERVER-LINUX_KALI/image-76.png)
*Finalización del particionado: se selecciona "Finalizar el particionado y escribir los cambios en el disco" (Finish partitioning and write changes to disk).*

### 🖼️ Imagen 19
![alt text](WIN_SERVER-LINUX_KALI/image-77.png)
*Confirmación de escritura: se marca la opción "Sí" (Yes) para aplicar los cambios de forma definitiva.*

### 🖼️ Imagen 20
![alt text](WIN_SERVER-LINUX_KALI/image-78.png)
*Selección de software (Software selection): se pulsa "Continuar" manteniendo las opciones por defecto para la base del sistema.*

### 🖼️ Imagen 21
![alt text](WIN_SERVER-LINUX_KALI/image-79.png)
*Finalización de la instalación (Finish the installation): el sistema carga los últimos paquetes y solicita reiniciar para entrar a Kali Linux.*

### 🔹 Verificación y Servicios
Acceso mediante la terminal para verificar IP con `ip a` e `ifconfig`. Se habilita el acceso remoto actualizando repositorios y activando el servicio SSH.

### 🖼️ Imagen 22
![alt text](WIN_SERVER-LINUX_KALI/image-81.png)
*Primer arranque del sistema: se selecciona la entrada de Kali Linux en el cargador de arranque GRUB.*

### 🖼️ Imagen 23
![alt text](WIN_SERVER-LINUX_KALI/image-82.png)
*Pantalla de login: ingreso del nombre de usuario y la contraseña definidos en los pasos anteriores.*

### 🖼️ Imagen 24
![alt text](WIN_SERVER-LINUX_KALI/image-83.png)
*Acceso al sistema operativo: una vez dentro, se procede a abrir el terminal (Terminal Emulator) para realizar tareas de administración.*

### 🖼️ Imagen 25
![alt text](WIN_SERVER-LINUX_KALI/image-84.png)
*Verificación de red: ejecución de los comandos `ip a` e `ifconfig` para confirmar la dirección IP asignada a la interfaz.*

### 🖼️ Imagen 26
![alt text](WIN_SERVER-LINUX_KALI/image-85.png)
**Mantenimiento avanzado y despliegue de servicios**

En esta captura se detalla el proceso crítico de reparación y configuración del sistema para garantizar el acceso remoto seguro. El procedimiento se divide en las siguientes etapas:

---

### 🛠️ Paso 1: Revisión del Gestor de Paquetes
Se comienza eliminando las fuentes que podrían estar corruptas para restablecer la integridad de las descargas.

* **Eliminar fuentes corruptas:** `sudo rm -f /etc/apt/sources.list`
* **Reescribir repositorio oficial (Kali Rolling):** `echo "deb http://http.kali.org/kali kali-rolling main contrib non-free non-free-firmware" | sudo tee /etc/apt/sources.list`

> [!IMPORTANTE]
> **Uso del editor Nano:** Si realizas este proceso manualmente, utiliza estos comandos:
> * **CTRL + O**: Guardar cambios.
> * **ENTER**: Confirmar nombre del archivo.
> * **CTRL + X**: Salir del editor.

---

### 🧹 Paso 2: Limpieza y Reparación Profunda
Tras corregir los repositorios, se ejecutan comandos para sanear el estado actual de los paquetes instalados.

1.  **Limpieza de caché:** `sudo apt clean`
2.  **Actualización con reparación de descargas:** `sudo apt update --fix-missing`
3.  **Configurar interrupciones previas:** `sudo dpkg --configure -a`
4.  **Forzar instalación de dependencias:** `sudo apt install -f -y`
5.  **Verificación final de integridad:** `sudo apt update`

---

### 🚀 Paso 3: Instalación y Activación de Servicios
Una vez que el sistema está estable, se procede a habilitar las herramientas de acceso remoto.

* **Instalación de servidores:** `sudo apt install openssh-server xrdp -y`
* **Gestión de demonios (SSH y XRDP):**
    * `sudo systemctl enable ssh` && `sudo systemctl start ssh`
    * `sudo systemctl enable xrdp` && `sudo systemctl start xrdp`

---

### 🔐 Paso 4: Conectividad y Firewall
Configuración final para permitir el tráfico de red necesario y verificar la conectividad.

* **Habilitar tráfico SSH:** `sudo ufw allow ssh`
* **Verificar dirección IP:** `ip a`

> **Resultado:** Ambos servicios (SSH y RDP vía XRDP) quedan activos, habilitados para el inicio automático y escuchando peticiones en sus respectivos puertos para permitir la administración remota.

---
