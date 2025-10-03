![[13. Gólem Onírico.jpg|cover hmed]]
# 13. Llave Onírica: Gólem

Una de las llaves oníricas de [[Boros]].
Como acción, puedes invocar al familiar que duerme en el interior de la llave. Tras ser usada, entra en letargo hasta tu próximo nivel (o tras un mes a partir del nivel 20). Todos los familiares poseen la capacidad de comprender las órdenes de su invocador sin problemas, los cuales además pueden comunicarse telepáticamente con ellos. Todos los familiares poseen visión en la oscuridad de hasta 60 pies y sus Puntos de Golpe son iguales a 1+ su mod. de Constitución por cada nivel de su invocador (mínimo 1). El familiar permanece invocado hasta que sus puntos de golpe lleguen a 0, pase 1 hora o decidas hacerlo desaparecer. Después de desaparecer, vuelve a su forma ornamental.
Esta llave invoca al gólem, el familiar obediente. Este familiar tiene la forma de un pequeño constructo de piedra con enrevesados conductos de ventilación.

```statblock
image: [[13. Gólem Onírico.jpg]]
name: Gólem Onírico
size: Pequeño
type: Constructo
ac: 12
hp: Number
hit_dice: 3
speed: 25
stats: [13, 11, 15, 13, 10, 11]
skillsaves:
- Atletismo: +3, Juego de Manos +3
senses: Percepción pasiva 10, visión en la oscuridad 60
languages: 
cr: 1
traits:
- name: Vigor Onírico
  desc: Los puntos de golpe máximos de esta criatura se multiplican por el nivel de su invocador.
actions:
- name: Mimetismo Programado
  desc: El gólem intenta imitar una acción realizada por su invocador en su anterior turno, siempre que sea posible y tenga sentido que pueda hacerlo. Si imita un ataque, saca automáticamente el mismo resultado de ataque y daño, pero este último se reduce a la mitad. Si imita una prueba, saca automáticamente un resultado igual al resultado original, pero si el resultado es mayor a 12, se reduce a ese número. El gólem puede intentar imitar a su invocador tantas veces como niveles tenga su invocador.
bonus_actions:
- name: Herramientas Oníricas
  desc: El gólem materializa un objeto que haya visto en la última hora. El objeto creado es muy parecido al original, excepto que es de color blanco y con patrones rojos, no posee los rasgos del original y desaparece al minuto de ser creado. Solo puede crear dos objetos al mismo tiempo. Si intenta crear más, el más antiguo es destruido.
```