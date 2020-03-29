# Parte3-post_work
Aplicar los conceptos de la sesión a tu proyecto personal. Automatizar las tareas que sean factibles Contar con una estructura de carpetas para tu proyecto Contar con un conjunto de datos

##Las comas han sido  omitidas 
## Se busca el directorio en el que estamos trabajando 
>>pwd

##Nos encontramos en la misma carpeta, solo usaremos ls, para confirmar que datos tenemos o que carpetas tenemos
>> ls

## Entremos a la carpeta Mi_Proyecto
>>cd Mi_Proyecto

##Volvemos a usar ls para saber que carpetas tenemos
>>ls

##Tenemos dos carpeta, la vista en clase y la de nuestro proyecto de criminalidad
#NOTA*  se quizo usar curl para extraer este archivo de índice delictivo https://drive.google.com/file/d/19EWWRrPQUpOIPP5CQCbAe2MxF-yeF4yD/view, sin embargo no funciono, y se extrajo de manera normal, en el postwork anterior, se menciona como.
>> cd Municipal-Delitos-2015-2020_ene2020

##Observamos la inforación en alguna de las carpeta que sean csv
>>head Criminalidad-2015-2020.csv

##Se realiza cat, el cat sirve para ver la información del contenido, no fue recomendable hacerlo, porque tiene mucha información
>>cat Criminalidad-2015-2020.csv

##Antes de usar el cat es recomencable, usar el wc, para contar las observaciones, si son mucha no hacer cat
>>wc Crimininalidad-2015-2020.csv
