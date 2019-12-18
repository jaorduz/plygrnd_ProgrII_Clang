# Data type

Consider the type: _int_, _float_ and...

?[What are the other types?]
-[ ] main, string, char
-[x] double, char, bool
-[ ] String, return, sizeof
-[ ] stdio.h, printf, Bool


<!---
Clase:
![analog clase](/img/car_class.png)

Objetos:
![analog objeto1](/img/car_obj1.png)
![analog objeto2](/img/car_obj2.png)

```cpp
class MiClase
{
  //Aquí van los miembros de la clase: Variables y funciones
}; //NO olvidar el ;
```
Los objetos, tal como se había mencionado con anterioridad, son variables (instancias) del tipo de dato definido por una clase. Por tanto, los
objetos se pueden declarar al interior o por fuera de funciones, tal y como una variable local o global respectivamente. Pueden ser declarados
como miembros de otras clases, es decir al interior de otras clases. Luego, para declarar un objeto primero se utiliza el mobre de la clase a la
que pertenece el objeto seguido de un nombre para el objeto y de una lista opcional de inicialización entre paréntesis. Dicha lista se verá más
adelante.

```cpp
MiClase objetoGlobal;  //Declaración de un objeto global de la clase MiClase

int main()
{
	MiClase objetoLocal; //Declaración de un objeto local de la clase MiClase  
}
```
--->