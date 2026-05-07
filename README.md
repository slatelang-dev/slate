# Slate Language Core Library

Lexer → Parser → AST → Semantic Analysis → Diagnostics.

## Modules

- **lexer/** - Tokenization with string interpolation
- **ast/** - NodeKind enum and Node struct
- **parser/** - Recursive descent parser with Pratt precedence
- **analysis/** - Resolution, type checking, mutability, returns, usage
- **diagnostics/** - Error and warning rendering
- **ink/** - Terminal styling (ANSI colors)

## Entry Points

- `parse(source)` → ParseResult
- `analyse(program, file)` → AnalysisResult

Status: 0.1.0 rewrite in progress