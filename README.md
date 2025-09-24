# Powershell-Ciberseguridad

Este repositorio contiene dos carpetas "Evidencia 9" y "Evidencia 10", donde vemos sobre los inicios de sesión y como separar a los usuarios que ya habían ingresado y no al sistema.

EVIDENCIA 9
La evidencia presentada contiene un reporte de usuarios del sistema, en el cual se identifican tanto las cuentas activas como aquellas que nunca han iniciado sesión. Para obtener esta información se desarrollaron scripts que permiten clasificar y separar a los usuarios en dos archivos: uno con las cuentas que sí registraron logon y otro con las que no lo hicieron. De esta manera, los scripts cumplen con la tarea de automatizar la revisión de cuentas, lo que resulta muy útil en ciberseguridad, ya que ayuda a detectar cuentas inactivas o predeterminadas que podrían representar una vulnerabilidad si permanecen habilitadas sin necesidad.

En términos prácticos, estos procesos resuelven tareas como el monitoreo de accesos, el control de cuentas no utilizadas y la verificación de la actividad de usuarios en el sistema, lo que permite tomar decisiones de seguridad más acertadas, como deshabilitar o eliminar cuentas innecesarias. Durante el desarrollo de estos scripts, el aprendizaje más relevante fue comprender cómo obtener y organizar información directamente desde el sistema de manera automatizada, y sobre todo, cómo interpretar esos resultados en un contexto de ciberseguridad. Esto refuerza la importancia de unir conocimientos técnicos con un análisis crítico que contribuya a la protección de los sistemas.

EVIDENCIA 10
En esta evidencia se desarrolló un script en PowerShell que permite validar la existencia de archivos dentro del sistema. El código incluye la función Validar-Archivo, la cual recibe una ruta como parámetro y comprueba si el archivo está disponible. En caso de encontrarlo, muestra un mensaje de confirmación, y si no existe, genera un error controlado. Además, el script siempre muestra una salida final de validación, lo que ayuda a dar retroalimentación clara sobre el proceso.

Se hicieron pruebas con un archivo inexistente y con otro ubicado en el Escritorio, lo que permitió comprobar el correcto funcionamiento en diferentes situaciones. También se incluyó la instrucción para que los resultados se guarden automáticamente en un reporte en formato .txt con la fecha actual en el nombre, lo que hace más fácil llevar un registro de las validaciones realizadas.

Este tipo de tareas se relacionan con la ciberseguridad porque ayudan a mantener un control sobre archivos importantes, evitando errores en procesos donde es fundamental que ciertos recursos estén disponibles. Además, son útiles para la automatización y para auditorías en las que se necesita confirmar la existencia y accesibilidad de archivos.

Al realizar este trabajo aprendí a crear funciones en PowerShell, a usar estructuras como try-catch-finally para manejar errores, y a generar reportes de manera automática. Esto me permitió reforzar conocimientos prácticos de scripting y comprender cómo estas herramientas se pueden aplicar en situaciones reales de ciberseguridad.
