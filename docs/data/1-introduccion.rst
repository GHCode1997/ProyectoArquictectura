Introducción
=================================

Nombre del proyecto:
--------------------------
                Sistema de análisis y gestión de consultas del clima (SAGCC)


Equipo de diseño: 
-----------------
        - Gustavo Huerta
        - Cristobal Marinkovic
        - Pablo Valeria
La meta de ingeniería de software es producir soluciones de software robustas, de alta calidad que provean valor a sus usuarios. Alcanzar este objetivo requiere la precisión de la ingeniería combinada con la sutileza del arte [1]. Esta meta presenta retos formidables cuando los sistemas de software a gran escala de hoy en día se encuentran entre las estructuras más complejas jamás construidas por humanos. Si estos retos no se resuelven antes de tiempo, los sistemas se entregan tarde, por encima del presupuesto o con un nivel de calidad inaceptablemente bajo [2].

La arquitectura de software de un sistema informático es el conjunto de estructuras necesarias para el razonamiento sobre el sistema, que comprende los elementos de software, las relaciones entre ellos, y propiedades de ambos. Es lo que hace que los conjuntos de partes de un sistema trabajen juntas como un todo coherente y exitoso, por lo que resulta ser crítica especialmente en sistemas de software intensivos. Ha emergido como una importante subdisciplina de la ingeniería de software [3].

Incluso la mejor arquitectura, la más adecuada para el trabajo, será esencialmente inútil si las personas que la necesitan no saben lo que es, no pueden entenderla lo suficientemente bien como para aplicarla, o la malinterpretan y aplican incorrectamente [3]. En consecuencia, la documentación es tan importante como la implementación de la solución.

Esta documentación tiene como propósito describir la arquitectura de software de SAGCC. El proyecto está enmarcado dentro de la asignatura ICC368: Arquitectura de Software, impartida por el Dr. Ricardo Gacitúa a alumnos de la carrera Ingeniería Civil Informática de la Universidad de La Frontera ubicada en Temuco, Chile.

SAGCC es una aplicación de captura, visualización y comunicación con expertos, sobre datos climáticos a través de una interfaz de usuario móvil y web. Los stakeholders son usuarios genéricos interesados en visualizar estos datos y resolver dudas potenciales, y pequeñas empresas agrícolas, que pueden mejorar sus procesos de negocio con mediciones y visualización de parámetros medioambientales de sus plantaciones.

Para producir la documentación se aplican A Visual Ad-Hoc Methodology [4] y A Template for Documenting Software and Firmware Architectures [5], junto con el uso de elementos de modelado de UML 2.5.1 [6], C4 Model [7] y ArchiMate 3.0.1 [8].

Esta documentación es un híbrido entre los dos tipos de documentación arquitectural descritos en [5], dado que tiene como propósito proveer un entendimiento compartido entre los stakeholders y a la vez describir la arquitectura de un modo preciso y detallado. Para esto, se representa la problemática con variados niveles de abstracción según el tema abordado.
