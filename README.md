# Actividad 2: Método de Runge-Kutta de 4to Orden (RK4) Modular en Java

Implementación modular en Java del algoritmo clásico de **Runge-Kutta de cuarto orden (RK4)** para la resolución numérica de Problemas de Valor Inicial (PVI).

## Descripción del Problema
El programa aproxima numéricamente la solución de la ecuación diferencial:
$$y' = x + y$$

Con las siguientes condiciones iniciales y parámetros de malla:
* **Condición inicial:** $y(0) = 1.0$
* **Intervalo de evaluación:** $x \in [0.0, 0.3]$
* **Tamaño de paso ($h$):** `0.1`
* **Solución analítica de referencia:** $y(x) = 2e^{x} - x - 1$

## Requisitos Previos
* **Java Development Kit (JDK):** Versión 11 o superior.
* **Git** instalado en el sistema.

## Clonación del Repositorio
Para descargar el proyecto de forma local, ejecuta en tu terminal:

```bash
git clone <URL_DE_TU_REPOSITORIO>
cd <NOMBRE_DE_LA_CARPETA>/src
```

*(Nota: Si el archivo `.java` se encuentra en la raíz del repositorio, omite `/src`).*

## Compilación y Ejecución desde la Terminal

1. **Compilar el archivo fuente:**
   ```bash
   javac MetodoRungeKutta.java
   ```

2. **Ejecutar el programa:**
   ```bash
   java MetodoRungeKutta
   ```

## Ejemplo de Salida Esperada ($h = 0.1$)
```text
         x_n     y_n (RK4)
----------------------------------------
0        0.0000  1.0000
1        0.1000  1.1103
2        0.2000  1.2428
3        0.3000  1.3997
```