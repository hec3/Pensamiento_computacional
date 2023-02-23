que calcula el promedio y el etsatus (apobado o reprobado) de un alumno de alguno de los siguientes tres grupos
grupo1 español, matematicas y ciencias
grupo 2 :español, matematicas, ciencias
grupo 3: español, matematicas, ciencias, ingles y musica
//primero empezamos desfragmentando, 
>primero conocer en nombre del alumno
>conocer las calificaciones del alumno por cada materia
>el grupo
>sumar y dividir las calificacones 
>promedio
// para tipo de variable nombre es cadena (str)
validar que no haya posibilidades de herror en el codigo
(alicar comdicionales)
hay tres tipos de validacion o condicionales simple, compuesta y añadida
Algoritmo sin_titulo
	definir nombre_al Como Caracter
	definir español Como Real
	definir mate Como Real
	definir ciencias Como Real
	escribir "Ingrese el nombre del alumno"
	leer nombre_al
	escribir "Ingresa caificacion de español"
	leer español
	escribir "Ingresa calificacion de mate"
	leer mate
	escribir "ingresa calificacion de ciencias "
	leer ciencias
	promedio<-(español+mate+ciencias)/3
	//salida de datos
	Si promedio>=6 Entonces
		escribir " El alumno ",nombre_al " Esta aprobado con un promedio de ", promedio
	SiNo
		escribir "El alumno ", nombre_al, " esta reprobado con un promedio de ", promedio
	Fin Si
FinAlgoritmo 
