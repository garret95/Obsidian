![[18. Ogro Onírico.jpg|cover hmed]]
# 18. Llave Onírica: Ogro

Una de las llaves oníricas de [[Boros]].
Como acción, puedes invocar al familiar que duerme en el interior de la llave. Tras ser usada, entra en letargo hasta tu próximo nivel (o tras un mes a partir del nivel 20). Todos los familiares poseen la capacidad de comprender las órdenes de su invocador sin problemas, los cuales además pueden comunicarse telepáticamente con ellos. Todos los familiares poseen visión en la oscuridad de hasta 60 pies y sus Puntos de Golpe son iguales a 1+ su mod. de Constitución por cada nivel de su invocador (mínimo 1). El familiar permanece invocado hasta que sus puntos de golpe lleguen a 0, pase 1 hora o decidas hacerlo desaparecer. Después de desaparecer, vuelve a su forma ornamental.
Esta llave invoca al ogro, el familiar bruto. Este familiar tiene el físico de un humanoide grande, con numerosas hileras de humo siendo expulsadas de su cuerpo.

```statblock
image: [[18. Ogro Onírico.jpg]]
name: Ogro Onírico
size: Grande
type: Monstruo
ac: 13
hp: Number
hit_dice: 3
speed: 30
stats: [15, 9, 14, 10, 11, 13]
skillsaves:
- Atletismo: +3, Intimidación +3
senses: Percepción pasiva 11, visión en la oscuridad 60
languages: Gigante
cr: 1
traits:
- name: Vigor Onírico
  desc: Los puntos de golpe máximos de esta criatura se multiplican por el nivel de su invocador.
- name: Astuto
  desc: Las criaturas tienen desventaja en las pruebas de Engaño y Sigilo contra el ogro. Además, el ogro inflige 1d8 de daño contundente extra en los ataques de oportunidad.
actions:
- name: Golpe Desatado
  desc: _Ataque de arma cuerpo a cuerpo:_ +4 al ataque, alcance 5 pies, 1 objetivo. _Impacto:_ 7 (1d12+2) puntos de daño contundente. La criatura impactada debe realizar una tirada de salvación de Fuerza CD 12 con éxito o es empujada 5 pies hacia atrás y queda tumbada.
```