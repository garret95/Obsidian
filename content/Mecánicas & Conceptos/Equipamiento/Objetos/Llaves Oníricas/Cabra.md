![[5. Cabra Onírica.jpg|cover hmed]]
# 5. Llave Onírica: Cabra

Una de las llaves oníricas de [[Boros]].
Como acción, puedes invocar al familiar que duerme en el interior de la llave. Tras ser usada, entra en letargo hasta tu próximo nivel (o tras un mes a partir del nivel 20). Todos los familiares poseen la capacidad de comprender las órdenes de su invocador sin problemas, los cuales además pueden comunicarse telepáticamente con ellos. Todos los familiares poseen visión en la oscuridad de hasta 60 pies y sus Puntos de Golpe son iguales a 1+ su mod. de Constitución por cada nivel de su invocador (mínimo 1). El familiar permanece invocado hasta que sus puntos de golpe lleguen a 0, pase 1 hora o decidas hacerlo desaparecer. Después de desaparecer, vuelve a su forma ornamental.
Esta llave invoca a la cabra, el familiar cabezudo. Este familiar posee una gran similitud con una cabra normal, pero la diferencia clave está en que sus cuernos están al rojo vivo.

```statblock
image: [[5. Cabra Onírica.jpg]]
name: Cabra Onírica
size: Pequeño
type: Bestia
ac: 12
hp: Number
hit_dice: 2
speed: 30 pies
stats: [14, 15, 12, 8, 13, 10]
skillsaves:
- Atletismo: +3, Acrobacias +3
senses: Percepción pasiva 11, visión en la oscuridad 60
languages: 
cr: 1
traits:
- name: Vigor Onírico
  desc: Los puntos de golpe máximos de esta criatura se multiplican por el nivel de su invocador.
- name: Ascendente
  desc: Cuando la cabra salta, puede añadir hasta 20 pies extra a la distancia de salto. Además, tiene ventaja en las pruebas relacionadas con saltar, escalar y mantener el equilibrio.
actions:
- name: Testarazo Candente
  desc: _Ataque de arma cuerpo a cuerpo:_ +4 al ataque, alcance 5 pies, un objetivo. _Impacto:_ 4 (1d6+2) puntos de daño contundente y 3 (1d4+2) puntos de daño de fuego. La criatura impactada debe realizar una tirada de salvación de Destreza (CD 12). Si falla, empieza a arder y debe realizar una tirada de salvación de Destreza al principio de cada uno de sus turnos con éxito o recibe 1d6 puntos de daño de fuego.
```