# Unidad 6: Resolución Numérica de EDOs (Euler y RK4)

Implementación modular en Java de los métodos de **Euler** y **Runge-Kutta de 4to orden (RK4)** para resolver Problemas de Valor Inicial (PVI) con criterio de paro por número de pasos $N$.

## Requisitos
- Java JDK (versión 8 o superior)
- Git

## Clonación, compilación y ejecución desde terminal

```bash
# 1. Clonar el repositorio
git clone <URL_DE_TU_REPOSITORIO>
cd <NOMBRE_DE_LA_CARPETA>

# 2. Compilar ambas clases
javac MetodoEuler.java MetodoRungeKutta.java

# 3. Ejecutar Método de Euler
java MetodoEuler

# 4. Ejecutar Método de Runge-Kutta (RK4)
java MetodoRungeKutta