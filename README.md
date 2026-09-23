# 📚 Portafolio de Ingeniería de Requisitos

Repositorio correspondiente al portafolio de evidencias del curso **Ingeniería de Requisitos** del Programa de Ingeniería de Software de la **Universidad Pontificia Bolivariana (UPB)**.

Este repositorio reúne los principales artefactos desarrollados durante el curso y organiza su documentación para facilitar la consulta, revisión y trazabilidad de los requisitos a través de las diferentes etapas del proceso de desarrollo de software.

---

## 🎯 Objetivo del repositorio

Consolidar en un único espacio los artefactos producidos durante el curso de Ingeniería de Requisitos, manteniendo una estructura organizada y trazable que permita relacionar:

**Necesidades del negocio → Requisitos → Modelos → Prototipos → Código → Pruebas → Resultados**

El repositorio también incorpora metadatos y mecanismos de trazabilidad para facilitar la identificación, seguimiento y estado de los artefactos.

---

# 📂 Estructura del repositorio

El portafolio se encuentra organizado por proyectos y por la gestión transversal de los artefactos.

| Carpeta | Descripción |
|---|---|
| `Aplicacion_Dietas` | Artefactos relacionados con el sistema **Dietas al Día**, incluyendo prototipado, requisitos y trazabilidad. |
| `Empresa_Mudanza` | Modelos y artefactos correspondientes al caso de la empresa de mudanza. |
| `Operaciones_Aereas` | Artefactos correspondientes al caso de la empresa de operaciones aéreas. |
| `Vehiculo_Conduccion` | Artefactos relacionados con el simulador de vehículo de conducción. |
| `Matriz_Trazabilidad` | Documentación asociada a la trazabilidad de requisitos y artefactos. |
| `Lecciones_Aprendidas` | Reflexiones finales y aprendizajes obtenidos durante el proceso. |

---

# 🗂️ Proyectos incluidos

## ✈️ 1. Empresa de Operaciones Aéreas

Este caso contiene artefactos relacionados con la definición y gestión de requisitos de una empresa de operaciones aéreas.

### Artefactos principales

- Product Vision Board
- Product Backlog
- Request for Change (RFC)
- Artefactos de modelado y documentación asociados al proyecto

### Propósito

Representar la identificación de necesidades, definición del producto y gestión de cambios dentro del contexto de una organización de operaciones aéreas.

---

## 🚗 2. Simulador de Vehículo de Conducción

Este proyecto reúne los artefactos utilizados para especificar y modelar el comportamiento y estructura de un simulador de vehículo de conducción.

### Artefactos principales

- Especificación de Requisitos de Software (SRS)
- Diagrama de casos de uso
- Diagramas UML
- Modelos estructurales
- Modelos de comportamiento
- Casos de prueba

### Propósito

Documentar los requisitos del sistema mediante diferentes técnicas de modelado y especificación, relacionando las necesidades identificadas con los modelos del sistema.

---

## 📦 3. Empresa de Mudanza

Este caso contiene diferentes modelos utilizados para representar los requisitos y estructura del sistema.

### Artefactos principales

- Diagrama de casos de uso
- Diagrama entidad-relación
- Diagrama UML de clases

### Propósito

Representar las funcionalidades y estructura de información necesarias para el sistema mediante modelos de requisitos y diseño.

---

## 🥗 4. Dietas al Día

**Dietas al Día** corresponde a una aplicación orientada al apoyo de decisiones nutricionales.

Este proyecto fue seleccionado para desarrollar la **matriz de trazabilidad de requisitos y artefactos**.

### Artefactos principales

- Épicas y requisitos
- Prototipo funcional de alta fidelidad
- Criterios de aceptación
- Código fuente
- Matriz de trazabilidad

### Requisito seleccionado

**EPC-28 — Asignación tratamiento nutricional**

> Como médico del Departamento de Nutrición quiero consultar las dietas compatibles con el diagnóstico de un paciente, señalando explícitamente si alguna dieta contiene alimentos incompatibles con sus alergias registradas, para elegir con seguridad un tratamiento sin cruzar manualmente la historia clínica con el catálogo de dietas.

### Criterios de aceptación

**CA1.** Dado un paciente con una enfermedad registrada, el sistema debe mostrar las dietas asociadas en un solo paso.

**CA2.** Si una dieta recomendada contiene un alimento incompatible con una alergia registrada del paciente, el sistema debe mostrar una alerta clara antes de confirmar.

**CA3.** El médico debe poder acceder a la ficha técnica completa de la dieta sin perder el contexto del paciente.

**CA4.** Un usuario nuevo debe poder seleccionar una dieta segura en menos de 90 segundos sin omitir las alertas correspondientes.

---

# 🔗 Trazabilidad de requisitos

La trazabilidad permite realizar el seguimiento de los requisitos a través de los diferentes artefactos del proyecto.

Para el caso **Dietas al Día**, se construyó una matriz de trazabilidad tomando como requisito principal el **EPC-28 — Asignación tratamiento nutricional**.

La cadena de trazabilidad considerada es:

```text
Necesidad de negocio
        ↓
Requisito / Épica
        ↓
Criterios de aceptación
        ↓
Prototipo
        ↓
Código
        ↓
Casos de prueba
        ↓
Resultado de validación
