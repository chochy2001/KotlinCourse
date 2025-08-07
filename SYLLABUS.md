# SYLLABUS - Kotlin Mastery: El Curso Completo

## 📋 Índice General del Curso

### 🏗️ FASE I: FUNDAMENTOS (25 horas)

#### Módulo 0: Preparación del Entorno (2 horas)
**Mini-proyecto**: "Mi Ambiente de Desarrollo Personalizado"
- Configuración de IntelliJ IDEA en Windows, macOS y Linux
- Kotlin Playground como alternativa en línea
- Primer programa "Hola Mundo" con variaciones

#### Módulo 1: Variables y Tipos de Datos (4 horas)
**Mini-proyecto**: "Calculadora de Finanzas Personales"
- `val` vs `var`: inmutabilidad por diseño
- Sistema de tipos e inferencia
- Tipos básicos: Int, Double, String, Boolean
- Operaciones y conversiones de tipos
- String templates y formateo

#### Módulo 2: Control de Flujo (4 horas)
**Mini-proyecto**: "Sistema de Decisiones Inteligente"
- Expresiones `if` vs `when`
- Rangos y operador `in`
- Smart casting automático
- Pattern matching básico

#### Módulo 3: Null Safety - El Superpoder de Kotlin (3 horas)
**Mini-proyecto**: "Validador de Datos Robusto"
- Tipos nullable vs non-nullable
- Operadores `?.`, `?:`, `!!`
- Smart casts con null checks
- Función `let` y safe calls

#### Módulo 4: Bucles y Repetición (4 horas)
**Mini-proyecto**: "Generador de Patrones y Arte ASCII"
- `for`, `while`, `do-while`
- Rangos y progresiones
- `break`, `continue` y labels
- Bucles anidados eficientes

#### Módulo 5: Funciones (4 horas)
**Mini-proyecto**: "Biblioteca de Utilidades Reutilizables"
- Funciones con parámetros por defecto y nombrados
- Funciones de expresión única
- Sobrecarga de funciones
- Funciones locales y scope

#### Módulo 6: Colecciones Fundamentales (4 horas)
**Mini-proyecto**: "Gestor de Inventario Dinámico"
- Lists, Sets, Maps
- Mutables vs Inmutables
- Operaciones básicas de colecciones
- Iteración y transformación simple

### 🎭 FASE II: PROGRAMACIÓN ORIENTADA A OBJETOS (30 horas)

#### Módulo 7: Clases y Objetos (5 horas)
**Mini-proyecto**: "Simulador de Cuenta Bancaria"
- Definición de clases, propiedades y métodos
- Constructores primarios y secundarios
- Bloques `init`
- Getters y setters personalizados

#### Módulo 8: Encapsulación y Visibilidad (4 horas)
**Mini-proyecto**: "API de Gestión de Usuarios"
- Modificadores de visibilidad: private, protected, internal, public
- Backing fields y properties
- Companion objects
- Nested e inner classes

#### Módulo 9: Herencia y Polimorfismo (5 horas)
**Mini-proyecto**: "Zoo Virtual con Jerarquía Animal"
- Clases `open` y `final`
- Override y super
- Clases abstractas
- Polimorfismo en acción

#### Módulo 10: Interfaces y Contratos (4 horas)
**Mini-proyecto**: "Sistema de Pagos Múltiples"
- Definición e implementación de interfaces
- Herencia múltiple de interfaces
- Default methods en interfaces
- Interfaces funcionales (SAM)

#### Módulo 11: Data Classes y Sealed Classes (4 horas)
**Mini-proyecto**: "Máquina de Estados para UI"
- Data classes y destructuring
- Sealed classes para jerarquías cerradas
- Enum classes avanzadas
- When exhaustivo con sealed classes

#### Módulo 12: Object Declarations y Singletons (3 horas)
**Mini-proyecto**: "Sistema de Configuración Global"
- Object declarations
- Companion objects patterns
- Object expressions
- Factory patterns idiomáticos

#### Módulo 13: Delegación y Composición (5 horas)
**Mini-proyecto**: "Sistema de Componentes Modulares"
- Delegación de clases con `by`
- Property delegation
- Lazy, observable, vetoable
- Composición vs herencia

### 🔧 FASE III: PROGRAMACIÓN FUNCIONAL (20 horas)

#### Módulo 14: Funciones de Orden Superior y Lambdas (4 horas)
**Mini-proyecto**: "Motor de Reglas de Negocio"
- Tipos de función
- Expresiones lambda y sintaxis
- Closures y capturing de variables
- Inline functions y performance

#### Módulo 15: Operaciones Funcionales en Colecciones (5 horas)
**Mini-proyecto**: "Analizador de Datos de Ventas"
- `map`, `filter`, `reduce`, `fold`
- `groupBy`, `partition`, `associate`
- Sequences y lazy evaluation
- Performance considerations

#### Módulo 16: Scope Functions (3 horas)
**Mini-proyecto**: "Builder DSL para Configuración"
- `let`, `run`, `with`, `apply`, `also`
- Cuándo usar cada una
- Encadenamiento idiomático
- Context receivers

#### Módulo 17: Extension Functions (4 horas)
**Mini-proyecto**: "Framework de Validación Extensible"
- Extension functions y properties
- Scope de extensiones
- Member extensions
- Extensions en companion objects

#### Módulo 18: Genéricos y Varianza (4 horas)
**Mini-proyecto**: "Contenedor de Datos Type-Safe"
- Generic classes y functions
- Type constraints (where)
- Variance: `in`, `out`, invariancia
- Reified type parameters

### 🚀 FASE IV: TEMAS AVANZADOS (20 horas)

#### Módulo 19: Corrutinas y Asincronía (6 horas)
**Mini-proyecto**: "Descargador Concurrente de Archivos"
- Suspend functions
- Coroutine builders: launch, async, runBlocking
- Structured concurrency
- Flow básico y operators
- Exception handling en corrutinas

#### Módulo 20: DSLs y Metaprogramación (4 horas)
**Mini-proyecto**: "HTML/SQL DSL Builder"
- Type-safe builders
- @DslMarker annotation
- Operator overloading
- Infix functions

#### Módulo 21: Reflection y Anotaciones (3 horas)
**Mini-proyecto**: "Serializador JSON Custom"
- KClass y reflection básica
- Anotaciones personalizadas
- Processing en runtime
- Limitaciones y performance

#### Módulo 22: Multiplatform Básico (4 horas)
**Mini-proyecto**: "Librería Compartida Simple"
- Expect/Actual declarations
- Common, JVM, JS, Native targets
- Estructura de proyecto multiplatform
- Publicación de librerías

#### Módulo 23: Testing y Calidad (3 horas)
**Mini-proyecto**: "Suite de Tests Completa"
- JUnit 5 con Kotlin
- Mocking con MockK
- Property-based testing
- Coverage y métricas

### 🎨 FASE V: INTEGRACIÓN Y MEJORES PRÁCTICAS (10 horas)

#### Módulo 24: Patrones de Diseño en Kotlin (5 horas)
**Mini-proyecto**: "Aplicación con Arquitectura Clean"
- Patrones creacionales idiomáticos
- Patrones estructurales en Kotlin
- Patrones de comportamiento
- Anti-patrones a evitar

#### Módulo 25: Performance y Optimización (5 horas)
**Mini-proyecto**: "Optimizador de Algoritmos"
- Profiling básico
- Inline functions y performance
- Collection performance
- Memory management
- Benchmarking con JMH

## 📚 Recursos por Módulo

### Cada módulo incluye:
- 📹 **Video teórico** (20-30 min)
- 💻 **Live coding** (30-40 min)
- 📋 **Cheatsheet progresivo**
- ❌ **Guía de errores comunes**
- 🏗️ **Mini-proyecto completo**
- ✅ **5-8 ejercicios graduados**

## 🎯 Metodología de Evaluación

### Por cada módulo:
- **30%** Ejercicios prácticos
- **50%** Mini-proyecto 
- **20%** Code review

### Portfolio final:
- **25+ proyectos funcionales**
- **Documentación técnica**
- **Código production-ready**
- **Commits incrementales en GitHub**

## 🔄 Flujo de Aprendizaje

1. **🎯 Contextualización** → ¿Por qué necesito esto?
2. **💡 Conceptualización** → ¿Cómo funciona?
3. **💻 Codificación** → Live coding paso a paso
4. **🔧 Consolidación** → Práctica guiada
5. **🏗️ Creación** → Mini-proyecto integrador

---

*Total: 85-90 horas de contenido estructurado para dominar Kotlin desde cero*