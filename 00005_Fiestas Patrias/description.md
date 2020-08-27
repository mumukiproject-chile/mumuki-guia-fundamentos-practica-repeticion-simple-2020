Muchas veces vamos a usar el tablero de Gobstones como memoria, es decir, para recordar algo importante que vamos a necesitar más adelante.

¿Qué podríamos representar con bolitas? Por ejemplo, una fecha. Una fecha que debemos recordar es el _18 de septiembre de 1810_, el Día de la Independencia de Chile, que hoy se conmemora como [Fiestas Patrias](https://es.wikipedia.org/wiki/Fiestas_Patrias_en_Chile).

> El objetivo, entonces, es definir un procedimiento `FiestasPatrias()`:

> * En la celda actual, pon 18 bolitas azules, que **representan** el día.
> * En la celda inmediatamente al este, pon 9 bolitas verdes, que **representan** el mes.
> * En la celda a continuación, pon 1810 bolitas negras, **representando** el año.

<gs-board> 
  GBB/1.0 
  size 3 1 
  cell 0 0 Azul 18 
  cell 1 0 Verde 9 
  cell 2 0 Negro 1810 
  head 2 0 
</gs-board>
