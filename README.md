# Introducción a Unity
Para la realización de esta práctica se han realizado los siguientes pasos:
# Creación del terreno
El primer Game Object que he introducido es el terreno. Los valores de escala y posición son los predeterminados. A este objeto le ponemos la etiqueta _isla_. Lo primero que modificamos del terreno es la textura del mismo; para ello, vamos a Basic Terrain < Material, y cambiamos a la opción _custom_, para poder editar el terreno. Una vez seleccionada una textura, lo siguiente que he hecho ha sido simular unas monstañas, con la herramienta #Brush. Con los parámetros de tamaño y altura adecuados, con esta herramienta conseguimos un efecto similar a un terreno montañoso y abrupto. 
# Creación de dos Game Objects
Como se especifica en el enunciado, he añadido dos esferas. Sin embargo, las he modificado de forma para que estén más alargadas, y las he bajado del plano, de forma que solo queda visible un semicírculo. Con este efecto, añadiéndole una textura adecuada, las dos esferas simulan dos rocas en el mar. Sobre una de ellas añadimos otro Game Object, #Ethan, al que también modifico añadiéndole texturas. Hay que destacar que, al crear a Ethan, el objeto se divide automáticamente en esqueleto, cuerpo y gafas. De esta manera, cuando queramos añadirle una textura al objeto deberemos añadirla sobre alguna de estas tres subcategorías, de modo que modifiquemos solo el cuerpo de Ethan, o las gafas por ejemplo. Ethan tiene como etiqueta #player, mientras que las dos esferas tienen como etiqueta #Piedra. 
# Creación de árboles y agua
A partir de los Standard Assets podemos añadir el agua, que solo cubrirá parte del terreno, al haber diferentes alturas en el mismo. Se identifica con la etiqueta Mar. Del mismo modo, añadimos los árboles a partir de los Standard Assets. Si bien Unity nos da la opción de añadir un árbol desde el menú de Game Objects, añadirlo desde los Standard Assets no solo nos da un mejor resultado, sino que nos permite elegir entre distintos árboles, y añadirlos de una forma determinada. En mi caso, he añadido coníferas, utilizando la herramienta #Brush. Es por ello que no se ha creado un objeto nuevo para los árboles, así que tampoco habrá etiquetas. 
