# UNIVERSIDAD TÉCNICA DE AMBATO
## Facultad de Ingeniería en Sistemas, Electrónica e Industrial
### Carrera de Software

* **Estudiante:** Esteban Zambrano
* **Nivel/Paralelo:** Primer Semestre "B"
* **Materia:** Programación Orientada a Objetos

---

# Taller Práctico: Ejercicios Fundamentales de POO

Este documento detalla la comprensión y la lógica aplicada en los 5 ejercicios prácticos basados en los conceptos fundamentales de Programación Orientada a Objetos (clases, atributos, constructores, referencias y bucles).

---

## 1. Notas del curso
* **Qué se aprende:** Creación de una clase con atributos básicos, uso de un constructor para instanciar objetos y aplicación de estructuras condicionales (`if-else`) para clasificar resultados numéricos.
* **Lógica clave:** Calcular un promedio a partir de tres notas y evaluar rangos específicos para determinar si un estudiante está **Aprobado** ($\ge 7$), **Supletorio** (entre $5$ y $6.99$) o **Reprobado** ($< 5$), llevando un contador total de aprobados.

## 2. Inventario de una tienda
* **Qué se aprende:** Gestión de datos numéricos en objetos y manipulación directa de atributos (como el stock) para simular transacciones comerciales.
* **Lógica clave:** Actualizar las unidades disponibles de un producto tras una venta, evaluar alertas de reposición cuando el stock es menor a $5$, y calcular el valor total del inventario multiplicando el precio por el stock de cada elemento.

## 3. Veterinaria
* **Qué se aprende:** Comprensión profunda del manejo de **referencias de objetos** en la memoria de Java en lugar de copias de valores.
* **Lógica clave:** Al asignar un objeto a otro (`Mascota m4 = m1;`), ambos apuntan exactamente a la misma dirección de memoria. Por lo tanto, cualquier modificación en la edad o atributos realizada desde el segundo objeto afecta directamente al primero.

## 4. Cuenta de ahorro
* **Qué se aprende:** Implementación de bucles repetitivos de tipo `while` combinados con la evolución del estado de un objeto en el tiempo.
* **Lógica clave:** Simular un proceso de ahorro mes a mes incrementando el saldo mediante depósitos constantes hasta alcanzar o superar una meta establecida (500), contabilizando de forma exacta el número de meses necesarios para cada cuenta.

## 5. Biblioteca
* **Qué se aprende:** Relación y modelado entre dos entidades o clases diferentes (`Libro` y `Socio`) dentro de un mismo sistema.
* **Lógica clave:** Modificar el estado lógico (`disponible = false`) de un recurso al ser solicitado por un usuario, incrementar el contador de elementos prestados del socio correspondiente, y calcular cuántos recursos libres quedan en total en el sistema.
