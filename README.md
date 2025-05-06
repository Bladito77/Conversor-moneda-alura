# Conversor-moneda-alura
Repositoria conversor de moneda Challenge Alura 

Proyecto Challenge Alura 
Módulos 

Clase principal  : Conversor
Funciones : Estatica convertir la cual tiene por objeto hacer la conversion de monedas de dos parametros pasados en esta funcion , además llama la función obtenerTasa
          : Funcion obtenerTasa la cual hace la consulta a la API realizando de manera concatenada mediante un metodo GET y  la consulta a esta por un argumento llamado monedabase 
            y a tra vez de un manejo de exepción try /cath controla el retorno del resultado de la función que contulta a la api

Este retorno va a la funcion convertir como parametro y mediante un if evalua que el resultado tenga "result", "succes", "conversion_rates" y tambien que no sea null
            
