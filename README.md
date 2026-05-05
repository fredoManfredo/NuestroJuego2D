# 🎮 Proyecto: Nuestro Primer Juego 2D (Godot Engine)

¡Bienvenidos al repositorio oficial de nuestro videojuego! Este es un proyecto familiar que conecta a **Bolivia 🇧🇴** y **Alemania 🇩🇪** para crear, aprender y divertirnos desarrollando en Godot Engine.

---

## 👥 Equipo y Roles

| Miembro | Rol | Responsabilidades |
| :--- | :--- | :--- |
| **Jair** | **Lead Programmer** | Encargado de GDScript y Lógica del juego |
| **Amir** | **Art & Asset Manager** | Creación de personajes, fondos y animaciones (Sprites). |
| **Sabi** | **Tech Mentor** | Apoyo en lógica de programación y resolución de dudas. |
| **Manf** | **QA** | revisión de código y gestión de GitHub. |

---

## 📂 Estructura del Proyecto

Para mantener el orden, todo lo que Godot Engine utiliza debe ir dentro de la carpeta `Assets/`. Lo que no sea del juego (ideas, bocetos) va en `Docs/`.

### 🛠 Carpeta de Producción (`HobbyHeroes/Assets`)

* **`scenes/`**  - Escenas principales del juego (.tscn)
    * **`player/`**
    * **`enemies/`**
    * **`ui/`**
    * **`levels/`**
* **`scripts/`**  - Codigo en GDScript (.gd)
    * **`player/`**
    * **`enemies/`**
    * **`systems/`**
* **`art/`**  - Sprites, tilesets, fondos animaciones
    * **`characters/`**
    * **`tilesets/`**
    * **`backgrounds/`**
* **`audio/`**  - Música y efectos de sonido
    * **`music/`**
    * **`sfx/`**
* **`resources/`**  - Data, shaders, configuraciones reutilizables (.tres/ .res)
    * **`data/`**
    * **`shaders/`**


### 📝 Carpeta de Diseño (`Docs/`)
* **`Borradores/`**: Dibujos e ideas de Amir que aún no están en el juego.
* **`Referencias/`**: Imágenes o links de inspiración.
* **`*.md`**: Documento de Diseño del Juego (mecánicas e historia).

---

## 🚀 Flujo de Trabajo (Git Workflow)

1.  **Pull:** Siempre descargar los cambios antes de empezar (`Fetch & Pull`).
2.  **Desarrollar:** Jair programa, Amir guarda artes terminados en `art/`.
3.  **Commit:** Guardar avances con mensajes claros (ej: *"Añadido salto al jugador"*).
4.  **Push:** Subir los cambios a la nube para que el equipo pueda revisarlos.

---

## 🛠 Requisitos Técnicos
* **Godot Engine Version:** 4.x (estable)
* **Plataforma:** 2D (Física 2D, Rigidbody2D).
* **Lenguaje:** GDScript.
* **Editor:** Godot Editor.

---
*Hecho con ❤️ por el Team Bolivia-Alemania.*