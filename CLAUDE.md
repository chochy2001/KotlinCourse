# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

**Kotlin Mastery** is a comprehensive educational repository containing a structured Kotlin course in Spanish. The course covers 85-90 hours of content across 26 modules organized in 5 progressive phases, from basic fundamentals to advanced topics.

## Architecture and Structure

### Course Organization
The repository follows a strict modular architecture with 5 phases:

1. **fase-01-fundamentos** (7 modules): Core language basics, null safety, functions, collections
2. **fase-02-poo** (7 modules): Object-oriented programming concepts and patterns  
3. **fase-03-funcional** (5 modules): Functional programming, lambdas, scope functions, generics
4. **fase-04-avanzados** (5 modules): Coroutines, DSLs, reflection, multiplatform, testing
5. **fase-05-integracion** (2 modules): Design patterns and performance optimization

### Module Structure
Each module follows a standardized layout:
```
modulo-XX-topic-name/
├── leccion/           # Theoretical content and explanations
├── ejercicios/        # Practice exercises in 3 difficulty levels
│   ├── basicos/
│   ├── intermedios/
│   └── avanzados/
├── mini-proyecto/     # Standalone practical projects
│   ├── especificacion/
│   ├── starter-code/
│   ├── solucion/
│   └── variantes/
└── recursos/          # Reference materials and cheat sheets
```

## Development Environment

### Required Tools
- **IntelliJ IDEA Community** (primary IDE)
- **JDK 11+** for Kotlin compilation
- **Kotlin Playground** as fallback for simple examples

### Git Workflow Policy
**CRITICAL**: Claude must NEVER create commits automatically. All git operations (add, commit, push) are handled exclusively by the user. Claude only provides code content and file modifications.

## Content Creation Guidelines

### Pedagogical Approach
The course follows the **5C Learning Cycle**:
1. **Contextualización**: Why this concept matters
2. **Conceptualización**: Theory with analogies 
3. **Codificación**: Live coding demonstrations
4. **Consolidación**: Guided practice exercises
5. **Creación**: Mini-project integration

### Key Teaching Principles
- **Objects-Later**: Procedural programming before OOP concepts
- **Null-Safety First**: Kotlin's safety features from day one
- **Error-Driven Learning**: Using common mistakes as teaching opportunities
- **Portfolio Building**: Each mini-project contributes to student portfolio

### Code Standards
- Follow official Kotlin coding conventions
- Prioritize immutable data structures (`val` over `var`)
- Implement comprehensive null safety practices
- Provide multiple solution approaches for complex problems
- Include error handling examples and common pitfalls

### Exercise Progression
- **Básicos**: Single concept application, minimal complexity
- **Intermedios**: Multiple concepts integration, moderate complexity  
- **Avanzados**: Real-world scenarios, full feature implementation

## Testing Framework
- **JUnit 5** for unit testing examples
- **MockK** for mocking in advanced modules
- Code coverage demonstrations in testing module

## Content Delivery Strategy
Each module produces:
- 25+ functional mini-projects for student portfolios
- Incremental complexity building from fundamentals to advanced topics
- Production-ready code examples following industry best practices
- Comprehensive documentation and error guides