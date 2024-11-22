---
title: "Modelando la base de datos de tu proyecto de Desarrollador Fullstack"
description: "Una vez que hayas definido el alcance, es una buena idea generar el modelo de la base datos antes de empezar a codear. Esto te ayudará a agilizar el desarrollo de tu proyecto"
tags: ["postgres", "modeling","sql","4geeks"]
authors: ["arnaldoperez"]

---

<onlyfor saas="true" withBanner="false">

## 🌱 ¿Cómo comenzar un proyecto?

1. Inicia sesión en [quickdatabasediagrams.com](https://app.quickdatabasediagrams.com) y crea un nuevo diagrama.
2. Asegúrate que todos tus compañeros de equipo tambien hayan iniciado sesión e invitalos mediante su correo electrónico (Solo un miembro del equipo debe hacer este paso)
3. Luego podrás empezar a crear tu modelo y posteriormente compartirlo.

</onlyfor>

## 📝Instrucciones

Crear un modelo de datos (también conocido como Diagrama de Entidad-Relación) usando la Notación CrowFoot y basado en las historias de usuario que has definido para tu proyecto. Esta acción también puede ayudarte a evaluar el alcance que has definido para el mismo.

- Si notas que necesitas demasiadas tablas y que realizar transacciones para cada una de ellas tomará más tiempo del disponible, puedes ajustar las funcionalidades que incluirás en tu proyecto final.
- Tu proyecto debe tener autenticación, lo que probablemente signifique que tendrás una tabla de Usuario para las credenciales.
  
Pregúntate: ¿Qué cosas necesito agregar, eliminar, borrar o actualizar en mi proyecto? Esta es una excelente herramienta para identificar las tablas necesarias.

- ¿Cómo se conectarán o relacionarán esas tablas entre sí? ¿Uno a uno? ¿Uno a muchos? ¿Muchos a muchos?
- Recuerda que las relaciones muchos a muchos requieren una tabla adicional (pivot) como conector.

Una vez que hayas terminado el modelo, [comparte el enlace en público](https://4geeks.com/es/lesson/aprender-en-publico) para un mejor aprendizaje.
