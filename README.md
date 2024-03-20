## Instrucciones para Instalar y Levantar una Máquina Virtual con Vagrant

Este documento detalla los pasos necesarios para instalar y levantar una máquina virtual utilizando Vagrant, una herramienta para la creación y gestión de entornos de desarrollo virtualizados. Este tutorial asume que ya tienes instalado VirtualBox, que es el proveedor de máquinas virtuales utilizado por Vagrant. 🛠️

### Requisitos Previos

Antes de comenzar, asegúrate de tener instalados los siguientes componentes:

- [VirtualBox](https://www.virtualbox.org/) 📦
- [Vagrant](https://www.vagrantup.com/) 📦

### Pasos para Instalar y Levantar la Máquina Virtual

1. **Clonar o Descargar el Repositorio**: Clona o descarga el repositorio que contiene los archivos de configuración para la máquina virtual. Por ejemplo:

    ```bash
    git clone https://github.com/xlmriosx/VirtualBox_Vagrant_WindowsServer19.git
    ```

2. **Navegar al Directorio del Proyecto**: Abre una terminal y navega al directorio del proyecto donde se encuentra el archivo `Vagrantfile`. 📂

3. **Inicializar Vagrant**: Ejecuta el siguiente comando para inicializar Vagrant y configurar la máquina virtual según el archivo `Vagrantfile` proporcionado:

    ```bash
    vagrant up
    ```

4. **Acceder a la Máquina Virtual**: Una vez que Vagrant haya terminado de crear la máquina virtual, puedes acceder a ella mediante SSH utilizando el siguiente comando:

    ```bash
    vagrant ssh
    ```

5. **Cuando se termine de utilizar a la Máquina Virtual**: 

    ```bash
    vagrant detroy -f
    ```
