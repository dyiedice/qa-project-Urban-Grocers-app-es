# Requerimientos para ejecutar las pruebas de kit_name_kit_test  
- Antes de ejecutar actualizar el server y su link de configuration.py
- Necesitas tener instalados los paquetes pytest y request para ejecutar las pruebas.
- Ejecuta todas las pruebas con el comando pytest.
# Resultados esperados de las Pruebas 
## Prueba Postivas
-  1 Caracter- fallo, error 400
-  511 Caracteres- fallo, error 400
-  Caracteres especiales- fallo, error 400
-  Caracter espacio- Aprobado
-  Numeros- fallo, error 400
## Pruebas Negativas
- Menos caracteres de lo permitido- Aprobado
- Mas caracteres de lo permitido- Aprobado
- Parametro incorrecto- Aprobado
- Tipo de dato erroneo- Aprobado

## Total de pruebas pasadas
### 5 de 9
