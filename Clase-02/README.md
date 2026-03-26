# Apuntes de clases sobre los trabajos anteriores

* Hablamos de manera mas critica y descriptiva de las obras de la galeria de la universidad.
* Describimos la obra con los recuerdos de lo que vimos y lo que pensamos que hacia cada objeto.

> ***Mejor relleno de la portada***
*Revision de los trabajos anteriores*

## Programacion de processing

- ENLACE [Processing](https://processing.org/examples).

  ### Codigo usado en processing.

  ```Processing
  int tamano = 50;
  int t1 = 10;
  int t2 = 40;
  int t3 = 50;

  void setup(){
  size(600,600);
  frameRate(30);
  }
  void draw(){
  background(0);
  
  if (frameCount < 30){
   tamano = t1;
  }
    if (frameCount > 30){
   tamano = t2;
  }
     if (frameCount > 30){
   tamano = t3;
  }
  println(tamano);
  tamano = frameCount;
  ellipse(300,300,tamano,tamano);
  fill(#FF0000);
  }
  //frameCount
  ```


> [!WARNING]
> ENLACE [SECRETO](https://pbs.twimg.com/media/G3pBT_PXkAAyVDC?format=jpg&name=medium). :shipit:
