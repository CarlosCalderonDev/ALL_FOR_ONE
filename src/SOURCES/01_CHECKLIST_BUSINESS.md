   # 📝 Checklist de Lógica de Negocio

   1. **Entidades**

      * ¿Qué objetos principales existen en este módulo?
      * ¿Son personas, cosas, eventos o información clave?
      * ¿Tienen identidad propia (se crean, se actualizan, se consultan, se eliminan)?

   2. **Reglas de negocio**

      * ¿Qué condiciones o restricciones deben cumplirse?
      * ¿Qué está prohibido o limitado (ej: no dos citas al mismo horario)?
      * ¿Qué validaciones son obligatorias?

   3. **Procesos de negocio**

      * ¿Qué flujos completos existen? (ej: *Agendar cita*, *Cancelar cita*).
      * ¿Qué pasos siguen para cumplir el objetivo?
      * ¿Cómo comienza y cómo termina cada proceso?

   4. **Acciones / Casos de uso**

      * ¿Qué operaciones específicas ejecuta un usuario o sistema?
      * ¿Qué pasos forman parte de los procesos?
      * Ejemplo: *crear cita, consultar citas, notificar cliente*.

   5. **Políticas y permisos**

      * ¿Quién puede hacer qué dentro del módulo?
      * ¿Qué roles existen?
      * ¿Hay condiciones adicionales según contexto (ej: un cliente solo puede ver sus citas)?

   ---

   ### ✅ Beneficios de usar este checklist

   * **Claridad**: Te asegura que no se te escape nada antes de programar.
   * **Orden**: Diferencia bien procesos, acciones y reglas.
   * **Escalabilidad**: Si mañana agregas una nueva función, sabes dónde encaja.
   * **Comunicación**: Facilita explicar la lógica a otros devs, jefes o clientes.
