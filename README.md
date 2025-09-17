# Práctica 2 - Programación Orientada a Objetos

## Descripción

Esta práctica tiene como objetivo aplicar los conceptos fundamentales de la **Programación Orientada a Objetos (POO)** mediante el desarrollo de un sistema que demuestre el uso correcto de clases, objetos, herencia, polimorfismo y encapsulación.

## Objetivos de Aprendizaje

Al completar esta práctica, el estudiante será capaz de:

- Diseñar e implementar clases con atributos y métodos apropiados
- Aplicar los principios de encapsulación mediante modificadores de acceso
- Implementar relaciones de herencia entre clases
- Demostrar el uso del polimorfismo a través de métodos virtuales y sobrescritura
- Utilizar constructores y destructores de manera efectiva
- Manejar excepciones y validación de datos
- Documentar el código de forma clara y profesional

## Conceptos de POO Cubiertos

### 1. **Clases y Objetos**
- Definición de clases con atributos y métodos
- Instanciación de objetos
- Uso de constructores y destructores

### 2. **Encapsulación**
- Modificadores de acceso (private, protected, public)
- Métodos getter y setter
- Validación de datos de entrada

### 3. **Herencia**
- Creación de clases base y derivadas
- Uso de super/base para acceder a métodos de la clase padre
- Jerarquías de clases

### 4. **Polimorfismo**
- Métodos virtuales y sobrescritura
- Implementación de interfaces
- Polimorfismo en tiempo de ejecución

## Estructura del Proyecto

```
Practica2-PA/
├── README.md
├── src/
│   ├── main/
│   │   ├── Clase1.java (o .cpp/.py según lenguaje)
│   │   ├── Clase2.java
│   │   └── Main.java
│   └── test/
│       └── TestClases.java
├── docs/
│   ├── diagrama_clases.png
│   └── documentacion.pdf
└── ejemplos/
    └── casos_uso.txt
```

## Requisitos del Sistema

### Requisitos Funcionales
- El sistema debe implementar al menos 3 clases con relación de herencia
- Debe incluir métodos que demuestren polimorfismo
- Implementar validación de datos de entrada
- Incluir manejo de excepciones
- Proporcionar una interfaz de usuario (consola o gráfica)

### Requisitos Técnicos
- Uso apropiado de modificadores de acceso
- Documentación en código (comentarios)
- Código limpio y bien estructurado
- Manejo adecuado de la memoria (si aplica)

## Entregables

1. **Código Fuente**: Implementación completa del sistema
2. **Diagrama de Clases**: UML mostrando la estructura del sistema
3. **Documentación**: Descripción detallada del diseño y funcionamiento
4. **Casos de Prueba**: Ejemplos de uso y validación del sistema
5. **Manual de Usuario**: Instrucciones para ejecutar el programa

## Instrucciones de Instalación y Ejecución

### Prerrequisitos
- [Especificar lenguaje y versión, ej: Java JDK 11+]
- [IDE recomendado, ej: IntelliJ IDEA, Eclipse, VS Code]
- [Otras dependencias si las hay]

### Pasos para Ejecutar
1. Clonar el repositorio
   ```bash
   git clone https://github.com/ianupiitaa/Practica2-PA.git
   cd Practica2-PA
   ```

2. Compilar el proyecto
   ```bash
   [Comando de compilación específico del lenguaje]
   ```

3. Ejecutar el programa principal
   ```bash
   [Comando de ejecución]
   ```

## Criterios de Evaluación

| Criterio | Peso | Descripción |
|----------|------|-------------|
| **Implementación de Clases** | 25% | Correcta definición y uso de clases y objetos |
| **Herencia y Polimorfismo** | 25% | Implementación apropiada de jerarquías y métodos virtuales |
| **Encapsulación** | 20% | Uso correcto de modificadores de acceso y validación |
| **Funcionalidad** | 15% | El programa cumple con los requisitos especificados |
| **Documentación** | 10% | Claridad en comentarios y documentación externa |
| **Calidad del Código** | 5% | Estructura, legibilidad y buenas prácticas |

## Ejemplo de Uso

```java
// Ejemplo conceptual - adaptar al lenguaje utilizado
public class Main {
    public static void main(String[] args) {
        // Instanciación de objetos
        ClaseBase objeto1 = new ClaseDerivada("parámetros");
        
        // Demostración de polimorfismo
        objeto1.metodoVirtual();
        
        // Uso de encapsulación
        objeto1.setAtributo("valor");
        System.out.println(objeto1.getAtributo());
    }
}
```

## Recursos Adicionales

- [Documentación del lenguaje utilizado]
- [Guías de buenas prácticas en POO]
- [Herramientas de diagramado UML]

## Autor

**[Nombre del Estudiante]**  
Matrícula: [Número de matrícula]  
Curso: Programación Orientada a Objetos  
Semestre: [Semestre/Año]

---

**Fecha de Entrega**: [Especificar fecha]  
**Versión**: 1.0
