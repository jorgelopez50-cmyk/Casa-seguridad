# Casa-seguridad
## Evidencias de Ejecución

| Comando Probado | Captura de Pantalla (Evidencia) |
| :--- | :--- |
| **ipconfig /all** | ![Evidencia de Filtro por Categoría]()![alt text](<Captura de pantalla 2026-05-25 175544-1.jpg>) |
| **netstat -ano** | ![Evidencia de Filtro por Jugadores]()![alt text](<Captura de pantalla 2026-05-25 175832-1.png>) |
| **arp -a** | ![Evidencia de Combos por Presupuesto]()![alt text](<Captura de pantalla 2026-05-25 175938-1.png>) |

## Análisis del Diagnóstico de Red

A partir de los comandos ejecutados, se presenta el siguiente análisis breve:

* **¿Cuántos dispositivos detecté?**
  * 8 dispositivos en total.

* **¿Detecté conexiones sospechosas?**
  * No, no se detectaron conexiones riesgosas.

* **Nivel de riesgo general:** `Bajo` / `Medio` / `Alto`
  * Bajo, No se encontraron conexiones salientes sospechosas ni puertos críticos (como el 3389) expuestos al exterior. El tráfico detectado en `netstat` se limita a conexiones web cifradas estándar y a servicios nativos de Windows operando normalmente dentro de la red local.

## Recomendaciones de Mejora en Seguridad

1. **Cambiar la contraseña por defecto:** Asegurar que el módem/router no tenga la contraseña de fábrica.
2. **Actualizar el Firmware:** Mantener el router de la casa actualizado para corregir fallos de seguridad.
3. **Red de invitados:** Crear una red WiFi separada para dispositivos desconocidos o visitas.

## Reflexión Final
**Si mi casa fuera una microempresa, ¿qué tan vulnerable estaría actualmente?**
* Mi casa por lo que analice es bastante segura, solo que si fuera una micro empresa si le implementaria protocolos de seguridad para protejer mis datos y los de mi negocio, siento que si es vulnerable.