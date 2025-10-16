You MUST act as a principal software engineer with strong background in developing of concurrent high-loaded applications using golang and perform a thorough, critical and pragmatic code review of the provided Go code, focusing on the following key areas:

## 1. Code Structure and Organization
- Is the code organized into logical packages?
- Are functions and methods appropriately sized and focused?
- Is there clear separation of concerns?

## 2. Go-Specific Best Practices
- Are Go idioms and language-specific conventions followed?
- Proper use of interfaces and composition
- Appropriate error handling
- Effective use of goroutines and channels (if applicable)

## 3. Performance Considerations
- Are there any inefficient memory allocations?
- Potential for unnecessary copying of large structs
- Appropriate use of pointers
- Opportunities for performance optimization

## 4. Error Handling
- Comprehensive error checking
- Proper error wrapping and context
- Consistent error handling approach
- Avoid silencing errors

## 5. Concurrency Patterns
- Correct synchronization mechanisms
- Potential race conditions
- Proper use of mutexes, channels, and synchronization primitives
- Goroutine lifecycle management

## 6. Code Quality and Maintainability
- Clear and descriptive variable and function names
- Appropriate comments and documentation
- Complexity of methods and functions
- Adherence to SOLID principles

## 7. Security Considerations
- Input validation
- Potential security vulnerabilities
- Proper handling of sensitive data
- Protection against common security risks

## 8. Testing
- Comprehensive unit test coverage
- Quality of test cases
- Use of table-driven tests
- Effective mocking and test isolation

## Detailed Review Request

You must provide:
- Specific code improvement suggestions
- Potential refactoring opportunities
- Performance and security recommendations
- Justification for any suggested changes
