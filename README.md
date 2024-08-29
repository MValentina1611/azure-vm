# 🌐 Informe de Creación de Máquina Virtual en Azure

## 📝 Introducción

En la práctica realizada, configuramos y desplegamos una máquina virtual en Azure utilizando la opción más económica disponible y un tamaño gratuito para estudiantes. El objetivo era familiarizarnos con la creación y configuración básica de una máquina virtual (VM) en la plataforma Azure.

## 💻 Detalles de la Máquina Virtual

- **Nombre:** `mi-primera-vm`
- **ID:** `/subscriptions/e864be64-78c8-4107-bfd1-6c91e38fa7ec/resourceGroups/valentinacastro-rg/providers/Microsoft.Compute/virtualMachines/mi-primera-vm`
- **Región:** `eastus` (Elegida por ser una de las opciones más económicas)
- **Tamaño de la VM:** `Standard_B2pts_v2` (Ajustada para cumplir con los requisitos básicos y el plan gratuito)
- **Sistema Operativo:** Ubuntu Server 22.04 LTS, ARM64
- **💾 Almacenamiento:**
  - **Disco del sistema operativo:** Linux, con opciones de caché de lectura y escritura.
  - **Tipo de almacenamiento:** Administrado y configurado para eliminarse automáticamente al desmantelar la VM.



  

  
## 🌐 Configuración de Red

La máquina virtual está asociada a una interfaz de red específica, configurada para ser eliminada al ser desvinculada de la VM.

## 🔐 Consideraciones de Seguridad

Optamos por habilitar la autenticación con contraseña para facilitar el acceso durante la práctica, dado que no requeríamos medidas de seguridad avanzadas para este entorno de aprendizaje.

## 📊 Disponibilidad y Escalabilidad

No configuramos una zona de disponibilidad, ya que no era necesario para los objetivos de esta práctica. El enfoque fue mantener la simplicidad y reducir costos.

## 🎯 Conclusión

La práctica nos permitió explorar las opciones básicas de configuración de una VM en Azure, seleccionando una región económica y aprovechando los beneficios del plan gratuito para estudiantes. A través de esta experiencia, adquirimos una comprensión práctica de la creación y manejo de máquinas virtuales en la nube, lo que nos prepara para proyectos más complejos en el futuro.

Evidencia de despliegue de la vm:
  ![Evidencia de la creación de la vm](/arch-img/vmResume2.jpeg)
  

Resumen de la vm en la interfaz de azure:
 ![Resumen de la vm](/arch-img/vmResume.jpeg)

  



