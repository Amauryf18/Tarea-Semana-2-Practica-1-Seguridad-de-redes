# Tarea-Semana-2-Practica-1-Seguridad-de-redes
FortiGate: Implementación y configuración de políticas de firewall, reglas de acceso, perfiles de seguridad, NAT y segmentación de red mediante VLAN.

## 🎬 Video demostrativo

[Ver video demostrativo](COLOCAR_ENLACE_DEL_VIDEO)

## Propósito del laboratorio

Implementar una infraestructura de red segmentada mediante VLAN,
utilizando FortiGate como firewall principal para administrar el
acceso entre usuarios, un servidor WEB y un servidor MySQL.

El laboratorio incluye enrutamiento, DHCP, NAT, políticas de
seguridad, inspección del tráfico y limitación de ancho de banda.

## Topología

![Topología del laboratorio](diagramas/topologia.png)

## Direccionamiento

| VLAN | Red | Gateway | Descripción |
|---|---|---|---|
| 10 | 192.168.10.0/25 | 192.168.10.1 | Usuarios |
| 20 | 192.168.20.0/28 | 192.168.20.1 | Servidor BD |
| 30 | 192.168.30.0/28 | 192.168.30.1 | Servidor WEB |

## Tecnologías utilizadas

- GNS3 y VMware
- FortiGate
- Cisco IOSvL2
- Ubuntu Server
- Apache y HTTPS
- MySQL

## Documentación

[📄 Documentación](documentacion.md)

## Evidencias

[Capturas de configuración](imagenes/)

## Scripts

[Scripts utilizados](scripts/)

## Running-Configs

[Configuraciones de los dispositivos](running-configs/)
