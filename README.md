# Sistema de Control para una Pierna Robótica de 2 GDL

Proyecto desarrollado para la asignatura **Sistemas de Control Continuo** de la **Universidad de Antioquia**.

## Descripción

Este proyecto presenta el modelado, análisis y diseño de estrategias de control para una **pierna robótica de dos grados de libertad (2 GDL)** que representa las articulaciones de la cadera y la rodilla. El sistema tiene como objetivo reproducir trayectorias de marcha mediante técnicas clásicas y modernas de control, evaluando el desempeño de diferentes controladores a través de simulaciones computacionales.

El desarrollo se enfoca en el seguimiento de trayectorias, la estabilidad del sistema y la robustez frente a perturbaciones e incertidumbres del modelo.

---

## Objetivos

* Modelar dinámicamente una pierna robótica de 2 GDL.
* Obtener una representación en espacio de estados del sistema.
* Diseñar y comparar diferentes estrategias de control.
* Evaluar el desempeño mediante simulaciones.
* Analizar el impacto sociotécnico del sistema y las implicaciones de diseño orientadas a la seguridad y accesibilidad.

---

## Estrategias de control implementadas

* Control PID.
* Compensación en el dominio de la frecuencia.
* Realimentación de estados con acción integral.

---

## Herramientas utilizadas

* Python 3
* Google Colab
* NumPy
* SciPy
* Python-Control
* Matplotlib

---

## Modelo del sistema

El sistema se representa mediante una formulación en espacio de estados:

$$
\dot{x}=Ax+Bu
$$

$$
y=Cx+Du
$$

donde:

- **Estados:** posiciones y velocidades angulares de la cadera y la rodilla.
- **Entradas:** torques aplicados por los actuadores.
- **Salidas:** posiciones articulares.

---

## Resultados esperados

Se evalúan los controladores mediante indicadores clásicos de desempeño:

* Error de seguimiento.
* Tiempo de establecimiento.
* Sobreimpulso.
* Error en estado estacionario.
* Robustez frente a perturbaciones.
* Estabilidad del sistema.

---

## Impacto del proyecto

Este trabajo busca demostrar la aplicación de técnicas de control continuo en sistemas robóticos con potencial uso en rehabilitación y asistencia al movimiento humano. Además del desempeño técnico, se consideran aspectos relacionados con la seguridad del usuario, accesibilidad, confiabilidad e impacto social del sistema.

## Autores

**Oscar David Mercado Gómez**

**Carlos Daniel Galvis Ramirez**

Ingeniería Electrónica
Universidad de Antioquia

---

## Licencia

Este proyecto fue desarrollado con fines académicos para la asignatura **Sistemas de Control Continuo** de la Universidad de Antioquia.
