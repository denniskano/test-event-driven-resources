# PEVE Event Driven Resources

Este repositorio contiene los recursos de infraestructura para el proyecto PEVE (Event Driven Architecture) usando Confluent Cloud Flink.

## 📁 Estructura del Proyecto

```
peve-event-driven-resources/
├── README.md
└── PEVE/
    ├── ccloud-connectors/           # Configuración de conectores
    │   └── ccloud-sql-db-sink-connector-01/
    ├── ccloud-flink-compute-pool/  # Configuración de compute pools
    │   └── dev-vars.yaml
    └── ccloud-flink-statements/    # Statements DDL y DML
        ├── ddl/                    # Data Definition Language
        └── dml/                    # Data Manipulation Language
```

## 🚀 Uso

Este repositorio se utiliza junto con el repositorio principal de Terraform para desplegar:

- **Compute Pools**: Recursos de computación para ejecutar Flink
- **Flink Statements**: Consultas SQL DDL y DML
- **Connectors**: Conectores para integración con bases de datos

## 🔗 Repositorio Principal

Los workflows de GitHub Actions y la configuración de Terraform se encuentran en:
`wp-cp-flink-tf-gh`

## 📋 Archivos de Configuración

- `dev-vars.yaml`: Variables de desarrollo para compute pools
- `*.yaml`: Archivos de configuración de statements DDL/DML
- `*.json`: Configuración de conectores

## 🛠️ Desarrollo

Para modificar la configuración:

1. Edita los archivos YAML correspondientes
2. Los cambios se reflejarán automáticamente en los workflows de GitHub Actions
3. Los workflows desplegarán los cambios en Confluent Cloud

## 📞 Soporte

Para dudas sobre la configuración, contactar al equipo de desarrollo.
