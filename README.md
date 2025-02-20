# Instalacion-Angular

## Instalación de Angular

### 1. Verificar que tenemos Node.js y npm instalados
```sh
node -v
npm -v
```

### 2. Instalar Angular CLI
```sh
npm install -g @angular/cli
ng version  # Verificamos la versión instalada
```

### 3. Crear un nuevo proyecto en Angular
```sh
ng new NOMBRE_DEL_PROYECTO --no-standalone
```
Durante la creación del proyecto, se solicitarán algunas configuraciones:
- Enrutamiento: Escribir `YES` para incluirlo o `NO` para agregarlo manualmente.
- Selección de preprocesador CSS: Elegir `CSS` con las teclas de flecha y presionar `Enter`.

### 4. Esperar a que se cree el proyecto

### 5. Abrir el proyecto en Visual Studio Code y ejecutar
```sh
ng serve
```
Esto iniciará el servidor de desarrollo y la aplicación estará disponible en `http://localhost:4200/`.

---

## Opcionales
### Actualizar Angular CLI
```sh
npm install -g @angular/cli@latest
```

### Instalar Angular Material 17.3
```sh
npm install --save @angular/material@^17.3.0 
npm install --save @angular/cdk@^17.3.0
npm list @angular/material
```

Si deseas instalar una versión más reciente de Angular Material, puedes usar:
```sh
npm install --save @angular/material  # Última versión disponible
