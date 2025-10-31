### Módulo 1: Auditoría Informática (Conceptos y Metodología)

La auditoría es un **proceso sistemático, independiente y documentado**[cite: 1133, 1135, 1136, 1145]. Su fin es obtener **evidencias** (pruebas) y evaluarlas objetivamente para determinar si se cumplen ciertos **criterios** (políticas, normas o requisitos)[cite: 1145, 1146, 1147]. Las diferencias encontradas se llaman **hallazgos**[cite: 1148].

**Actores y Tipos:**

- **Actores:** Cliente (solicita la auditoría), Auditor (ejecuta) y Auditado (es examinado)[cite: 1152, 1160, 1161].
- **Tipos (Relación del Auditor):**
  - **Interna:** Realizada por personal de la propia organización[cite: 1165].
  - **Externa:** Realizada por una entidad independiente[cite: 1166].
- **Tipos (Relación del Cliente):**
  - **De Primera Parte:** Auditoría interna[cite: 1158].
  - **De Segunda Parte:** Una organización audita a un proveedor[cite: 1167].
  - **De Tercera Parte:** Una entidad externa e independiente audita para certificar (ej. una norma ISO)[cite: 1168].

**Enfoques de Control:**
La auditoría se enfoca en dos tipos de controles[cite: 1218, 1219]:

1.  **Controles Generales de TI (CGTI):** Son la base. Se aplican a todo el ambiente de TI (seguridad, desarrollo, operaciones)[cite: 1220, 1226].
2.  **Controles de Aplicación:** Específicos de un sistema o proceso (ej. validaciones en un formulario)[cite: 1244]. La efectividad de estos depende de la fortaleza de los CGTI[cite: 1220].

#### Las 4 Fases de la Metodología de Auditoría

El proceso de auditoría se divide en cuatro etapas claras[cite: 1010, 1011, 1012, 1013]:

**1. Planificación:**

- Es la fase inicial para definir el marco de trabajo[cite: 1014].
- Se define el **alcance** (los límites de la auditoría) y los **objetivos**[cite: 1021, 1177].
- Se estudia el entorno a auditar [cite: 1022], se determinan los recursos (humanos, tiempo) [cite: 1023] y se elaboran los programas de trabajo[cite: 1024].

**2. Ejecución (Trabajo de Campo):**

- Es la actividad principal donde se obtienen las evidencias[cite: 1015, 1072].
- Se usan dos tipos de procedimientos:
  - **Pruebas de Cumplimiento:** Verifican que los controles existan y se usen eficazmente[cite: 1076].
  - **Pruebas Sustantivas:** Verifican la validez e integridad de los datos (ej. saldos, transacciones)[cite: 1077].
- **Técnicas de Ejecución (Cómo se obtienen las evidencias):**
  - **Relevamiento:** Recopilar información para entender el área[cite: 1089].
  - **Análisis:** Descomponer un proceso en sus partes[cite: 1090].
  - **Observación:** Verificación ocular de cómo se realiza un proceso[cite: 1093].
  - **Indagación:** Obtener información mediante entrevistas[cite: 1092].
  - **Confrontación:** Comparar lo observado con los criterios/normas para hallar diferencias[cite: 1091].
  - **Comprobación:** Revisar documentos para verificar la legalidad y autorización de las operaciones[cite: 1100].
  - **Cálculo:** Verificación aritmética[cite: 1098].
  - **Conciliación:** Comparar información de distintas fuentes para verificar que coincidan[cite: 1115].
  - **Circularización:** Obtener confirmación por escrito de un tercero externo (ej. un banco)[cite: 1117].

**3. Informe:**

- Es el producto final donde se comunican los resultados[cite: 1017].
- Contiene: observaciones (hallazgos), conclusiones y recomendaciones[cite: 1120].
- Se entrega un **Informe Preliminar** al auditado para que pueda hacer descargos o correcciones[cite: 1123].
- Luego, se emite el **Informe Final**[cite: 1031].

**4. Seguimiento:**

- Fase posterior donde el auditor revisa si el auditado implementó las acciones correctivas recomendadas[cite: 1018, 1019, 1126].

---

### Módulo 2: Gestión de Seguridad (SGSI y Análisis de Riesgo)

Un **SGSI (Sistema de Gestión de la Seguridad de la Información)** es el marco que usa una organización para gestionar su seguridad.

**Pilares de la Seguridad (DCI):**
La seguridad de la información se define como la preservación de[cite: 203]:

- **Confidencialidad:** La información solo es accesible por personal autorizado[cite: 203, 1381].
- **Integridad:** La información no ha sido modificada sin autorización[cite: 203, 1385].
- **Disponibilidad:** La información y los sistemas están accesibles cuando se necesitan[cite: 203, 1388, 1390].

**El Ciclo de Deming (PDCA) del SGSI:**
El SGSI se basa en un ciclo de mejora continua[cite: 847]:

1.  **Plan (Planificar):** Establecer el SGSI. Definir la política, alcance, objetivos e identificar los riesgos[cite: 848, 849, 850, 854, 856].
2.  **Do (Hacer):** Implantar y operar el SGSI. Implementar el plan de tratamiento de riesgos y los controles[cite: 859, 860].
3.  **Check (Verificar):** Monitorizar y revisar el SGSI. Realizar auditorías internas y revisiones[cite: 869, 873, 874].
4.  **Act (Actuar):** Mantener y mejorar el SGSI. Aplicar acciones correctivas y preventivas[cite: 862, 863].

#### Proceso de Análisis de Riesgo

El análisis de riesgo es el corazón del SGSI.

- **Riesgo:** Es la combinación de la **Probabilidad** de que ocurra un evento y su **Impacto**[cite: 222, 928].
- **Amenaza:** Causa potencial de un incidente (ej. un malware, un incendio)[cite: 224, 1395].
- **Vulnerabilidad:** Una debilidad que puede ser explotada por una amenaza (ej. un software sin actualizar)[cite: 226].

**Pasos del Análisis de Riesgo:**

**1. Identificación y Clasificación de Activos:**

- Un **activo** es cualquier cosa de valor para la organización (datos, hardware, software, personas)[cite: 185, 837].
- Se debe hacer un inventario de activos[cite: 397, 1340].
- A cada activo se le asigna un **propietario**[cite: 398, 1345].
- Se clasifican según su criticidad usando los pilares **DCI** (Disponibilidad, Confidencialidad, Integridad)[cite: 1375].
  - **Confidencialidad:** (0) Público, (1) Reservado-Interno, (2) Confidencial, (3) Secreto[cite: 1382].
  - **Integridad:** (0) No aplica, (1) Bajo, (2) Medio, (3) Alto[cite: 1385].
  - **Disponibilidad:** (0) No aplica, (1) Bajo, (2) Medio, (3) Alto[cite: 1389].
- La suma de estos valores da la **Criticidad** del activo (Baja, Media, Alta)[cite: 1392].

**2. Valoración del Riesgo:**

- Se identifican las **amenazas** (ej. Ataques intencionados, Errores, Desastres) [cite: 1399, 1400, 1401] y **vulnerabilidades**[cite: 920].
- Se estima la **Probabilidad** (Frecuencia) y el **Impacto** (Daño)[cite: 925, 926, 1303].
- Se calcula el Nivel de Riesgo (Riesgo = Probabilidad x Impacto)[cite: 928].

**3. Tratamiento del Riesgo:**
Una vez conocido el riesgo, hay 4 opciones[cite: 285, 286, 287, 288, 935]:

1.  **MITIGAR:** Aplicar controles de seguridad para reducir el riesgo a un nivel aceptable[cite: 285, 936]. (Es la opción más común).
2.  **ACEPTAR:** No hacer nada. Se toma esta decisión si el riesgo es bajo ("apetito de riesgo") o el costo del control es mayor al del impacto[cite: 286, 945, 946].
3.  **EVITAR:** Eliminar la actividad o el activo que genera el riesgo[cite: 287, 939, 940].
4.  **TRANSFERIR:** Trasladar el riesgo a un tercero (ej. contratar un seguro, tercerizar un servicio)[cite: 288, 944].

**Riesgo Inherente vs. Residual:**

- **Riesgo Inherente:** Es el riesgo puro, sin ningún control aplicado[cite: 952].
- **Riesgo Residual:** Es el riesgo que permanece _después_ de haber aplicado los controles (tratamiento)[cite: 956].

---

### Módulo 3: Informática Forense y Gestión de Incidentes

Este módulo se centra en qué hacer _después_ de que ocurre un incidente de seguridad.

**Gestión de Incidentes (DFIR):**
Es el proceso para manejar las consecuencias de un incidente.

- **Fases:**
  1.  **Preparación y Prevención:** Análisis de riesgo, políticas, backups[cite: 20, 21, 23, 25].
  2.  **Detección y Análisis:** Darse cuenta del incidente, clasificarlo y priorizarlo[cite: 26, 29, 30].
  3.  **Contención, Remediación y Recuperación:** Aislar el problema, eliminarlo y volver a la normalidad[cite: 35, 36].
  4.  **Actividades Post-Incidente:** Aprender del incidente para evitar que se repita[cite: 39, 45].

#### Manipulación de Evidencia Digital

Este es el proceso técnico y legal para que las pruebas digitales sean válidas en un juicio[cite: 11, 12]. Tiene 3 etapas cruciales[cite: 56]:

**1. Recolección:**

- El objetivo es obtener todos los elementos que puedan ser evidencia[cite: 48].
- **Prerrequisitos:** Estudiar el caso [cite: 61], definir el objetivo [cite: 62], y contar con las herramientas de HW (bloqueadores de escritura, duplicadores) [cite: 66] y SW (software de imagen forense)[cite: 67].
- **Acceso:** Es vital verificar el nivel de acceso legal (Voluntario, Allanamiento, Notificación)[cite: 69, 70, 73, 74].
- **Estrategias:** Se puede tomar el equipo completo, hacer una imagen total (copia bit a bit) o una imagen parcial[cite: 79].

**2. Preservación:**

- Es la etapa más importante. El objetivo es asegurar que la investigación **NO altere la evidencia original**[cite: 88].
- **REGLA DE ORO: NUNCA se debe trabajar sobre el original**[cite: 89].
- Se deben realizar **Copias Forenses** (imágenes) para trabajar sobre ellas[cite: 90, 97].
- **Función HASH (MD5/SHA):** Se usa para verificar la integridad. Es una "huella digital" única de los datos[cite: 93].
- **Proceso Hash:**
  1.  Se calcula el HASH del disco original[cite: 93].
  2.  Se realiza la copia forense[cite: 90].
  3.  Se calcula el HASH de la copia[cite: 94].
  4.  **Ambos HASH deben coincidir perfectamente**. Esto prueba que la copia es exacta y no fue alterada[cite: 94, 98, 165].

**3. Manipulación (Manejo):**

- Se refiere a los procedimientos correctos para manejar la evidencia[cite: 101].
- **Principios:**
  1.  Siempre trabajar sobre una copia[cite: 106].
  2.  Usar **bloqueadores de escritura (write blockers)** si se accede al original para evitar cualquier escritura accidental[cite: 66, 107].
  3.  Mantener una adecuada **Cadena de Custodia**[cite: 108].
- **Cadena de Custodia (Chain of Custody):**
  - Es un **formulario o registro que documenta CADA acción realizada sobre la evidencia**: quién la recolectó, quién la transportó, quién la analizó, dónde estuvo guardada, y las fechas y horas de todo[cite: 111, 116].
  - Es el elemento legal primordial para asegurar la **admisibilidad de la evidencia** en la justicia[cite: 112]. Sin una cadena de custodia intacta, la evidencia puede ser descartada.
