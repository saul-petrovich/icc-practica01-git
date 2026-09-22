# icc-practica01-git
<<<<<<< HEAD
Tarea de Rafael Sandoval Castillo y Petrovich Tovar Diego Saúl
# Preguntas Iniciales
## ¿Que informacion almacena un commit?
    Bytes
## ¿Que diferencia existe entre un repositorio local y uno remoto?
    El local es más ráoido y el remoto es más eficiente pero lento
## ¿Que esperan que ocurra cuando ambos integrantes modifican archivos distintos?
    Cada quien tendria una version diferente del archivo
## ¿Que esprean que ocurra cuando ambos modifican la misma linea?
    Se guarda la ultima actualizacion 
# Comandos Utilizados
    git add
    git commit
    git push
    git pull
    git status
# Planeación
    A y B se repartirán equitativamente los commits según requiera el trabajo, estando al tanto de los cambios que realize cada uno
    Cada que haya un cambio aprobado por A y B, se ralizará un push
    Pull se llevará a cabo para actualizar los repositorias locales de A y B y asi mantener los documentos actualizados

# Historial esperado'
A---B---C <-----main
    \
     D---E <---- binario	
# Reto 08
    ## ¿Por qué git rechazó el primer push de B?
    Porque los repositorios locales de cada uno no estaban sincronizados
    ##¿Existia un conflicto de contenido?
    No
    ##¿Qué ocurrio cuando ejecutaron pull?
    Se actualizaron los repositorios locales y se sincronizaron
    ##¿Que diferencia observan entre un push rechazado y un conflicto?
    Hay que ver la raiz del problema para poder resolverlo
## Pregunta
	##¿Realizar un merge implica necesariamente que exista un conflicto?
	No, si se hace de manera efectiva y con orden no debe haber conflicto
	
	Discutiendo la afrimacion creemos que es cierto debido a que merge busca unificar las ramas porqur todas son importantes
# Comflicto
## ¿Que representa HEAD en este momento?
    DEsde donde se está trabajando
## ¿Que representa el contenido entre y =========?
    la version de B
## ¿Que representa el conflicto entre ======== y ?
   La versiona de A
## ¿Por que git no pudo decidir automaticamente que contenido conservar?
    Porque se cambio la misma region del archivo y git no sabe cual es la version importante 
