#ingeniería #sistemas 
[Indice](Algebra%20y%20geometría%20Analítica)
Proposición: es aquella Oración declarativa que puede ser calificada como verdadera
==( **V(p)=1** o **V(p)=Verdadero** )== o falsa ==( **V(p)=0** o **V(p)=Falso** )==

# Conectivos lógicos y Proposiciones compuestas

Nos permite construir razonamientos complejos
  _Negación_ (-p): Invierte el valor de verdad
  _Conjunción_ ($p\land q$): verdadero si ambas proposiciones son V
  _Disyunción_($p\lor q$): Falsa si ambas proposiciones son F
  _Implicacion_ ($p\implies q$) : Falso si $V\implies F$
  _Doble Implicacion_ ($p\iff q$): V si $V\iff V$
Tautología: Es una proposición compuesta que es siempre verdadera a pesar de sus elementos
Contradicción: Es la opuesta a la tautología, su valor es siempre falso
Leyes de Morgan
  $¬(p\land q ) \iff (¬p \lor ¬q)$
  $¬(p\lor q) \iff (¬p\land ¬q)$

Tambien tenemos las cuantificaciones Universales de una Preposicion $\exists$ y $\forall$  
Cuantificador Universal ($\forall$): "Para todo x se cumple . . ."
Cuantificador Existencial($\exists$): "Existe al menos un x que cumple . . . "

# Teoría de Conjuntos

Definición: Un conjunto y un elemento son términos primitivos. La relación fundamental es la pertenencia ($\in$)
Se pueden definir de dos maneras
  Por Extensión: nombramos a cada Elemento dentro del conjunto $A= ({1,2,3})$
  Por Comprensión: Todos los elementos que cumplan una preposición $A={x/P(x)}$ 
  donde P(x) es cualquier proposición que defina el ejercicio 

**Operaciones Entre Conjuntos**
Inclusión ($A\subset B$): todo elemento de A es tambien elemento de B
Igualdad ($A=B$): se da si y solo si $A\subset B \land B\subset A$
Complemento (A'): elemento/s que no pertenecen a A : { x$\in\mathbb{E}$ / x$\notin$A }
Unión ($A\cup B$): todos los elementos de ambos conjuntos: {$x/x\in A \lor x\in B$ } 
Intersección ($A \cap B$): todos los elementos entre ambos conjuntos : {$x/x\in A \land x\in B$ }
Diferencia ($A-B$): los elementos presentes en uno y no en otro {$x\in A/x\notin B$ }

Conjunto de Partes (p(A)): conjunto de todos los subconjuntos de A. si a tiene n elementos, p(A) tiene $2^n$ 
Partición de un Conjunto: Un sistema de Subconjuntos P es partición de A si cumple tres axiomas
  |- No Vaciedad: no existe ningun conjunto vacio ($\emptyset \notin P$)
  |- Disjunción: la intersección entre dos conjuntos es nula ($A\cap B = \emptyset$)
  |- Unión Total: la unión de todos los subconjuntos da p(A)  ($p(A)= A_1 \cup A_2 \cup ... \cup A_n$)

# Producto Cartesiano

Par ordenado (a,b): es el conjunto donde el orden de los elementos importa $(a,b) = (c,d) \iff a=c \land b=d$ 
Producto Cartesiano: ($A\times B$): Conjunto de todos los pares ordenados donde la primer componente es del Conjunto A y la segunda del conjunto B
   |- El producto no es conmutativo ($A\times B \ne B\times A$ ), excepto que uno de los conjuntos sea vacio o ambos sean iguales
