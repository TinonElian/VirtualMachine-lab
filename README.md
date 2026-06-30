# VirtualMachine-lab 1 - Configuracion de un entorno de pruebas seguro

## Objetivo
Configurar un enterno virtual aislado utilizando la herramienta VirtualBox para realizar las practicas de ciberseguridad de forma aislada, evitando que la máquina virtual tenga acceso a Internet o a la red doméstica.

---

## Software utilizado

- VirtualBox
- VirtualBox Extension Pack
- Ubuntu Desktop (ISO)
- Sistema Host: Windows 11

  ---

  ## Configuracion de las Maquinas Virtuales (VM)

- Sistema Operativo: Ubuntu Desktop
- Memoria RAM: 2 GB
- Procesadores: 2 núcleos
- Disco Virtual: 25 GB
- Adaptador de Red: **Red Interna**

## Configuracion de red
  <img width="427" height="531" alt="image" src="https://github.com/user-attachments/assets/26596097-d215-4198-999b-48e2f94e2710" />

---

## Justificación tecnica
Se eligio el modo *Red Interna* porque permite que la máquina virtual permanezca completamente aislada del sistema anfitrion y de internet.
Este modo es ideal para laboratorios de ciberseguridad donde se desea ejecutar herramientas o realizar pruebas sin riesgo de afectar otros dispositivos de la red.

---

## Snapshot
Se creó una instantánea denominada *Estado Actual*
Esta instantánea permite restaurar rapidamente el sistema a un estado controlado antes de realizar pruebas
<img width="1299" height="769" alt="image" src="https://github.com/user-attachments/assets/eda534ba-c0e5-487a-b05b-3564f0fbf506" />

## Conclusion
La configuracion aplicada nos brinda un entorno de pruebas seguro y controlado, siguiendo los principios de aislamiento recomendados para laboratorios de ciberseguridad.
El uso de instantáneas facilita la recuperación del sistema y permite repetir prácticas sin necesidad de reinstalar el sistema operativo.
