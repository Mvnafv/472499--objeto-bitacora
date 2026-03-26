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
### Codigo modificado por mi 
```Processing

int[] temperatura = {10, 40, 15, 17, 30, 28, 26};
int tamano = 50;
int i = 0; //Iniciador


void setup(){
  size(900,900);
  background(0);
  frameRate(60); // Son los fps 
}

void draw(){
  
  {circle(450,450,mouseY);
 fill(255, 255, 255);}
 {circle(450,450,150);
 fill(255, 255, 255);}
  {tamano = temperatura[i];
  println(frameCount);
  println(" - ");
  println(tamano);
  circle(mouseX,mouseY,tamano);
 fill(#FF0000);
 stroke(3);
 
 i = i + 1;
 if (i > 6){
 i = 0;
 }
}

}

```

> [!WARNING]
> ENLACE [SECRETO](https://pbs.twimg.com/media/G3pBT_PXkAAyVDC?format=jpg&name=medium). :shipit:
