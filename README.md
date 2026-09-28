# didactic-octo-succotash

A learning project for building a document Q&A application with verifiable source citations.

The goal is to import PDF and Markdown documents, retrieve relevant passages, answer questions from those passages, and show where each answer came from. The project is also used to practise evaluating retrieval quality, handling unanswered questions, and testing failures.

## Status

Early development. Features and setup instructions will be documented here as they are implemented.

## Planned first version

- ASP.NET Core API and React/TypeScript UI
- Local model through Ollama
- PDF text extraction with page numbers and Markdown import
- SQLite FTS5 search
- Answers with links to the source document and page
- A small, manually checked evaluation set

Hybrid search, reranking, observability, and deployment are later steps. They are not prerequisites for the first working version.

## Development

This section will contain exact prerequisites and run commands once the API and UI have been created.

Use public or self-written documents for development. Do not add client documents, credentials, or local MCP settings to this repository.

## Evaluation

The evaluation set will include questions with known source pages and questions that the documents cannot answer. Expected sources are checked manually. Results will be recorded with the model version and retrieval configuration so changes can be compared fairly.

## Development tools

The repository can be built and understood without AI coding tools. Some contributors may optionally use SocratiCode for code search, Graphify for code relationships, and Obsidian for personal learning notes. Their installation and data are not required by the application.

See `.github/copilot-instructions.md` for repository-specific Copilot guidance.# didactic-octo-succotash