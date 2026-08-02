# Fase 2 - Redes para SOC Analyst

## Descripción

Esta fase está enfocada en el aprendizaje de conceptos fundamentales de redes orientados al análisis de eventos de seguridad, monitoreo de infraestructura y respuesta ante incidentes.

El objetivo es desarrollar una comprensión sólida sobre cómo se comunican los dispositivos dentro de una red, cómo viajan los datos, cómo se direccionan los equipos y cómo interpretar información relacionada con conexiones, protocolos, puertos y servicios.

Estos conocimientos son esenciales para el trabajo diario de un analista SOC (Security Operations Center), ya que gran parte de los eventos de seguridad están relacionados con tráfico de red, autenticaciones, conexiones remotas, comunicaciones entre sistemas y actividad sospechosa en la infraestructura.

La fase combina teoría, práctica y análisis orientado a escenarios reales de seguridad, buscando desarrollar la capacidad de interpretar información de red y relacionarla con posibles eventos de seguridad.

---

# Objetivos

* Comprender los fundamentos de las redes informáticas.
* Identificar los principales dispositivos de red y su función.
* Comprender cómo se comunican los dispositivos dentro de una red.
* Comprender los modelos OSI y TCP/IP.
* Identificar dispositivos y direcciones IP.
* Diferenciar redes públicas y privadas.
* Comprender conceptos básicos de direccionamiento IPv4.
* Entender el funcionamiento de los principales protocolos de red.
* Comprender el concepto de puertos y servicios.
* Analizar conexiones de red.
* Interpretar información básica de tráfico de red.
* Interpretar registros relacionados con tráfico y conexiones.
* Utilizar herramientas básicas de análisis de red desde Linux.
* Identificar posibles indicadores de actividad sospechosa en una red.
* Detectar anomalías básicas relacionadas con conexiones, IPs y puertos.
* Preparar la base necesaria para trabajar posteriormente con Wazuh, Splunk y otras herramientas SIEM.

---

# Temas a estudiar

## Módulo 1 - Fundamentos de Redes

* ¿Qué es una red?
* ¿Para qué sirven las redes?
* Tipos de redes.
* LAN.
* WAN.
* WLAN.
* VPN.
* Dispositivos de red.
* Host.
* Cliente.
* Servidor.
* Switch.
* Router.
* Access Point.
* Firewall.
* Comunicación entre equipos.
* Comunicación cliente-servidor.
* Conceptos básicos de infraestructura de red.

---

## Módulo 2 - Modelos de Comunicación

### Modelo OSI

* ¿Qué es el modelo OSI?
* Capa Física.
* Capa de Enlace de Datos.
* Capa de Red.
* Capa de Transporte.
* Capa de Sesión.
* Capa de Presentación.
* Capa de Aplicación.
* Función de cada capa.
* Protocolos relacionados con cada capa.
* Encapsulación.
* Desencapsulación.

### Modelo TCP/IP

* ¿Qué es el modelo TCP/IP?
* Capa de Acceso a la Red.
* Capa de Internet.
* Capa de Transporte.
* Capa de Aplicación.
* Relación entre OSI y TCP/IP.
* Diferencias entre ambos modelos.
* Ubicación de protocolos dentro del modelo TCP/IP.

---

## Módulo 3 - Direccionamiento IP

* ¿Qué es una dirección IP?
* IPv4.
* Estructura de una dirección IPv4.
* Dirección de red.
* Dirección de host.
* IP pública.
* IP privada.
* Rangos de IP privadas.
* Máscara de red.
* Gateway.
* Dirección de broadcast.
* CIDR básico.
* Conceptos básicos de subredes.
* Identificación de dispositivos mediante direcciones IP.

---

## Módulo 4 - Protocolos de Red

* ¿Qué es un protocolo de red?
* TCP.
* UDP.
* ICMP.
* ARP.
* Diferencias entre TCP y UDP.
* Concepto de conexión.
* TCP 3-Way Handshake.
* SYN.
* SYN-ACK.
* ACK.
* Estados básicos de una conexión TCP.
* Comunicación orientada a conexión.
* Comunicación no orientada a conexión.

---

## Módulo 5 - Servicios y Puertos

* ¿Qué es un puerto?
* Puertos TCP.
* Puertos UDP.
* Puerto origen.
* Puerto destino.
* Puertos conocidos.
* Puertos registrados.
* Puertos dinámicos.
* Servicios de red.

### Principales servicios

* SSH.
* HTTP.
* HTTPS.
* DNS.
* FTP.
* SMTP.
* Otros servicios comunes.

### Análisis orientado a SOC

* Identificación de puertos utilizados.
* Relación entre puertos y servicios.
* Puertos comunes.
* Puertos inusuales.
* Identificación de posibles servicios expuestos.
* Conceptos básicos de servicios vulnerables.

---

## Módulo 6 - DNS y Resolución de Nombres

* ¿Qué es DNS?
* ¿Por qué es importante DNS?
* Funcionamiento de DNS.
* Resolución de nombres.
* Consultas DNS.
* Servidores DNS.
* Registros DNS.
* Registro A.
* Registro AAAA.
* Registro CNAME.
* Registro MX.
* Registro NS.
* Registro TXT.
* Resolución directa.
* Resolución inversa.
* DNS desde la perspectiva de un SOC.
* Identificación de dominios sospechosos.
* Conceptos básicos de actividad DNS anómala.

---

## Módulo 7 - Herramientas de Red en Linux

En este módulo se aprenderán herramientas de línea de comandos utilizadas para consultar, diagnosticar y analizar información relacionada con redes y conexiones.

### Herramientas

* `ip`
* `ss`
* `ping`
* `traceroute`
* `tracepath`
* `nslookup`
* `dig`
* `curl`
* `wget`
* `nc`
* `tcpdump`

### Objetivos prácticos

* Consultar información de interfaces de red.
* Identificar direcciones IP.
* Consultar rutas de red.
* Identificar conexiones activas.
* Identificar puertos en escucha.
* Comprobar conectividad.
* Analizar la resolución DNS.
* Consultar información de dominios.
* Realizar solicitudes HTTP.
* Comprender conexiones TCP y UDP.
* Capturar y analizar tráfico básico de red.

---

## Módulo 8 - Tráfico y Conexiones de Red

* ¿Qué es el tráfico de red?
* IP origen.
* IP destino.
* Puerto origen.
* Puerto destino.
* Protocolo.
* Conexiones entrantes.
* Conexiones salientes.
* Tráfico Inbound.
* Tráfico Outbound.
* Cliente y servidor.
* Conexiones activas.
* Puertos en escucha.
* Estados de conexiones.
* Flujo básico de comunicación.
* Interpretación de información de tráfico.

### Análisis práctico

* Identificación de IP origen y destino.
* Identificación de puertos.
* Identificación de protocolos.
* Análisis básico de conexiones.
* Identificación de patrones de comunicación.
* Detección de conexiones repetitivas.

---

## Módulo 9 - Análisis de Red para SOC

Este módulo está enfocado en aplicar los conocimientos adquiridos para analizar eventos relacionados con redes desde la perspectiva de un analista SOC.

### Temas

* Identificación de IPs sospechosas.
* IP origen vs. IP destino.
* Interpretación de logs de red.
* Análisis de conexiones.
* Identificación de puertos utilizados.
* Identificación de servicios.
* Análisis de tráfico entrante.
* Análisis de tráfico saliente.
* Detección de conexiones repetitivas.
* Detección básica de escaneo de puertos.
* Identificación de puertos inusuales.
* Identificación de posibles indicadores de compromiso.
* Identificación de dominios sospechosos.
* Detección básica de anomalías.
* Análisis inicial de posibles eventos de seguridad.

### Indicadores de interés para un SOC

* IPs sospechosas.
* Dominios sospechosos.
* Puertos inusuales.
* Conexiones repetitivas.
* Intentos de conexión fallidos.
* Escaneo de puertos.
* Comunicaciones inesperadas.
* Tráfico anómalo.
* Conexiones hacia destinos desconocidos.

---

# Metodología

Cada módulo incluirá:

### 📚 Teoría

Explicación de los conceptos fundamentales necesarios para comprender el tema.

### 🧪 Laboratorio práctico

Ejercicios prácticos para aplicar los conocimientos adquiridos.

### 🎯 Misiones

Retos diseñados para resolver problemas utilizando los conceptos y herramientas aprendidas.

### 🕵️ Casos de uso orientados a SOC

Escenarios simulados relacionados con monitoreo, análisis de eventos y detección de posibles actividades sospechosas.

### 🛠️ Herramientas

Uso de herramientas de Linux y utilidades relacionadas con el análisis de redes.

### 📂 Documentación

Cada módulo será documentado en GitHub con explicaciones, comandos utilizados, resultados y conclusiones.

---

# Objetivo Final

Al finalizar esta fase se busca ser capaz de:

* Comprender cómo funcionan las redes informáticas.
* Comprender cómo se comunican los dispositivos.
* Identificar direcciones IP, puertos y protocolos.
* Comprender el funcionamiento básico de los principales servicios de red.
* Analizar conexiones de red.
* Utilizar herramientas básicas de red desde Linux.
* Interpretar información básica de tráfico de red.
* Analizar registros relacionados con conexiones y tráfico.
* Identificar posibles IPs, puertos y dominios sospechosos.
* Detectar anomalías básicas relacionadas con actividad de red.
* Relacionar eventos de red con posibles incidentes de seguridad.
* Estar preparado para comenzar el análisis de eventos en herramientas SIEM.

---

# Laboratorio Final

El laboratorio final integrará los conocimientos adquiridos durante toda la fase mediante un escenario práctico orientado a SOC.

El escenario podrá incluir información como:

* Logs de conexiones.
* Logs DNS.
* Logs de firewall.
* Logs HTTP.
* Información de tráfico de red.
* Direcciones IP.
* Puertos.
* Protocolos.
* Dominios.

El objetivo será investigar y analizar la información disponible para responder preguntas como:

* ¿Qué IP genera más conexiones?
* ¿Qué IP presenta comportamiento sospechoso?
* ¿Qué puertos están siendo utilizados?
* ¿Existen conexiones inusuales?
* ¿Se observa un posible escaneo de puertos?
* ¿Existen dominios sospechosos?
* ¿Qué conexiones deberían investigarse?
* ¿Qué indicadores podrían considerarse relevantes?
* ¿Cuál sería la conclusión del análisis?
* ¿Qué acciones recomendaría un analista SOC?

El laboratorio deberá ser resuelto utilizando los conocimientos adquiridos durante la fase y deberá incluir una documentación final con los hallazgos encontrados.

---

# Resultado Esperado

Al finalizar la Fase 2, el estudiante deberá contar con una base sólida en redes orientada al análisis de seguridad y estar preparado para avanzar hacia el análisis de logs, herramientas SIEM y monitoreo de eventos de seguridad.

La combinación de los conocimientos adquiridos en:

* Linux.
* Redes.
* Análisis de logs.
* Herramientas de línea de comandos.

permitirá avanzar progresivamente hacia escenarios más cercanos al trabajo real de un analista SOC.

---

# Estado

🚧 En progreso

## Fase anterior completada

✅ Fase 1 - Linux para SOC Analyst

## Fase actual

🚧 Fase 2 - Redes para SOC Analyst

