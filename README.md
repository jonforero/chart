# Helm Charts para Aplicaciones Microservicio

Este repositorio contiene Helm charts para desplegar diferentes microservicios en Kubernetes utilizando Helm.

## Estructura del Directorio

- `zp-fco-id-audit/`: Chart para desplegar el microservicio de auditoría.
- `zp-fco-id-biometric/`: Chart para desplegar el microservicio biométrico.

### Archivos Importantes

- **Chart.yaml**: Define la información básica del chart, como nombre, versión y descripción.
- **values.yaml**: Contiene las configuraciones predeterminadas y opciones de personalización para los charts.
- **templates/**: Contiene las plantillas de Kubernetes YAML utilizadas para desplegar los recursos en el clúster.

## Instrucciones de Uso

### Instalación

1. Agrega el repositorio de Helm:
   ```bash
   helm repo add mi-repo http://ruta-a-tu-servidor-o-repositorio
   helm repo update
