Main
int numJugador
int intentos = 7
bool adivinado = FALSO
adivinado = VERDADERO
int numeroSecreto = Random(0,101)

while (intentos >0 && !adivinado)
lee numJugador
if(numJugador = numeroSecreto)
mostrar adivinado
adivinado = VERDADERO
mostrar "Has Ganado"
-- intentos
Sino
if(numJugador > numeroSecreto)
mostrar "Demasiado alto"
-- intentos
Sino if(numJugador > numSecreto)
mostrar "Demasiado bajo"
--intentos
finIf
finWhile
FinMain
