# Analisis de los resultados del naufragio del Titanic.

Autor: Lucas Rafael Iribarne.


# Introduccion.

Siempre causa estupor y desconcierto cuando escuchamos o vemos noticias o peliculas relacionadas al naufragio del Titanic, acaecido en 1912. En este trabajo, tomaremos un dataset de Kaggle, en el cual analizaremos algunas variables a fin de dilucidar si fallecieron mas Hombres que Mujeres, o a la inversa. Ademas, intentaremos establecer si incidió en la tasa de supervivencia la clase de cada uno de los integrantes y/o tripulantes del colosal navio.



# Requisitos.

-Python 3
-Jupyter notebook
-Pandas
-Matplotlib

Instalación:

La forma más fácil de instalar todo junto es instalando anaconda. Podes seguir las intrucciones de la pagina oficial.

# Datasets.

Dataset "train" extraido de kaggle.com


# Contenido del Dataset.


El Dataset "train" contiene las siguientes variables:

PassengerId -> Muestra el id del Pasajero (solamente es un indicador) 
Survived -> Se encuentra en 2 valores 0 si murió en la tragedia y 1 si sobrevivió 
Pclass -> Determina la clase del pasajero, 1ra, 2da o 3era clase. 
Name -> Nombre de los Pasajeros 
Sex -> Sexo de los Pasajeros 
Age -> Edad de los Pasajeros 
SibSp -> Número de parientes como Hermano, Hermana, Hermanastra, Hermanastro, Esposo o Esposa 
Parch -> Número de parientes como Madre, Padre, Hijo, Hija, Hijastro, Hijastra 
Ticket -> Número del ticket o boleto 
Fare -> Tarifa del pasaje 
Cabin -> Número de cabina del pasajero 
Embarked -> Muestra los datos del puerto de embarcaquedero (C = Cherbourg, Q = Queenston, S = Southapmtpon)


# Limpieza de datos.

Procedimos a eliminar las columnas irrelevantes para nuestro analisis. A saber: 'Name', 'Ticket', 'SibSp', 'Parch' 'Fare', 'Embarked'.


# Conclusiones.

Luego de nuestros analisis podemos afirmar que fallecieron mas Hombres (468) que Mujeres (81). Salvaron su vida 203 Mujeres y 109 Hombres. La tasa de supervivencia es de 0,74 para Mujeres y de 0,18 para los Hombres. Se podría decir que tuvieron prioridad las Mujeres sobre los Hombres para acceder a los escasos botes que había a disposición de la gente. 
Ademas, en cuanto a la variable "Pclass", la mayor tasa de supervivencia es para 1° con 0,62. Mientras que 2° obtiene el 0,47 y 3° solamente el 0,24. Definitivamente, se salvó gente con mas recursos económicos que otra.


