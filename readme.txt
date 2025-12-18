TRABAJO PRÁCTICO – XML

1. Contexto elegido
Gestión de un centro educativo.

2. Estructura del XML
El archivo datos.xml tiene como raíz <centroEducativo>.
Contiene tres elementos principales: clase, secretaria y direccion.
Cada uno tiene un atributo id y varios subelementos.
Las clases contienen alumnos, la secretaría administrativos y la dirección miembros.

centroEducativo
│
├── clase
│   ├── alumno
│   │   ├── nombre
│   │   └── edad
│   ├── alumno
│   │   ├── nombre
│   │   └── edad
│   ├── alumno
│   │   ├── nombre
│   │   └── edad
│   ├── alumno
│   │   ├── nombre
│   │   └── edad
│   └── alumno
│       ├── nombre
│       └── edad
│
├── secretaria
│   ├── administrativo
│   │   ├── nombre
│   │   └── turno
│   ├── administrativo
│   │   ├── nombre
│   │   └── turno
│   ├── administrativo
│   │   ├── nombre
│   │   └── turno
│   ├── administrativo
│   │   ├── nombre
│   │   └── turno
│   └── administrativo
│       ├── nombre
│       └── turno
│
└── direccion
    ├── miembro
    │   ├── nombre
    │   └── cargo
    ├── miembro
    │   ├── nombre
    │   └── cargo
    ├── miembro
    │   ├── nombre
    │   └── cargo
    ├── miembro
    │   ├── nombre
    │   └── cargo
    └── miembro
        ├── nombre
        └── cargo

Cada elemento principal contiene subelementos y utiliza atributos id para identificar sus elementos internos

3. Qué valida el DTD
El DTD valida el orden de los elementos, la repetición mínima de elementos,
y que los atributos id sean obligatorios.

4. Qué valida el XSD
El XSD valida la misma estructura que el DTD e incorpora tipos de datos,
como números enteros para id y edad.

5. Dificultades encontradas
La mayor dificultad fue mantener el mismo orden y estructura
en XML, DTD y XSD sin cometer errores de sintaxis.
