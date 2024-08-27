# Problemas 

Escribir el seudocódigo, verificar que es correcto, hallar tiempo de ejecución e implementar en Julia los algoritmos que solucionan los siguientes problemas:

1. Implemente un algoritmo de la Criba de Eratóstenes
2. Queremos ordenar una lista $S$ de $n$ elementos enteros que contiene muchos elementos duplicados. Supongamos que los elementos de $S$ sólo toman $O(lg(b))$ valores distintos. Encuentre un algoritmo que tome a lo más $O(n\ lg(lg(n)))$ tiempo para ordenar $S$.
3. Supongamos que tenemos dos listas ordenadas $S$ y $T$, cada una con $n$ elementos. Encuentre un algoritmo que en $O(lg(n))$ encuentre el $n$-ésimo elemento de $S \cup T$.
4. Dada una bolsa con $n$ tornillos de distintos tamaños y otra con sus $n$ tuercas. Tenemos que encontrar para cada tornillo su tuerca. En cada paso sólo puede comparar un tornillo y una tuerca y verificar si una tuerca corresponde al tornillo, o si el diámetro del tornillo es mayor o menor al diámetro de la tuerca ya que la diferencia en tamaño es tan pequeño que no puede compara los tornillos entre ellos y las tuercas entre ellas. Encuentre un algoritmo que resuelva el problema en $O(n^2)$ en el peor de los casos, pero que su tiempo esperado sea $O(n\ lg(n))$.
5. Dados $n$ números naturales entre $1$ y $n^2$, encuentre un algoritmo lineal que los ordene.