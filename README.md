# Registro De Estudiantes
APLICACION QUE CONSISTE EN UN FORMULARIO DE REGISTRO DE ESTUDIANTES DEL ITLA. LOS DATOS SON LOS SIGUIENTES:
- MATRICULA
- NOMBRES
- APELLIDOS
- CARRERA
- DIRECCION
- TELEFONO
- EMAIL

LA APLICACION DEBE PERMITIRLE AL USUARIO INGRESAR LOS DATOS DE TANTOS
ESTUDIANTES COMO SE DESEE.
AL INSERTAR LOS DATOS DE ALGUIEN, LA APLICACION DEBE DARLE AL USUARIO LA
OPCION DE PERSISTIR LOS DATOS EN UNA DE TRES (3) OPCIONES:
1. UN ARCHIVO DE TEXTO PLANO
2. UN ARCHIVO DE EXCEL
3. UN ARCHIVO JSON

CADA MECANISMO DEBE IMPLEMENTAR SU PROPIA LOGICA Y PERSISTIR LOS DATOS.
APLICAR EL PATRON DE DISEÑO STRATEGY, PARA DESVINCULAR AL CODIGO
CLIENTE DE LOS DETALLES DE LAS IMPLEMENTACIONES DE PERSISTENCIA.

**IMPORTANTE:** TRATE DE MANTENER EL CODIGO CLIENTE LO MAS DESACOPLADO
POSIBLE, QUITANDOLE RESPONSABILIDADES QUE CONVIENE QUE NO TENGA.
NOTA: LOS ARCHIVOS CON LOS DATOS PERSISTIDOS (EL TXT, EL XLSX, EL JSON)
