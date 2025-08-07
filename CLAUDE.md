# Claude Configuration for Kotlin Course

## Project Settings

- **Type**: Educational Content - Kotlin Course
- **Structure**: Modular course with 26 modules across 5 phases
- **Total Duration**: 85-90 hours of content

## Development Guidelines

### Code Style
- Follow Kotlin coding conventions
- Use descriptive variable and function names
- Prefer immutable data structures when possible
- Implement null safety best practices

### Project Structure
- Each module follows: `leccion/`, `ejercicios/`, `mini-proyecto/`, `recursos/`
- Exercise difficulty: basic → intermediate → advanced
- Mini-projects should be standalone and functional

### Git Workflow
**IMPORTANT**: Claude should NEVER create commits automatically.
- User handles all git operations (add, commit, push)
- Claude provides code and file changes only
- No automatic commits, no git commands unless explicitly requested

### Content Creation Priorities
1. Focus on practical, hands-on learning
2. Each concept must have immediate application
3. Mini-projects should build real portfolio pieces
4. Error-driven learning approach

### File Organization
- Keep code examples simple and focused
- Include comprehensive error handling examples
- Provide multiple solution approaches when relevant
- Document common pitfalls and solutions

## Tools and Commands

### Kotlin Development
- Primary IDE: IntelliJ IDEA Community
- Fallback: Kotlin Playground online
- JDK: Version 11 or higher required

### Testing
- Unit testing framework: JUnit 5
- Mocking: MockK
- Code coverage and quality metrics included

## Course Philosophy
- Objects-Later approach: Procedural concepts before OOP
- Null-Safety First: Teach safe programming from day 1
- Contextual learning: Every exercise has real-world purpose
- Portfolio building: Students create 25+ functional projects