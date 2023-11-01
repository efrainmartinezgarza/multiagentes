# M1T1. Actividad Sistemas Multiagente
### Modelación de sistemas multiagentes con gráficas computacionales (Gpo 303)

**“Piedra, papel o tijeras”** es un juego muy antiguo que es comúnmente usado para tomar pequeñas decisiones entre grupos de personas, esto de una forma divertida y dinámica. A pesar de que su origen es incierto, muchos afirman que la primera mención a este juego fue en un libro de origen chino conocido como Wazuzu (1600 a.C.), y que a partir de ahí ha ido evolucionando de cultura en cultura recibiendo nombres como Jankenpon, Cham-chaum, etc.

A pesar de que existen muchas variaciones, el modo de juego más popular es aquel donde las tijeras vencen al papel, el papel a la piedra, y la piedra a las tijeras.

Cada año el país de México lleva a cabo un torneo de “piedra, papel o tijera” donde durante 50 rondas, 10 mil participantes compiten por no ser eliminados. 

En esta competencia, cada participante tiene a su alrededor 8 personas con las cuales deberá de jugar (estas se encuentran adyacentes en formato horizontal, vertical y diagonal). Los enfrentamientos se van haciendo en conjuntos de dos personas. 

Existen dos tipos de jugadores, **“activos” y “eliminados”**. 
- Sólo aquellos que son del mismo tipo pueden jugar entre sí. 
- En un inicio todos comienzan el torneo en estado “activo”.

**Las reglas del torneo son las siguientes:**

- Cuando dos jugadores “eliminados” empatan regresan al estado “activo”. El empate se considera cuando ambos utilizan el mismo objeto durante el enfrentamiento.
- Cuando un jugador pierde su partida pasa automáticamente al estado “eliminado.

**Un participante puede perder su partida si hace lo siguiente:**

- Utiliza piedra contra alguien que usó papel.
- Utiliza tijera contra alguien que usa piedra.
- Utiliza papel contra alguien que usa tijera.

**Por otro lado, un participante puede ganar su partida si hace lo siguiente:**

- Utiliza piedra contra alguien que usó tijera.
- Utiliza tijera contra alguien que usa papel.
- Utiliza papel contra alguien que usa piedra.

Cada vez que se cambia de contrincante el jugador se ve obligado a reformular su jugada.
Al finalizar el torneo se premian a todos los participantes que se encuentran en estado “activo”.

