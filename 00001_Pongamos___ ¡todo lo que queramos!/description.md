Ahora que tenemos una idea de _reutilización_, y practicamos _repetición_, vamos a crear un procedimiento **que nos va a servir de ahora en adelante**.

La idea es definir un procedimiento que nos ayude a poner muchas bolitas. Sí, podríamos simplemente usar un `repeat` para lograrlo, pero como es una tarea súper común que vamos a hacer un montón de veces, vamos a preferir definir un `procedure` que se encargue de ello.

> Tu tarea es definir un procedimiento `PonerN(cantidad, color)` que reciba un número y un color, y ponga la cantidad de bolitas del color dado.

Por ejemplo, `PonerN(3, Azul)` haría esto:

<gs-board>   
  GBB/1.0 
  size 2 2
  cell 0 0 Azul 3 
  head 0 0 
<gs-board>