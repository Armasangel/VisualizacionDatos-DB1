# Canal Digital y E-commerce — RetailMax
## CC3088 Bases de Datos 1 | Universidad del Valle de Guatemala | Ciclo 1, 2026

Dashboard analítico del área de Canal Digital y E-commerce de RetailMax,
construido con Metabase sobre Docker.

## Integrantes
- Angel Armas 
- Wilson Peña

## Video de presentación
[Ver video en YouTube](https://youtu.be/BqMJHPxQJNQs)

## Área de negocio
Canal Digital y E-commerce — Área encargada de gestionar y evaluar el
desempeño del canal de ventas en línea de la empresa, analizando su
comportamiento frente al canal físico y su impacto en los resultados
globales del negocio.

## Estructura del dashboard
| Tab | Nombre | Enfoque |
|-----|--------|---------|
| 1 | Rendimiento del Canal Online | Volumen de ventas, pedidos y evolución temporal |
| 2 | Rentabilidad y Clientes | Márgenes, devoluciones, pagos y segmentos de clientes |

## Cómo levantar el ambiente

### Requisitos
- Docker
- Docker Compose

### Pasos
1. Clonar el repositorio:
   git clone <url-del-repo>
   cd <nombre-del-repo>

2. Levantar el ambiente:
   docker compose up

3. Abrir Metabase en el navegador:
   http://localhost:3000

4. Iniciar sesión con las credenciales de calificación:
   - Correo: calificar@uvg.edu.gt
   - Contraseña: secret123+

El dashboard "Canal Digital y E-commerce — RetailMax" aparece
automáticamente al iniciar sesión.

## Estructura del repositorio
lab7/
├── docker-compose.yml       # Ambiente Docker con PostgreSQL y Metabase
├── DDL.sql                  # Esquema de la base de datos
├── DATA.sql                 # Datos de prueba
├── metabase-data/           # Volumen persistido con el dashboard construido
├── informe.pdf              # Documentación de los 12 indicadores
└── README.md                # Este archivo