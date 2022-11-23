# KOTLIN
## 1.- **CONCEPTOS BASICOS**
### 1.1.- VARIABLES, TIPOS Y STRING TEMPLATES

1.1.1- **val y var**

Las variables locales de sólo lectura se definen con la palabra clave `val`. Sólo se les puede asignar un valor una vez.
```kotlin
    val a: Int = 1  // Declaración e inicialización.
    val b = 2   // `Int` El tipo es inferido.
    val c: Int  // El tipo es requerido cuando no se ha inicializado
    c = 3       // Asignación diferida
```

Las variables a las que podemos reasignar su valor se definen con la palabra clave `var`
```kotlin
    var x = 5 // `Int` El tipo es inferido
    x += 1
```

1.1.2.- **Tipos**

**Numéricos**

Enteros

```kotlin
    val byteNumber : Byte = 127 // 8
    val shortNumber : Short = 32767 // 16
    val intNumber : Int = 493921238810 // 32
    val longNumber : Long =  9439212385810// 64
```

Decimales

```kotlin
    val e = 2.7182818284 // Double 15-16 decimales
    val eFloat = 2.7182818284f // Float. 6-7 decimales
```

### 1.2.- FUNCIONES
### 1.3.- CLASES
### 1.4.- PROPIEDADES ( PROPERTIES )
### 1.5.- INTERFACES
### 1.6.- DATA CLASSES
### 1.7.- COLECCIONES
### 1.8.- ENUMS
### 1.9.- RANGOS
### 1.10.- CONTROLES DE FLUJOS
### 1.11.- NAMED ARGUMENTS Y VALORES POR DEFECTO
### 1.12.- LAMBDAS
### 1.13.- NULIDAD
### 1.14.- EXTENSION FUNCTIONS
### 1.15.- SCOPE FUNCTIONS
### 1.16.- OBJECTS
### 1.17.- DELEGACION DE PROPIEDADES
