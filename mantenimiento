Informe Técnico – Sistema de Gestión de Biblioteca
Este documento resume el Trabajo Práctico Experimental N.3: Informe Técnico – Sistema de Gestión de Biblioteca , desarrollado por el Grupo N.-4 de la Carrera de Ingeniería de Software  de la UNEMI (Universidad Estatal de Milagro).
- Descripción del Caso
El Sistema de Gestión de Biblioteca es una aplicación informática cliente-servidor con almacenamiento local desarrollada para optimizar la administración de los recursos bibliográficos en una institución. Su función principal es registrar los libros disponibles, gestionar los préstamos a los usuarios y controlar las devoluciones.

- Módulos Principales 

Módulo de Libros: Registra nuevos ejemplares, títulos, autores, categorías y su estado de disponibilidad.

Módulo de Préstamos: Permite asignar libros a usuarios y lleva el control de las fechas de entrega y devolución.


Módulo de Reportes: Genera listados de préstamos activos, devoluciones pendientes y estadísticas de uso.

- Análisis del Problema (Limitaciones Actuales) 

Se detectaron limitaciones funcionales que afectan la fiabilidad y eficiencia del servicio:


Ausencia de control de disponibilidad: El sistema actual no verifica si un libro está prestado antes de autorizar un nuevo préstamo, lo que genera duplicaciones y pérdida de control sobre los ejemplares físicos.


Falta de registro de usuarios: No es posible conocer quién tiene un libro en préstamo ni su historial de uso, lo que limita la trazabilidad y complica la gestión de devoluciones.


- Reportes limitados
El módulo de reportes es básico y no permite obtener información detallada sobre préstamos vencidos o estadísticas de uso, impidiendo tomar decisiones informadas.

- Objetivos y Justificación
El objetivo prioritario es aplicar un proceso de mantenimiento que corrija los errores detectados y mejore la funcionalidad del software , buscando optimizar el uso del sistema y garantizar un mayor control sobre los recursos bibliográficos.

Mejorar la calidad de los datos y reducir los errores humanos.

Favorecer la transparencia en la gestión de préstamos.

Lograr que la estructura del sistema sea más escalable.

- Requerimientos: Cambio Funcional Propuesto

Nombre del Cambio: Módulo de control de usuarios y disponibilidad de libros.

- Descripción y Funcionalidades

Se propone desarrollar un nuevo módulo que gestione la información de los usuarios y controle la disponibilidad de los ejemplares.

Incluirá funcionalidades para registrar, modificar y eliminar usuarios.
Se añadirá una validación automática que verifique el estado del libro antes de permitir un nuevo préstamo.

- Mejoras que Aporta 

Aumenta la trazabilidad de los préstamos y devoluciones.

Mejora la integridad de la base de datos al evitar registros duplicados.

Optimiza la experiencia del usuario al garantizar información actualizada.

Facilita la generación de reportes y estadísticas de uso.

- Implementación Técnica

Crear una nueva tabla Usuarios en la base de datos.

Modificar la tabla Libros para incluir un campo Estado (Disponible/Prestado).

Relacionar Usuarios con Préstamos mediante un identificador único.

Esquema de Módulo Propuesto (Modelo de Datos): 
- Tipo de Mantenimiento Propuesto

De acuerdo con las clasificaciones de Sommerville (2011) y Pressman (2014):

- Mantenimiento Correctivo 

Enfoque: Corrección de defectos detectados durante el funcionamiento del sistema.

Aplicación: Resolver los errores de validación que permiten los préstamos duplicados.

Justificación Técnica: La corrección de la lógica de validación fortalecerá la confiabilidad del sistema al asegurar que no se realicen préstamos simultáneos del mismo ejemplar.

- Mantenimiento Perfectivo 

Enfoque: Mejorar las características funcionales y de rendimiento del sistema, incorporando nuevas funciones.

Aplicación: Añadir el módulo de usuarios y el control de disponibilidad.

Justificación Técnica: Responde a una necesidad evolutiva del sistema, mejorando la trazabilidad y eficiencia en la gestión bibliotecaria.

- Evaluación del Impacto

Criterio

Control de disponibilidad

Registro de usuarios

Confiabilidad de datos

Trazabilidad

Mantenibilidad

Escalabilidad
