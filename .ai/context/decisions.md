# Architectural & Technical Decisions

## 2026-02-02: AI Context Store
- **Decision**: Use a `.ai/` directory for long-term AI memory and session continuity.
- **Rationale**: Standardizes where AI agents look for history and state, reducing the need for the user to repeat context in every new session.
- **Components**: `history/` for session logs, `context/` for persistent project state.

## 2026-02-02: Version Control Strategy
- **Decision**: Follow **Git Flow**.
- **Rationale**: Provides a structured branching model for feature development, releases, and hotfixes.
