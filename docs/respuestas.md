# Respuestas de la práctica

## Preguntas de control

**¿Qué ventaja tiene registrar las dependencias en requirements.txt en lugar de compartir .venv?**  
Permite reconstruir el entorno de forma ligera y reproducible, sin compartir archivos específicos de una computadora.

**¿Por qué el repositorio de la computadora no es el mismo concepto que el fork creado en GitHub?**  
El fork es una copia remota vinculada al repositorio original; el clone es una copia local de trabajo en la computadora.

## Preguntas individuales

**79. ¿Cómo identificaste el comando necesario cuando la práctica no lo proporcionó?**  
Relacioné la acción solicitada con el comando de Git, Python o terminal correspondiente y comprobé el resultado.

**80. ¿Qué diferencia existe entre preparar un archivo para un commit y crear el commit?**  
Preparar coloca el archivo en staging; el commit registra permanentemente esa versión en el historial local.

**81. ¿Cómo puedes comprobar en qué rama estás trabajando?**  
Con `git branch --show-current` o `git status`.

**82. ¿Cómo puedes determinar qué archivos fueron modificados antes de registrarlos?**  
Con `git status`.

**83. ¿Cómo puedes observar exactamente qué cambió dentro de un archivo?**  
Con `git diff`.

**84. ¿Por qué debe reconstruirse .venv después de obtener un repositorio?**  
Porque no se versiona y puede contener rutas y archivos específicos de otra computadora.

**85. ¿Qué relación existe entre requirements.txt y .gitignore?**  
`requirements.txt` registra las dependencias y `.gitignore` excluye el entorno virtual que las contiene.

**86. ¿Por qué la colaboración se realiza desde una rama y no directamente desde main?**  
Para aislar el trabajo, revisarlo y evitar afectar la versión estable.

**87. ¿Por qué una solicitud de cambios no requiere crear un Pull Request nuevo?**  
Porque los nuevos commits enviados a la misma rama actualizan automáticamente el Pull Request existente.

**88. Después del merge en GitHub, ¿por qué todavía es necesario actualizar el repositorio local?**  
Porque el merge modifica el repositorio remoto y la copia local debe descargar esos cambios con `git pull`.
