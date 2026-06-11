# Contributing Guidelines

Thank you for your interest in contributing to this project!

## How to Contribute

1. **Fork** the repository
2. **Create a new branch** for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes** with clear, descriptive commits
4. **Test** your code thoroughly
5. **Push** to your fork
6. **Submit a Pull Request** with a clear description

## Code Standards

### C Code Style
- Use meaningful variable and function names
- Add comments for complex logic
- Follow consistent indentation (2 or 4 spaces)
- Keep functions focused and modular
- Add function documentation headers

### Example Format
```c
/*
 * Function: calculate_sum
 * Description: Calculates the sum of two integers
 * Parameters:
 *   - a: First integer
 *   - b: Second integer
 * Returns: Sum of a and b
 */
int calculate_sum(int a, int b) {
    return a + b;
}
```

## Naming Conventions
- Files: `lowercase_with_underscores.c`
- Functions: `camelCase()`
- Variables: `snake_case`
- Constants: `UPPERCASE_WITH_UNDERSCORES`

## Guidelines
- Keep code simple and readable
- Write efficient algorithms
- Avoid compiler warnings
- Test on multiple platforms if possible
- Document non-obvious implementations

## Pull Request Process

1. Update the README.md if needed
2. Ensure your code compiles without warnings
3. Add appropriate comments and documentation
4. Keep commits atomic and well-described

## Questions?
Open an issue or discussion for questions about the project!
