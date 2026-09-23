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

## Historia real 
    ¿En que se parece al dibujo inicial?
     que habia unas ramas que se separaban y despues volvian al main
    ¿En que es diferente?
    fueron mas commits y cosas que no esperaba que pasaran
    ¿Que partes del historial no habian anticipado?
    que el orden de las acciones si influye mucho en como se va a desarrollar
    ¿que entienden ahora que no entendian antes del primer dibujo?
    que el orden de el flujo depende de como nosotros lo hagamos 
## Tag
    ¿Que ventaja tiene usar el nombre v1.0 para identificar este punto del historial en lugar de utilizar solamente el hash del commit?
    Que es mas practico y sencillo que el hash
## Reflexion Final
    ¿Que informacion almacena un commit?
    guarda los datos de el estado del archivo en el momento

    ¿Que direrencia existe entre un repositorio local y uno remoto?
    el local vive en mi computadora es donde trabajas  el remoto es una copia que sirve de punto para compartirlo

    ¿Que ocurrio uando modificaron archivos diferentes?
    si se pudieron guardar los cambios de buena manera ya que no se sobreponian con otros

    ¿Que ocurrio cuando modificaron la misma region de un archivo?
    git no pudo decidir cual era la version buena por lo que se produjo un error

    ¿Que diferencias existen entre commit y push?
    commit guarda los cambios localmente mientras push lo sube al repositorio remoto
 
    ¿Que funcion tuvo pull durante la practica?
    actualizar las versiones que se tenian de todas las personas

    ¿Por que un push puede ser rechazado aunque no haya un conflicto de contenido?
    porque evita que se sobreescriba sin que antes se integren cosas pasadas con un pull

    ¿Que representa una rama?
    es una linea independiente de desarrollo
 
    ¿Que indica HEAD?
    indica en que punto y en que rama se esta trabajando actualmente
  
    ¿Que hace merge?
    integra dos lineas distintas en una sola combinando los cambios de ambas
 
    ¿por que git pudo integrar algunos cambios automaticamente y otros no?
    porque cuando se modifica a la misma linea git no sabia cual era la version correcta

    ¿Que representan los marcadores ?, ============ y ?
    delimitan las versiones que estan en conflicto por cambios hechos
 
    ¿Que ventaja proporciona un tag?
    es una forma mas facil de identificar un punto especifico en el historial

    ¿Como cambio su interpretacion de los diagramas de historial depues de utilizar git log -graph -oneline -all?
    creia que era mas sencillo de lo que realmente es entendiendo que cada linea representa un camino de trabajo independiente
