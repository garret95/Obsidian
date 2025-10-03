![[21. Escorpión Onírico.jpg|cover hmed]]
# 21. Llave Onírica: Escorpión

Una de las llaves oníricas de [[Boros]].
Como acción, puedes invocar al familiar que duerme en el interior de la llave. Tras ser usada, entra en letargo hasta tu próximo nivel (o tras un mes a partir del nivel 20). Todos los familiares poseen la capacidad de comprender las órdenes de su invocador sin problemas, los cuales además pueden comunicarse telepáticamente con ellos. Todos los familiares poseen visión en la oscuridad de hasta 60 pies y sus Puntos de Golpe son iguales a 1+ su mod. de Constitución por cada nivel de su invocador (mínimo 1). El familiar permanece invocado hasta que sus puntos de golpe lleguen a 0, pase 1 hora o decidas hacerlo desaparecer. Después de desaparecer, vuelve a su forma ornamental.
Esta llave invoca al escorpión, el familiar territorial. Este familiar posee la apariencia de un escorpión mucho más grande de lo normal.

```statblock
image: [[21. Escorpión Onírico.jpg]]
name: Escorpión Onírico
size: Mediano
type: Bestia
ac: 13
hp: Number
hit_dice: 2
speed: 30 pies
stats: [13, 15, 13, 9, 13, 10]
skillsaves:
- Sigilo: +3, Supervivencia +3
senses: Percepción pasiva 11, visión en la oscuridad 60
languages: Conoce tlincalli, pero no puede hablar
cr: 1
traits:
- name: Vigor Onírico
  desc: Los puntos de golpe máximos de esta criatura se multiplican por el nivel de su invocador.
- name: Acechador Furtivo
  desc: Mientras el escorpión se encuentre bajo la superficie, tiene ventaja en las tiradas de ataque y se puede mover 15 pies más.
actions:
- name: Aguijonazo
  desc: _Ataque cuerpo a cuerpo:_ +3 al ataque, alcance 5 pies, 1 objetivo. _Impacto:_ 7 (1d6+1) puntos de daño perforante. Si la criatura atacada recibe daño, debe realizar una tirada de salvación de Constitución CD 12. Si tiene éxito, recibe 1d4 de daño por veneno. Si falla, queda además paralizada.
```