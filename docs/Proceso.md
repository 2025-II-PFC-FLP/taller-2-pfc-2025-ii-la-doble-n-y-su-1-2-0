# 📘 Taller 2:  Programación Funcional y Concurrente
**Tema:** Ejercicios de programación: Conjuntos difusos

🗓️**Fecha:** Octubre de 2025

---
## 🧩 Introducción
### 🔢 Conjuntos difusos y lógica difusa
Los conjuntos difusos son una extensión de los conjuntos clásicos que permiten representar la pertenencia parcial de un elemento. A diferencia de los conjuntos 
tradicionales donde un elemento pertenece completamente (1) o no pertenece (0), en los conjuntos difusos un elemento puede tener un grado de pertenencia entre 0 y 1.

Este taller implementa `siete operaciones fundamentales` sobre conjuntos difusos:

1. **Pertenece**: Función que evalúa el grado de pertenencia de un elemento en un conjunto difuso
2. **Grande**: Función que determina qué tan "grande" es un número
3. **Complemento**: Operación que invierte los grados de pertenencia de un conjunto
4. **Union**: Operación que combina dos conjuntos difusos tomando el máximo
5. **Interseccion**: Operación que combina dos conjuntos tomando el mínimo
6. **Inclusion**: Relación que verifica si un conjunto está contenido en otro
7. **Igualdad**: Relación que verifica si dos conjuntos son idénticos

---
## ALGORITMOS
### 🔷 DEFINICIÓN FUNCIÓN "PERTENECE"


---
## ALGORITMOS
### 🔷 DEFINICIÓN FUNCIÓN "GRANDE"
La función `grande` crea un conjunto difuso que modela el concepto de "números grandes" mediante una función sigmoidal parametrizada. Utiliza la siguiente fórmula matemática:

Para un número $n$, su grado de pertenencia al conjunto de "números grandes" se define como:

$$
\text{grande}(n) =
\begin{cases}
0 & \text{si } n \leq 0 \\
\left(\frac{n}{n+d}\right)^e & \text{si } n > 0
\end{cases}
$$


---
## ALGORITMOS
### 🔷 DEFINICIÓN FUNCIÓN "COMPLEMENTO"


---
## ALGORITMOS
### 🔷 DEFINICIÓN FUNCIÓN "UNION"


---
## ALGORITMOS
### 🔷 DEFINICIÓN FUNCIÓN "INTERSECCIÓN"


---
## ALGORITMOS
### 🔷 DEFINICIÓN FUNCIÓN "INCLUSION"


---
## ALGORITMOS
### 🔷 DEFINICIÓN FUNCIÓN "IGUALDAD"


---