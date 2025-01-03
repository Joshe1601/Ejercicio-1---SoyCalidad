# Sistema de Gestión de Inventario

Un sistema simple para la gestión de inventario desarrollado en Python. Este ejercicio implementa opciones para manejar productos en un inventario, con validaciones y manejo de errores.

## 🚀 Características

- Visualización clara de productos en un formato determinado
- Operaciones completas:
  - Agregar nuevos productos
  - Mostrar lista de productos
  - Actualizar productos existentes
  - Eliminar productos
- Validaciones para la entrada de datos
- Manejo de errores
- Interfaz de línea de comandos amigable

## 📋 Requisitos

- Python 3.10 o superior
- No se requieren dependencias externas

## 🛠️ Instalación y Ejecución

1. Clona este repositorio:
```bash
git clone https://github.com/Joshe1601/Ejercicio-1---SoyCalidad
```

2. Asegúrate de tener instalado Jupyter Notebook en tu sistema. Si no lo tienes, puedes instalarlo con:
```bash
pip install notebook
```

3. Abre el notebook:
- A través de Jupyter Notebook:
  ```bash
  jupyter notebook
  ```
  Navega hasta el archivo `.ipynb` en la interfaz de Jupyter
  
- O directamente desde VS Code u otro editor compatible con notebooks

4. Ejecuta las celdas del notebook secuencialmente (Shift + Enter)

**Nota:** Este proyecto está implementado como un Jupyter Notebook (`.ipynb`), lo que permite una ejecución más interactiva y documentación en el mismo archivo. A su vez, esto no quita el hecho de que el ejercicio esté programado en Python.

## 💻 Uso

El programa ofrece un menú interactivo con las siguientes opciones:

1. **Agregar Producto**
   - Ingresa nombre, precio y stock
   - Validación automática de datos

2. **Eliminar Producto**
   - Elimina productos por ID
   - Verificación de existencia

3. **Actualizar Producto**
   - Actualiza información por ID
   - Mantiene la integridad de los datos

4. **Mostrar Productos**
   - Visualización en formato tabla
   - Información clara y organizada

## ✨ Validaciones Implementadas

- **Nombres de Producto**
  - No pueden estar vacíos
  - Máximo 20 caracteres
  - Elimina espacios en blanco innecesarios

- **Precios**
  - Deben ser números válidos
  - No pueden ser negativos o cero
  - Se aceptan decimales

- **Stock**
  - Debe ser un número entero
  - No puede ser negativo

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para cambios importantes:

1. Haz fork del repositorio
2. Crea una nueva rama
3. Realiza tus cambios
4. Envía un pull request
