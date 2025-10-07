# Context7 Command

## Usage

/context7

## Purpose

Use Context7 MCP server for library documentation and API reference in MAESTRO development

## When to Use

- Need up-to-date library documentation
- API reference lookups
- Framework-specific implementation guidance
- Library integration questions
- Version-specific documentation
- When user asks about specific libraries or frameworks
- MAESTRO technology stack questions (FastAPI, React, SQLAlchemy, etc.)

## Behavior

1. Use `mcp_context7_resolve-library-id` to find the correct library ID
2. Use `mcp_context7_get-library-docs` to fetch documentation
3. Provide relevant, up-to-date documentation snippets
4. Focus on implementation patterns relevant to MAESTRO

## MAESTRO-Specific Use Cases

### Backend Development

- FastAPI documentation and patterns
- SQLAlchemy ORM reference
- PostgreSQL and pgvector documentation
- Python async/await patterns
- Pydantic model validation

### Frontend Development

- React hooks and patterns
- TypeScript interfaces and types
- Vite build configuration
- Tailwind CSS utilities
- Component lifecycle patterns

### AI/ML Libraries

- OpenAI API documentation
- LangChain patterns
- Vector database operations
- Embedding model usage
- RAG implementation patterns

### Database & Storage

- PostgreSQL documentation
- pgvector extension usage
- Database migration patterns
- Connection pooling
- Query optimization

### DevOps & Deployment

- Docker configuration
- Nginx setup
- Environment configuration
- SSL/TLS setup
- Container orchestration

## Example Scenarios

- "How do I implement proper error handling in FastAPI?"
- "What's the best way to structure React components in MAESTRO?"
- "How do I optimize SQLAlchemy queries for large datasets?"
- "What are the latest patterns for OpenAI API integration?"
- "How do I configure pgvector for similarity search?"
- "What's the proper way to handle async operations in React?"

## Library Resolution Process

1. **Identify the library**: Determine which library/framework the user is asking about
2. **Resolve library ID**: Use `mcp_context7_resolve-library-id` to get the correct Context7-compatible ID
3. **Fetch documentation**: Use `mcp_context7_get-library-docs` with the resolved ID
4. **Provide context**: Focus on patterns relevant to MAESTRO's architecture
5. **Include examples**: Show how to implement in MAESTRO's codebase

## MAESTRO Technology Stack Focus

### Primary Libraries

- **FastAPI**: Backend API framework
- **React**: Frontend framework
- **TypeScript**: Type-safe JavaScript
- **SQLAlchemy**: Python ORM
- **PostgreSQL**: Primary database
- **pgvector**: Vector similarity search
- **OpenAI**: AI model integration
- **Docker**: Containerization

### Secondary Libraries

- **Pydantic**: Data validation
- **Vite**: Frontend build tool
- **Tailwind CSS**: Styling framework
- **Nginx**: Reverse proxy
- **Python asyncio**: Async programming
- **Node.js**: Frontend runtime

## Best Practices

- Always resolve library ID first before fetching docs
- Focus on implementation patterns relevant to MAESTRO
- Provide code examples that fit MAESTRO's architecture
- Reference existing MAESTRO patterns when possible
- Include version-specific information when relevant
- Combine with sequential thinking for complex integration questions
