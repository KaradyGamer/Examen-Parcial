# instalar ISS

## 📌 **Definición**
IIS (Internet Information Services) es un **servidor web** desarrollado por **Microsoft** para sistemas operativos Windows. Se usa para alojar y administrar **sitios web, aplicaciones web y servicios**.

![CREACION DE ARCHIVO](imagen/1.png)

### EL ERROR DEL PORQUE DESDCARGA

# 🚨 Problema: Windows Home no es compatible con contenedores de Windows en Docker

## ❌ **Por qué no funciona en Windows Home**
Docker necesita soporte para **contenedores de Windows**, pero esta función **no está disponible en Windows 10/11 Home**.  
Solo **Windows Pro, Enterprise y Server** permiten ejecutar contenedores de Windows nativamente.  


📌 **Verifica tu versión de Windows con:**
powershell
```
winver
```
![CREACION DE ARCHIVO](imagen/2.png)

# 🚨 No se puede habilitar contenedores de Windows en Windows Home con PowerShell  

## ❌ **Razón principal**  
Windows Home **no tiene soporte para contenedores de Windows** porque le faltan características clave como:  
- **Hyper-V**, necesario para ejecutar contenedores de Windows.  
- **La característica "Contenedores" de Windows**, que solo está en Windows Pro, Enterprise y Server.  

## ⚠️ **No hay comandos en PowerShell que lo activen**  
No existe ningún comando en **PowerShell** o **Docker** que pueda habilitar los contenedores de Windows en **Windows Home**, porque el sistema **no tiene esa función incluida**.  

## 🔹 **Opciones disponibles**  
 **Actualizar a Windows Pro** para habilitar contenedores de Windows.  
**Usar una Máquina Virtual (VM) con Windows Server o Windows 11 Pro**.  

📌 Si usas Windows Home, Docker solo funcionará con **contenedores Linux**.
