# Problemas

Escribir el seudocódigo, verificar que es correcto, hallar tiempo de ejecución e implementar en Julia los algoritmos que solucionan los siguientes problemas:

1. Implemente el algoritmo de división
2. Sea un natural $n$, usando sólo comparaciones, halle un algoritmo que en $lg(n)$ encuentre a n.
3. Dados dos conjuntos $A$ y $B$ de n números, y un número $x$, diseñe un algoritmo que en $O(n\ lg(n))$ encuentre, si existe, un elemento en $a$ en $A$] y otro $b$ en $B$ tales que $a+b=x$
4. Supongamos que tenemos una lista $A$ con $n$ elementos, y que cada elemento en lista es *verde, rojo o azul*. Encuentre un algoritmo lineal que solucione el problema de ordenar los elementos en nuestra lista de tal forma que aparezcan los elementos *verdes*, después los *rojos* y al final los *azules*. Las operaciones que tenemos disponibles son:
  
- *Color(A,i)*: nos da el color del elemento *i* en la lista A.
- *Intercambio(A,i,j)*: Intercambia el elemento *i* de A con el elemento *j*

5. Dada una lista de *n* enteros $\{x_1, x_2,...,x_n\}$ y un número *y*, encuentre un algoritmo que en $O(n\ lg(n))$ encuentre la pareja $(i,j)$ tal que $x_i+x_j \leq y$ y ademas sea máxima 