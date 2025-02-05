# Descripcion del proyecto

## Práctica: Introducción a Git y GitHub con Vite

### Objetivos

- Familiarizarse con los comandos básicos de Git.
- Aprender el flujo de trabajo con ramas en Git.
- Practicar la colaboración mediante GitHub.
- Crear un proyecto básico con Vite.

### Requisitos Previos

- Tener instalado Git en el equipo local.
- Tener una cuenta en GitHub.
- Tener Node.js instalado.
- Tener un editor de código (VS Code recomendado)
- Es Obligatorio Usar Markdown para la creación de la documentación.


## 1.Desarrollo de la práctica

### Parte 1: Configuración Inicial (15%)

#### 1. Crear un nuevo repositorio en GitHub llamado "proyecto-vite-[tunombre]"


![Texto](/images/parte1-1.png)

#### 2. Crear un directorio local para el proyecto

![Texto alternativo](/images/parte1-2.png)

#### 3. Inicializar un proyecto con Vite:

![Texto alternativo](/images/parte1-3.png)

#### 4. Inicializar Git en el directorio local, realizando el primer commit

![Texto alternativo](/images/parte1-4.png)
![Texto alternativo](/images/parte1-4-2.png)

#### 5. Conectar el repositorio local con GitHub:

![Texto alternativo](/images/parte1-5.png)

### Parte 2: Trabajo con Ramas (25%)

#### 1. Crear dos ramas nuevas:
```bash
desarrollo (para desarrollo general)
feature-ui (para cambios en la interfaz)
```
![Texto alternativo](/images/parte2-1.png)

#### 2. En la rama feature-ui:
```bash
Modificar el componente principal (index.html) de Vite
Realizar al menos 2 commits significativos
```
![Texto alternativo](/images/parte2-2-1.png)
![Texto alternativo](/images/parte2-2-2(1).png)
![Texto alternativo](/images/parte2-2-2(2).png)

#### 3. En la rama desarrollo:
```bash
Añadir un nuevo componente
Realizar al menos 2 commits significativos
```
![Texto alternativo](/images/parte2-2-3(1).png)
![Texto alternativo](/images/parte2-2-3(2).png)

### Parte 3: Colaboración (30%)

#### 3.1 Propietario del Repositorio
```bash
1. Añadir colaboradores al repositorio:
   Ir a Settings > Collaborators
   Añadir al profesor usando su usuario de GitHub
   Añadir a un compañero usando su usuario de GitHub
   Asegurarse que ambos reciben y aceptan la invitación
```

![Texto alternativo](/images/parte-3.1.png)

### 3.2 Pasos del Colaborador
```bash
1. Aceptar la invitación de colaboración (llegará por email)
```

![Texto alternativo](/images/parte3.2(1).png)

```bash
2. Clonar el repositorio:
```

![Texto alternativo](/images/parte3.2(2).png)

```bash
3. Crear y cambiar a una nueva rama:
```
![Texto alternativo](/images/parte-3.2-3.png)
```bash
4. Realizar modificaciones simples y concretas:
   Modificar el componente de navegación
   Añadir un nuevo botón
   Cambiar los estilos del header
```

![Texto alternativo](/images/parte-3.2(4-1).png)
![Texto alternativo](/images/parte3.2-4(2).png)
![Texto alternativo](/images/parte3.2(4-3).png)

```bash
5. Añadir y commitear los cambios:
```
![Texto alternativo](/images/parte3.2-5.png)

```bash
6. Subir la rama al repositorio:
```

![Texto alternativo](/images/parte3.2-6.png)

```bash
7. Crear el Pull Request:
   Ir a GitHub
   Clic en "Compare & pull request"
   Base: desarrollo ← Compare: feature-nav-[tunombre]
   Título descriptivo
   Descripción detallada de los cambios realizados
   Asignar al propietario como reviewer
   Clic en "Create pull request"
```

![Texto alternativo](/images/parte3.2-7(1).png)
![Texto alternativo](/images/parte-3.2-7(2).png)
![Texto alternativo](/images/parte-3.2-7(3).png)
![Texto alternativo](/images/parte-3.2-7(4).png)

### 3.3 Pasos del Propietario para Gestionar el PR

```bash
1. Revisar el Pull Request:
   Ir a la pestaña "Pull requests"
   Abrir el PR creado por el colaborador
   Revisar los cambios en la pestaña "Files changed"
```

![Texto alternativo](/images/parte-3.3(1).png)
![Texto alternativo](/images/parte-3.3(2).png)
![Texto alternativo](/images/parte-3.3(3).png)

```bash
2. Proponer cambios si es necesario:
   Añadir comentarios específicos en las líneas de código
   Sugerir mejoras concretas
   Ejemplo: "El color del botón podría ser más oscuro para mejorar el contraste"
```
![Texto alternativo](/images/parte-3.3-2(1).png)

```bash
3. Solicitar cambios o aprobar:
   Si requiere cambios: "Review changes" → "Request changes"
   Si está todo correcto: "Review changes" → "Approve"
```

![Texto alternativo](/images/parte.3.3-3.png)

```bash
4. Realizar el merge:
   Una vez aprobado, clic en "Merge pull request"
   Confirmar el merge
   Borrar la rama del colaborador si ya no se necesita   
```

![Texto alternativo](/images/parte-3.3-4(2).png)
![Texto alternativo](/images/parte-3.3-4(3).png)
![Texto alternativo](/images/parte-3.3-4(3.1).png)

## Parte 4: Integración Final (20%)

```bash
1. Realizar merge de la rama desarrollo a main
```

![Texto alternativo](/images/parte-4.1.png)

```bash
2. Resolver cualquier conflicto que pueda surgir
```

![Texto alternativo](/images/parte-4.2.png)

```bash
3. Realizar un push final a GitHub
```

![Texto alternativo](/images/parte.4-3.png)