# NetResilience-ODS9 ??
## Infraestructura Digital Sostenible para el Sector Industrial de Xalapa

Este proyecto forma parte de la materia de Herramientas de Cómputo en la Nube. Su objetivo es diseñar una arquitectura de red monitoreada y resiliente que apoye al **ODS 9: Industria, Innovación e Infraestructura**.

---

## ?? Alineación con el ODS 9
Nuestra solución busca reducir la brecha digital en las zonas industriales de Xalapa, proporcionando una infraestructura de red que sea:
1. **Resiliente:** Capaz de recuperarse ante fallos de hardware.
2. **Sostenible:** Optimizada para bajo consumo energético.
3. **Innovadora:** Utilizando monitoreo automatizado y gobernanza de datos moderna.

## ?? Declaración de Etica del Repositorio
Para garantizar la integridad y el impacto social positivo, este repositorio se rige por los siguientes principios:

* **Privacidad de Datos:** El sistema de monitoreo solo recolecta métricas de rendimiento de hardware (uso de CPU, temperatura, estado de enlaces). **No se inspeccionan paquetes de datos de los usuarios** ni se almacenan direcciones IP privadas.
* **Inclusividad:** La documentación está diseñada para ser entendida por técnicos de distintos niveles, fomentando la transferencia de conocimiento.
* **Transparencia:** Todo el código de automatización es auditable y libre de "backdoors" o sesgos que prioricen el tráfico de ciertos sectores sobre otros.

---

## ??? Arquitectura de la Solución (Docs-as-Code)

\\\mermaid
graph TD
    subgraph Local_Infrastructure [Infraestructura Local - Xalapa]
        A[MikroTik Router/Switch] -->|Métricas SNMP| B(Agente de Monitoreo Local)
    end
    
    flowchart TD
    Ciudadano[Ciudadano]
    Operador[Operador municipal]
    Admin[Administrador técnico]
    Sistema[Sistema de Reporte de Infraestructura]
    BD[(Base de datos)]
    Panel[Panel de seguimiento]

    Ciudadano -->|Envía reporte| Sistema
    Operador -->|Consulta y actualiza incidencias| Sistema
    Admin -->|Configura y audita| Sistema
    Sistema --> BD
    Sistema --> Panel
\\\

---

## ??? Tecnologías Utilizadas
* **Versionamiento:** Git & GitHub con flujo de historial lineal.
* **Gobernanza:** GitHub Actions para validación de estándares éticos.
* **Documentación:** Mermaid.js para diagramas dinámicos.




