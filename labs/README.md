# 🧪 Laboratorios de Aprendizaje - AWS re/Start

Este repositorio documenta los laboratorios prácticos realizados durante el bootcamp intensivo de **Generation Chile** en colaboración con **Bootcamp Institute**. Los ejercicios están alineados con el programa **AWS re/Start** y se centran en la implementación de seguridad automatizada, gestión de bases de datos administradas y operaciones SQL avanzadas.

---

## 🛠️ Listado de Laboratorios Técnicos

### 🔍 [Gestión de Vulnerabilidades con Amazon Inspector](./amazon-inspector-lambda)
**Enfoque:** DevSecOps y Seguridad Serverless.
* **Seguridad Automatizada:** Implementación de un flujo de trabajo para identificar vulnerabilidades en funciones **AWS Lambda** de forma continua.
* **Remediación de CVEs:** Identificación y parcheo de la vulnerabilidad **CVE-2023-32681** en la biblioteca `requests` de Python, actualizando dependencias en `requirements.txt`.
* **Ciclo de Vida:** Uso de Amazon Inspector para transicionar hallazgos de estado `Active` a `Closed` mediante redeplegues seguros.

### 🗄️ [Despliegue e Interacción con Amazon RDS (MySQL)](./aws-rds-mysql-project)
**Enfoque:** Infraestructura de Datos y Conectividad Segura.
* **Aprovisionamiento:** Creación de una base de datos administrada **Amazon RDS** (MySQL) bajo el esquema de Capa Gratuita.
* **Arquitectura de Red:** Configuración de **Security Groups** para permitir tráfico específico (puerto 3306) entre una instancia EC2 (cliente) y el motor de base de datos.
* **Integridad Referencial:** Diseño de esquemas relacionales vinculando tablas de estudiantes y certificaciones mediante **Llaves Foráneas (Foreign Keys)** y consultas de unión (**Inner Join**).

### ⚙️ [Operaciones SQL en AWS EC2](./sql-operations-on-aws)
**Enfoque:** Administración de Bases de Datos y Lenguaje DDL/DML.
* **Gestión de Ciclo de Vida:** Configuración de un servidor MySQL sobre **Amazon EC2** utilizando **Systems Manager (Session Manager)** para acceso remoto seguro.
* **Definición de Esquemas:** Creación y modificación de estructuras de datos complejas (`CREATE`, `ALTER`) aplicando correcciones de integridad sin pérdida de datos.
* **Manipulación Técnica:** Uso avanzado de tipos de datos (ENUM, CHAR, FLOAT) y comandos de limpieza controlada (`DROP`) de recursos.

---

## 🎓 Competencias Fortalecidas
* **Principio de Menor Privilegio:** Restricción de accesos mediante políticas de red y firewall (Security Groups).
* **Enfoque DevSecOps:** Integración de herramientas de escaneo proactivo en el ciclo de vida del software.
* **Administración de Sistemas:** Uso de la CLI y Session Manager para operaciones remotas eficientes.
* **Arquitectura Well-Architected:** Aplicación de los pilares de Seguridad, Excelencia Operativa y Eficiencia de Desempeño.

---

**Autor:** Patricia Constanza Salas González  
*Egresada de AWS re/Start - Generation Chile & Bootcamp Institute*
