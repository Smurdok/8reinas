8reinas
=======

PRograma de las 8 reinas en c

<PRINCIPIO ensayar> (i: entero)

inicializar el conjunto de posiciones de la reina i-ésima

+-REPETIR hacer la selección siguiente

| +-SI segura ENTONCES

| | poner reina

| | +-SI i < 8 ENTONCES

| | | LLAMAR ensayar (i + 1)

| | | +-SI no acertado ENTONCES

| | | | quitar reina

| | | +-FINSI

| | +-FINSI

| +-FINSI

+-HASTA acertada O no hay más posiciones

<FIN>


