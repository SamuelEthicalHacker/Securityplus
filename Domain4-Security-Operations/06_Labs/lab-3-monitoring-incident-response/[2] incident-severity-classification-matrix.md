# Incident Severity Classification Matrix / Matriz de Clasificación de Severidad de Incidentes

## Overview / Descripción General

Dentro de un **SOC / Centro de Operaciones de Seguridad**, los eventos de seguridad deben evaluarse rápidamente para determinar si representan una amenaza real para la organización.

La **Incident Severity Classification Matrix / Matriz de Clasificación de Severidad de Incidentes** permite categorizar 
incidentes de seguridad según su impacto operativo y la evidencia de actividad maliciosa.
Este enfoque facilita la priorización de alertas y la asignación adecuada de recursos dentro del proceso de respuesta a incidentes.

Este modelo es utilizado por analistas de seguridad para distinguir entre eventos de bajo riesgo, actividad sospechosa y compromisos confirmados,
garantizando que los incidentes críticos reciban atención inmediata.

---

# Incident Classification Criteria / Criterios de Clasificación de Incidentes

La clasificación de severidad se basa en múltiples factores evaluados durante el proceso de alert triage / análisis inicial de alertas.

| Classification Factor / Factor de Clasificación | Descripción |
|---|---|
| Impact / Impacto | Grado en que el incidente afecta la confidencialidad, integridad o disponibilidad de los sistemas. |
| Scope / Alcance | Número de sistemas, usuarios o recursos potencialmente comprometidos. |
| Evidence of Compromise / Evidencia de Compromiso | Indicadores claros de actividad maliciosa dentro del entorno. |
| Threat Actor Activity / Actividad del Actor de Amenaza | Evidencia de comportamiento asociado a atacantes o malware. |
| Business Criticality / Criticidad del Negocio | Importancia del sistema afectado para las operaciones de la organización. |

# Incident Severity Classification Matrix / Matriz de Clasificación de Severidad

| Severity Level / Nivel de Severidad | Description / Descripción | Example Scenario / Escenario Ejemplo |
|---|---|---|
| Low Severity / Severidad Baja | Evento de seguridad sin evidencia de compromiso o con impacto mínimo. | Intentos aislados de autenticación fallida registrados en logs. |
| Medium Severity / Severidad Media | Actividad anómala que requiere análisis adicional pero sin indicios claros de explotación. | Múltiples intentos de acceso fallidos desde una misma dirección IP externa. |
| High Severity / Severidad Alta | Evidencia de comportamiento malicioso o intento de explotación de vulnerabilidades. | Escaneo de puertos activo contra un servidor interno o ejecución sospechosa de comandos. |
| Critical Severity / Severidad Crítica | Incidente confirmado con impacto directo en sistemas, credenciales o datos sensibles. | Compromiso de credenciales administrativas o ejecución de malware dentro de un servidor. |

# Operational Response / Respuesta Operacional

Cada nivel de severidad determina la acción que debe tomar el equipo de Operaciones de Seguridad.

| Severity Level / Nivel de Severidad | Operational Response / Respuesta Operacional |
|---|---|
| Low Severity / Severidad Baja | Registrar el evento y continuar monitoreo mediante herramientas de **Security Monitoring / Monitoreo de Seguridad**. |
| Medium Severity / Severidad Media | Iniciar investigación por un **SOC Analyst / Analista SOC** para validar si la actividad representa una amenaza real. |
| High Severity / Severidad Alta | Escalar el evento dentro del SOC e implementar medidas iniciales de contención si es necesario. |
| Critical Severity / Severidad Crítica | Activar el proceso completo de **Incident Response / Respuesta a Incidentes** y coordinar acciones de contención inmediata. |

# Integration with Security Operations / Integración con Operaciones de Seguridad

Esta matriz forma parte del proceso de **Security Monitoring and Incident Handling** / Monitoreo de Seguridad y Gestión de Incidentes,
utilizado en centros de operaciones de seguridad para priorizar alertas generadas por plataformas de monitoreo.

El flujo operativo típico incluye:

1. Log Collection / Recolección de Logs
2. Event Correlation / Correlación de Eventos
3. Security Alert Generation / Generación de Alertas de Seguridad
4. Alert Triage / Análisis Inicial de Alertas
5. Incident Severity Classification / Clasificación de Severidad
6. Incident Response Activation / Activación de Respuesta a Incidentes

Este enfoque permite que los analistas SOC identifiquen rápidamente incidentes de alto impacto y prioricen su investigación.

# Practical Example / Ejemplo Práctico

Durante un monitoreo de seguridad, el sistema SIEM detecta múltiples intentos de autenticación fallidos 
contra una cuenta administrativa provenientes de una dirección IP externa.

Evaluación:

| Factor | Evaluación |
|---|---|
| Impact / Impacto | Medio |
| Scope / Alcance | Cuenta privilegiada |
| Evidence of Compromise / Evidencia de Compromiso | No confirmada |
| Threat Actor Activity / Actividad del Atacante | Posible fuerza bruta |

Clasificación resultante:

**Medium Severity / Severidad Media**

Ahora bien, ¿Qué acción es la más adecuada y común en un escenario como este?

El proceso suele seguir estos pasos: 

- Investigación por parte del **SOC Analyst / Analista SOC**
- Monitoreo de actividad relacionada
- Posible bloqueo de la dirección IP sospechosa



