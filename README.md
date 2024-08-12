# calculadora_redes
PASOS:
1) Obtener los valores de los campos de entrada (distancia/freciencia)
2) Verificar si alguno de los campos está vacío
3) Convertir los valores de los campos a números flotantes
4) Calcular la Zona de Fresnel usando la fórmula 
5) Muestra el resultado

FORMULA:
let fresnel = 17.32 * Math.sqrt((d / 4) / f);
1) Primero, se divide la distancia (d) entre 4
2) Luego, se divide este resultado por la frecuencia 
3) Se calcula la raíz cuadrada del resultado usando Math.sqrt().
4) Finalmente, se multiplica por 17.32 para obtener el valor final de la Zona de Fresnel.