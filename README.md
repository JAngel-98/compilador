# Compilador del Libro de Aho

## Compilador código fuente

El primer paso para el uso de esta compilador es compilar las clases en Java, para lo que que ejecuta lo siguiente en la carpeta raíz del código fuente en java:

```
javac ./*/*.java
```

o carpeta por carpeta:

```
javac analizadorLexico/*.java
javac simbolos/*.java
javac inter/*.java
javac analizador/*.java
javac main/*.java
```

## Funcionamiento

Para su funcionamiento se debe ingresar un código que respete la sintaxis del compilador, el cual debe estar escrito en el archivo "prueba" que esta en el directorio raíz del proyecto, y como resultado este arrojara su corresponddiente código ensamblador. Para ello se usa el siguiente comando:

```
java main.Main < prueba
```

