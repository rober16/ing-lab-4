# Trabajo Práctico N° 1: Sistemas de control de versiones.

[Repositorio con la resolucion de este trabajo](https://github.com/rober16/Lab-4)

**Conflicto con el merge**

* Cuando se quiere mergear la rama Clon con la rama Master se produce un conflicto 

![image1](https://github.com/rober16/ing-lab-4/blob/master/tp-1/imagenes/conflictoMerge.png)

* Cuando un PR tiene conflictos, es decir que algunos de los archivos que estamos modificando avanzaron en la rama base,  vemos que no lo podemos mergear, como en la siguiente imágen. 

![image2](https://github.com/rober16/ing-lab-4/blob/master/tp-1/imagenes/conflictoBranch.png)

* GitHub nos proporciona una herramienta para poder encontrar en que linea del codigo se produjo el conflicto

![image3](https://github.com/rober16/ing-lab-4/blob/master/tp-1/imagenes/codigo2.png)

![image4](https://github.com/rober16/ing-lab-4/blob/master/tp-1/imagenes/codigo.png)

* Después de resolver el conflicto el PR se podrá mergear al branch master. Luego que la revisión está completa, hacer merge del pull request.

![image5](https://github.com/rober16/ing-lab-4/blob/master/tp-1/imagenes/merge.png)

### Version LOCAL
Es la version que tenemos en nuestro equipo

### Version BASE
Es la base en donde donde mergean la version LOCAL y REMOTE

### Version REMOTE
Es el lugar donde se almacena nuestro código y en donde otros usuarios pueden realizar cambios
