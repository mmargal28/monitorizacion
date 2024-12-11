# Herramientas propias del sistema

Las herramientas propias del sistema son aquellas que están integradas en el sistema operativo o que son proporcionadas directamente por el proveedor de la infraestructura. Estas herramientas permiten a los administradores y técnicos realizar tareas básicas de monitorización, como el control de recursos, el análisis de procesos o el diagnóstico de fallos.

#### Ejemplos de herramientas propias:
1. **Ps (Process Status)**:
   - El comando `ps` permite visualizar información sobre los procesos que se están ejecutando en el sistema, lo que es crucial para el monitoreo de la carga de trabajo y la gestión de recursos.
   - Un ejemplo básico de uso de `ps` sería:
     ```bash
     ps a
     ```
     Este comando muestra todos los procesos de los usuarios, no solo los de la sesión actual.
     ```bash
     ps aux
     ```
     Este comando muestra todos los procesos activos en el sistema con información detallada como el ID del proceso (PID), el usuario que ejecuta el proceso, el uso de CPU y memoria, y el tiempo de ejecución.
2. **Top / Htop**:
   - `top` es una herramienta de monitoreo que muestra el uso de los recursos del sistema en tiempo real, como la CPU, la memoria y la carga de trabajo de los procesos.
   - `htop` es una versión más avanzada de `top`, con una interfaz más amigable y la posibilidad de interactuar de manera más dinámica.

3. **Netstat**:
   - `netstat` se utiliza para ver las conexiones de red activas y las estadísticas de red, ayudando a identificar posibles problemas de conectividad.

4. **Syslog**:
   - Herramienta para el registro y monitoreo de eventos del sistema. `syslog` permite capturar mensajes generados por el sistema operativo o aplicaciones.

#### Beneficios:
- Son herramientas ligeras y fáciles de configurar.
- Están preinstaladas en la mayoría de los sistemas operativos.
- Son útiles para obtener información rápida y básica.

#### Limitaciones:
- Algunas herramientas son limitadas en cuanto a funcionalidades avanzadas.
- Generalmente no cuentan con interfaces gráficas de usuario (GUI) y requieren conocimiento de comandos.
