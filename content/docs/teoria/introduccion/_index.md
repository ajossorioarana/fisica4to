---
title: '1. Introducción a la Física: Magnitudes y Unidades'
weight: 10
---

# 1. Introducción a la Física: Magnitudes y Unidades
{{< hint info >}}
Cantidad medible de un sistema físico a la que se pueden asignar valores. Por ejemplo, *longitud*, *temperatura*, *fuerza*, *velocidad*.
{{< /hint >}}

## Introducción

La palabra "Física" deriva del griego *physikós*, que significa "natural" o "relativo a la naturaleza". La Física es la ciencia natural que estudia los fenómenos más fundamentales del Universo, como lo son la energía, la materia, el movimiento, las fuerzas, entre otros. 
Es la ciencia más elemental o primera, y eso hace que sea tan interesante: es el gran primer escalón para comprender un sinfín de fenómenos, desde el movimiento de los planetas, el electromagnetismo, las ondas de radio, el cálculo de edificios y puentes hasta cómo es posible que vuele un avión o calcular la trayectoria de un disparo de cañón.
Como sucede con toda disciplina, la primera exposición a la Física es ardua, ya que trae terminología y metodologías nuevas a las que no estábamos acostumbrados.

## Magnitudes físicas
Cuando estudiábamos matemática, trabajamos con números. Estudiamos números naturales, reales, funciones y ecuaciones, pero siempre trabajamos con números. 
Sin embargo, cuando salimos del aula y aplicamos esos conceptos matemáticos en la vida real, pocas veces tratamos con números aislados. Solemos acompañarlos de **unidades** que le dan sentido al número. De esta manera, no decimos que una cuadra mide "100", sino que mide "100 metros". Aunque cuando tenemos fiebre solemos decir "tengo 38 y medio", estamos haciendo referencia a que nuestra temperatura es de 38,5 °C. Si nos piden que llevemos dos kilos de chorizos y vamos a la carnicería y pedimos "dos" chorizos en vez de "dos kilos" de chorizos, no nos van a invitar más.
De la misma manera, durante la materia veremos muchos ejemplos de **magnitudes físicas**. 

{{< hint info >}}
**Definición: Magnitud física**  
Cantidad medible de un sistema físico a la que se pueden asignar valores. Por ejemplo, *longitud*, *temperatura*, *fuerza*, *velocidad*.
{{< /hint >}}

De esta manera veremos problemas donde un auto se mueve a una **velocidad** de "*100 km/hr*" o que recorre una **distancia** de *56 metros*. También veremos unidades que nos van a resultar menos familiares, como {{< katex >}}{m}/{s^2}{{< /katex >}} para aceleración o Newton para fuerzas.

## Magnitudes escalares y vectoriales
Todas las magnitudes que veremos caen dentro de una de las siguientes categorías: magnitudes **escalares** y magnitudes **vectoriales**.

{{< hint info >}}
**Definición: Escalar**  
Un *escalar* es aquella magnitud que puede ser descripta completamente con su **módulo**, que se forma mediante un número acompañado de su correspondiente unidad.
{{< /hint >}}

Un escalar es aquella magnitud que puede ser descripta completamente con su **módulo**, que se forma mediante un número acompañado de su correspondiente unidad.
Un claro ejemplo es la temperatura: decir que el agua para mate debe estar a 85°C (módulo) es suficiente para que otra persona comprenda cuánto debe calentar el agua. Otro ejemplo es la altura de una persona, que expresamos como 1.85 metros o 185 centímetros. En ambos casos estamos informando un número y una unidad, y es todo lo que necesitamos para transmitir la altura de una persona.

{{< hint info >}}
**Definición: Vector**  
Un *vector* es una magnitud física que, además de tener un módulo tiene una **dirección**. Se las representa con flechas.
{{< /hint >}}

Un caso emblemático de magnitud vectorial es la velocidad. Podemos decir que un auto va a 100 km/hr (módulo), pero la realidad es muy distinta si el auto va desde San Martín de los Andes a Neuquén o si va hacia Bariloche. En ambos casos voy a 100 km/hr, pero al cabo de una hora estaré en lugares diferentes.

## Sistemas de unidades
Las unidades correspondientes a las magnitudes que se ven en los primeros cursos de física pueden ser derivadas de cinco magnitudes elementales:
+ Masa (M)
+ Longitud (L)
+ Tiempo (T)
+ Carga eléctrica (Q)
+ Temperatura ({{< katex >}}\Theta{{< /katex >}})

Por ejemplo, si sabemos que la velocidad se obtiene como una longitud dividido por tiempo, las unidades de velocidad serán {{< katex >}}[v]=L/T{{< /katex >}}. De la misma forma, si queremos obtener las unidades de área, obtendríamos {{< katex >}}[A]={L}^{2}{{< /katex >}}.
Para mencionar un caso no trivial, la unidad utilizada para definir una fuerza es el newton (N). Veremos más adelante que una fuerza es igual a una masa multiplicado por una aceleración. De esta manera, la unidad de fuerza tendrá la siguientes dimensiones {{< katex >}}[F]=M.L/{T}^{2}{{< /katex >}}. 

Se puede decir mucho acerca de unidades y sistemas de unidades, pero lo más importante al respecto que hay que saber es:
+ Existen distintos **sistemas de unidades**, dependiendo de que unidades se utilizan en las magnitudes elementales. El más utilizado es el sistema MKS  (metro, kilogramo, segundo), que sirvió de base para el Sistema Internacional (SI).
+ Una respuesta de un problema físico requiere que estén bien tanto el número como la unidad. Es importantísimo saber trabajar con magnitudes con unidades.
+ A veces, las unidades de las distintas magnitudes a utilizar no van a ser compatibles. Debemos convertir todas las unidades a un mismo sistema de unidades, para poder operar entre las distintas magnitudes.

### Ejemplo 1: Convertir unidades de tiempo

{{< hint warning >}}
**Enunciado**  
La clase de Física duró 1 hora, 19 minutos y 50 segundos. Expresar la duración de la clase en minutos. Expresarla también en segundos.
{{< /hint >}}

Sabemos que una hora son 60 minutos, y que un minuto son 60 segundos. De esta manera:

{{< katex display >}}
1hr + 19 min + 50seg = 1*(60 min) + 19 min + 50*(\frac{1}{60}min) = 79,83 min
{{< /katex >}}

Si lo hubiéramos querido expresar en segundos:

{{< katex display >}}
1hr + 19 min + 50seg = 1*60*(60 seg) + 19 *(60 seg) + 50seg = 4.790seg
{{< /katex >}}

### Ejemplo 2: Convertir unidades de caudal

{{< hint warning >}}
**Enunciado**  
Una bomba de agua tiene un caudal de operación de 3,5 {{< katex >}}m3/hr{{< /katex >}} ¿Cuánto es expresado en litros/segundo {{< katex >}}(lt/s){{< /katex >}} sabiendo que un litro es igual a 1.000 {{< katex >}}cm^3{{< /katex >}}?
{{< /hint >}}

Convertimos el caudal[^1] de {{< katex >}}m^3/hr{{< /katex >}} a {{< katex >}}cm^3/s{{< /katex >}}:

{{< katex display >}}
3,5\frac{m^3}{hr}=3,5\frac{(100cm)^3}{60*60s}=3,5\frac{1.000.000cm^3}{3600s}=972,22\frac{cm^3}{s}
{{< /katex >}}

Sabiendo que {{< katex >}}1lt=1.000cm^3{{< /katex >}}:
{{< katex display >}}
972,22\frac{cm^3}{s} = 972,22\frac{0.001lt}{s}=0,97\frac{lt}{s}
{{< /katex >}}

# Conceptos claves
+ Una **magnitud física** se define como una cantidad que puede ser medible a la que se pueden asignar valores. Consta de un valor y una unidad. Ejemplos de esto son *longitud*, *temperatura*, *fuerza* y *corriente eleéctrica*.
+ Un **escalar** es una magnitud física que se define simplemente con su valor y unidad. Por ejemplo, *temperatura*, *edad*, *masa*, *altura*.
+ Un **vector** es una magnitud física que además de su valor y unidad, necesitamos expresar su **dirección** y **sentido**. Ejemplos de vectores son *fuerzas*, *aceleración*, *velocidad*.
+ Existen distintos **sistemas de unidades** que surgen dependiendo las unidades que le asignemos a las magnitudes elementales. En el curso usaremos primariamente el sistema MKS (*metro, kilogramo, segundo*).

# Further reading
+ Bla
+ Bla
+ Bla



[^1]: No vamos a trabajar con caudales en esta materia, pero es un buen ejemplo para practicar cambio de unidades.