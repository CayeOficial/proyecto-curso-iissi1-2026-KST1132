# Título Proyecto

## Miembros del grupo L2 - GRUPO 3

1. Barrera Lozano, Cayetano
2. Ragel Ruiz, Luca
3. García Félix, Alejandro

## 1. Introducción al problema

Nuestro cliente corresponde a una empresa la cual se dedica a la construcción, rehabilitación y reformas de infraestructuras por todo el territorio Español. Una de las muchas labores que se llevan a cabo en dicha empresa es el control en cuanto al registro de jornada laboral.

Actualmente el cliente lleva a cabo el registro de la jornada laboral manualmente mediante partes de trabajo "a papel", donde el responsable de cada obra escribe a mano las horas de entrada y salida de cada trabajador para posteriormente enviarlas al responsable que se encuentra en las oficinas de la empresa. 

Sin embargo, en cuanto a este método utilizado, encuentran varios inconvenientes, entre ellos los siguientes:

- En España, el registro de la jornada laboral está regulado en el artículo 34.9 del Estatuto de los Trabajadores (introducido por el [Real Decreto-ley 8/2019](https://www.boe.es/eli/es/rdl/2019/03/08/8/con)) y es de obligatorio cumplimiento para todas las empresas, con independencia de su tamaño o sector.
El Ministerio de Trabajo mantiene en tramitación un proyecto de Real Decreto de Registro de Jornada Digital. Cuando este texto definitivo se apruebe y se publique en el Boletín Oficial del Estado (BOE). El formato físico (papel y plantillas manuales) quedará expresamente prohibido y se exigirá obligatoriamente que el sistema sea electrónico o digital, garantizando la inmutabilidad de los datos (que no se puedan borrar ni alterar los fichajes sin dejar una huella/auditoría clara).

- El personal de oficina debe esperar a que los responsables de cada obra envíen los partes, lo que a menudo provoca retrasos.

- Han ocurrido algunos incidentes que involucran las pérdidas de dichos partes con sus correspondientes sanciones económicas, así como las dificultades del personal de oficina para calcular el salario mensual de los trabajadores afectados.


- Descripción del problema para poner en contexto el proyecto, incluyendo información sobre los clientes y usuarios, la situación actual, problemas, expectativas, etc. Se valorará la presencia de información multimedia (fotos, gráficos, documentos escaneados, etc.).

## 2. Glosario de términos

- Términos específicos del dominio del problema, ordenados alfabéticamente. Se valorará la presencia de información multimedia.

## 3. Visión general del sistema

### 3.1. Requisitos generales

### 3.2. Usuarios del sistema

## 4. Catálogo de requisitos

### 4.1. Requisitos funcionales

#### R.F.01. Título requisito funcional

Como [tipo de usuario]
quiero [servicio]
para [razón]

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### 4.1.1. Requisitos de información

##### R.I.01. Título requisito de información

Como [tipo de usuario]
quiero [servicio]
para [razón]

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- ...

#### 4.1.2. Reglas de negocio

##### R.N.01. Título regla negocio

Descripción de la regla de negocio.

### 4.2. Mapa de historias de usuario (opcional)

### 4.3. Requisitos no funcionales (opcional)

**R.N.F. 01. Título requisito no funcional**
Como [tipo de usuario]
quiero [servicio]
para [razón]

-- fin entregable 1 --

## 5. Modelo conceptual

### 5.1. Diagramas de clases UML

- con restricciones.

### 5.2. Escenarios de prueba

- con descripción textual y diagrama de objetos UML.

## 6. Matrices de trazabilidad

- Matriz de trazabilidad entre los elementos del modelo conceptual y los requisitos.

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:------|:-----------|:-----------|:-----------|:-----------|
| RI-1  | X          | X          | X          | X          |
| RI-2  |            | X          |            | X          |
| RF-1  |            | X          |            | X          |
| RF-2  | X          |            | X          | X          |
| RN-1  |            | X          |            |            |
| RN-2  | X          | X          | X          |            |
| ...   |            |            |            |            |

-- fin entregable 2 --

## 7. Modelo relacional en 3FN

- Relaciones obtenidas al aplicar la transformación del modelo conceptual.

### 7.1.  Justificación de la estrategia de transformación de jerarquías

- si se identificaron jerarquías en el MC.


### 8. Matriz de trazabilidad MC/SQL (opcional):

- Restricciones sobre el MC / Elementos del modelo tecnológico (SQL) (Triggers, checks, etc.)
- Incluir Reglas de negocio — Constraints/Triggers en las matrices de trazabilidad para el entregable 3

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:-------|:-------|:-------|:-------|:-------|
| TABLA-1 |        |        |        |        |
| TABLA-2 |        |        |        |        |
| TABLA-3 |        |        |        |        |
| TABLA-4 |        |        |        |        |
| TRIG-1 |        |        |        |        |
| TRIG-2 | X      | X      |        | X      |
| TRIG-3 |        | X      |        | X      |
| TRIG-4 |        |        | X      |        |
| CONST-1 |        |        |        |        |
| CONST-2 | X      | X      |        | X      |
| CONST-3 |        | X      |        | X      |
| CONST-4 |        |        | X      |        |

Se consideran todo tipo de constraints declarativas (aquellas definidas durante el CREATE TABLE).
-- fin entregable 3 --

## Referencias


