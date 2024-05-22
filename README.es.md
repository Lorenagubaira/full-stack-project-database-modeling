---
title: "Modelando la base de datos de tu proyecto de Desarrollador Fullstack"
description: "Una vez que hayas definido el alcance, es una buena idea generar el modelo de la base datos antes de empezar a codear. Esto te ayudará a agilizar el desarrollo de tu proyecto"
tags: ["postgres", "modeling","sql","4geeks"]
authors: ["arnaldoperez"]

---

## ¿Cómo empezar?

1. Inicia sesión en (quickdatabasediagrams.com/)[https://app.quickdatabasediagrams.com/] y crea un nuevo diagrama.
2. Asegúrate que todos tus compañeros de equipo tambien hayan iniciado sesión e invitalos mediante su correo electrónico (Solo un miembro del equipo debe hacer este paso)
3. Luego podrás empezar a crear tu modelo y posteriormente compartirlo.

## 📝Instrucciones

Create a data model (a.k.a Entity Relationship Diagram) using the CrowFoot Notation and based on the user stories you have defined for your project. This action can also help you evaluate the scope you have defined for it.

- If you notice that you need too many tables and that making transactions for each one of them will take more time than available, you can adjust the functionalities you will include in your final project.
- Your project must have authentication, meaning you will probably have a User table for the credentials.
Ask yourself: Which things do I need to add, remove, delete, or update on my project? This is a great tool for identifying the necessary tables.
- How will those tables connect or relate with each other? One to one? One to many? Many to many?
- Remember that many-to-many relationships require an additional (pivot) table as a connector.

Once you have finished the model, [share the link in public](https://4geeks.com/lesson/learn-in-public) for better learning.