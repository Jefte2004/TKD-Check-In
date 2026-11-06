\# TKD Check-In



Sistema inteligente para la gestión de torneos de Taekwondo, registro de competidores y pesaje automatizado.



\## Descripción



TKD Check-In es una plataforma que busca automatizar el proceso de registro y pesaje de competidores mediante la integración de hardware IoT, una base de datos, un motor de inferencia lógica y una interfaz web.



\## Objetivos



\- Registrar competidores.

\- Gestionar academias y profesores.

\- Crear y administrar salas de torneo.

\- Automatizar la captura del peso.

\- Validar categorías mediante Prolog.

\- Registrar el historial de pesajes.

\- Mostrar resultados en tiempo real.



\## Roles del sistema



\### Organizador

Administra los torneos, crea salas, registra academias y habilita a los profesores.



\### Profesor

Gestiona los competidores de su academia, realiza registros y opera el proceso de pesaje desde una sala habilitada.



\### Competidor

Participa en el torneo y proporciona sus datos mediante el profesor de su academia.



\## Arquitectura propuesta



ESP32 + HX711 → API → Base de datos → Prolog → Dashboard.



\## Tecnologías propuestas



\- ESP32

\- HX711

\- Celda de carga

\- WiFi

\- Base de datos SQL

\- Prolog

\- Dashboard web



\## Estado del proyecto



Etapa actual: análisis y diseño inicial.

