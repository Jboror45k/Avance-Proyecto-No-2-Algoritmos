Algoritmo RegistroNotas
Inicio
Imprimir " Avance de Proyecto 02"
Imprimir "Registro y visualización de notas, cálculo de promedio"

Imprimir  "Ingrese la cantidad de Notas: "
Leer cantidad
numeros como Lista
Para i <- 1 Hasta cantidad Hacer
Imprimir "Ingresa la Nota ", i, ": "
Leer num
Imprimir "Se ha Registrado la Nota"
Agregar num a numeros
Fin Para

Imprimir "Las Notas Registradas son: ", numeros

Imprimir "¿Deseas Calcular el Promedio? (si/no): "
Leer Indicacion

Para Indicacion = "si" Entonces hacer
Imprimir "Obteniendo Tu Promedio..."
prom <- (Suma(numeros)) / cantidad
Imprimir "El promedio de las notas es: ", prom
Sino
Si Indicacion = "no" Entonces
Imprimir "Sin Promedio disponible."
Sino
Imprimir "Por favor escribe 'si' o 'no'."
Fin Si
Fin Si

Imprimir "Final de Registro y visualización de notas, cálculo de promedio"

FinAlgoritmo


