# DBA-MySQL

Este proyecto refleja mi enfoque práctico en el **modelado, diseño y administración** de una base de datos orientada al sector de indumentaria, utilizando **MySQL** como motor principal.  

- El diseño parte desde cero, aplicando **normalización** y creando tablas específicas para artículos y facturación de clientes.  
- Se incluyen **llaves primarias y foráneas**, restricciones de unicidad y enumerados, con el objetivo de garantizar integridad y reglas de negocio claras.  
- Se desarrollan consultas de prueba para validar el modelo y facilitar la gestión posterior.  
- La administración se complementa con **procedimientos almacenados, triggers, índices, vistas y catálogos**, que permiten automatizar operaciones y optimizar el acceso a los datos.  
- Además, se implementa un **sistema de logs de usuario**, que registra inserciones, actualizaciones y eliminaciones, aportando trazabilidad y control sobre las operaciones realizadas.  

---

## Diagramas y vistas del proyecto

- **Diagrama Entidad-Relación**: `db_indumentaria`  
- **Vista general de tablas y estructura**  
- **Ejemplo de tabla de artículos**  
- **Listado de vistas (Views)**  
- **Procedimientos almacenados (Stored Procedures)**  
- **Triggers implementados**  
- **Registros de usuario (Logs de inserción y actualización)**  

*(Las imágenes de cada sección se encuentran en la carpeta `documentation`.)*

---

## Tecnologías utilizadas

| Herramienta | Versión | Uso principal |
|-------------|---------|---------------|
| Git Bash    | 2.29.1.windows.1 | Control de versiones |
| XAMPP       | 3.2.2 | Entorno de servidores |
| DBeaver     | 21.1  | Diseño y administración de BD |

---

## Documentación oficial de las herramientas
- [Git](https://git-scm.com/docs)  
- [XAMPP](https://www.apachefriends.org/download.html)  
- [DBeaver](https://dbeaver.io/)  

---

## Orden recomendado de ejecución de scripts

1. `db_indumentaria_DDL.sql`  
2. `db_indumentaria_DML.sql`  
3. `db_indumentaria_QUERIES_SELECT.sql` *(opcional)*  
4. `db_indumentaria_QUERIES_INSERT.sql`  
5. `db_indumentaria_QUERIES_UPDATE.sql`  
6. `db_indumentaria_INDEXES.sql`  
7. `db_indumentaria_VIEWS.sql`  
8. `db_indumentaria_PROCEDURES_INSERT.sql`  
9. `db_indumentaria_PROCEDURES_UPDATE.sql`  
10. `db_indumentaria_PROCEDURES_DELETE.sql`  
11. `db_indumentaria_CATALOGS.sql` *(opcional)*  
12. `db_indumentaria_TRIGGERS_INSERT.sql`  
13. `db_indumentaria_TRIGGERS_UPDATE.sql`  
14. `db_indumentaria_TRIGGERS_DELETE.sql`  
