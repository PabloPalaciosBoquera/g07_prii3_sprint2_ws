# Sprint 2 — Grupo 07

Código de la versión presentada y probada por el equipo en simulación y con el robot real.

- `src/g07_prii3_move_jetbot`: control del JetBot.
- `src/g07_prii3_move_turtlebot`: control del TurtleBot3 simulado.

Cada paquete incluye los ejecutables `draw_number` y `collision_avoidance`, sus launch y configuración ROS 2. Ejecutar solo un controlador de movimiento a la vez. El controlador de colisiones del JetBot comienza pausado.

Servicios: `/detener_dibujo`, `/reanudar_dibujo` y `/reiniciar_dibujo` (`std_srvs/srv/Trigger`).

Se conserva el código entregado sin cambios. Los PDF no forman parte de este repositorio.

El Sprint 1 se mantiene por separado en [g07_prii3_ws](https://github.com/PabloPalaciosBoquera/g07_prii3_ws).
