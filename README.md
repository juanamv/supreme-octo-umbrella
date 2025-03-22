# Docker Database Examples - Ejemplos de Bases de Datos Docker

## ⚠️ ADVERTENCIA ⚠️

Estos archivos de configuración Docker son **EJEMPLOS BÁSICOS** que no deben utilizarse en entornos de producción. Están diseñados únicamente con fines educativos y de desarrollo.

### Limitaciones de seguridad:

- Contraseñas predeterminadas o débiles expuestas en archivos de configuración
- Configuraciones de seguridad mínimas
- Puertos expuestos públicamente
- Sin implementación de cifrado adecuado
- Sin configuración de respaldo automatizada
- Sin alta disponibilidad ni estrategias de recuperación ante desastres

### Bases de datos incluidas:

| Base de Datos | Tipo |
|---------------|------|
| MongoDB       | NoSQL Document |
| ArangoDB      | Multi-model |
| Cassandra     | Wide-column |
| MySQL         | Relational |
| DragonFly     | In-memory |
| Redis         | Key-value |
| ScyllaDB      | Wide-column |
| SurrealDB     | Multi-model |

## Para entornos de producción:

Antes de utilizar cualquiera de estos ejemplos en producción, consulta la documentación oficial de cada base de datos para implementar:

1. Gestión segura de credenciales
2. Control de acceso adecuado
3. Cifrado de datos
4. Estrategias de respaldo
5. Configuración de red segura
6. Limitación de recursos adecuada
