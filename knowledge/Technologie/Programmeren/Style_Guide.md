# 📚 Markdown Style Guide

## 📝 Samenvatting

Een complete gids voor de markdown styling conventies binnen het kennisbank systeem, inclusief opmaak regels en best practices.

## 🎯 Belangrijkste punten

- <span style="color: #22c55e;">✓</span> Consistente opmaak over alle documenten
- <span style="color: #22c55e;">✓</span> Verbeterde leesbaarheid
- <span style="color: #22c55e;">✓</span> Gestandaardiseerde emoji gebruik
- <span style="color: #ef4444;">⚠</span> Vereist kennis van Markdown syntax

## 🔍 Details

> [!NOTE]+ Markdown Basis Regels
> - Gebruik headers met emoji prefixes (# 📚, ## 📝, etc.)
> - Laat één lege regel tussen secties
> - Gebruik backticks voor `code snippets`
> - Gebruik drie backticks voor code blocks met taal specificatie
> - Gebruik blockquotes (>) voor belangrijke notities
> - Gebruik lijsten met - voor opsommingen

> [!WARNING]+ Emoji Conventies
> - 📚 Voor hoofdtitels
> - 📝 Voor samenvattingen en notities
> - 🎯 Voor belangrijke punten
> - 🔍 Voor details
> - 📊 Voor visualisaties
> - 🔗 Voor links en referenties
> - 🏷️ Voor tags

## 📊 Visualisaties

### Markdown Hiërarchie
```mermaid
graph TD
    A[Document] -->|Level 1| B[# Hoofdtitel]
    B -->|Level 2| C[## Secties]
    C -->|Level 3| D[### Subsecties]
    D -->|Level 4| E[#### Details]
    
    style A fill:#f9f,stroke:#333
    style B fill:#bbf,stroke:#333
    style C fill:#ddf,stroke:#333
    style D fill:#eef,stroke:#333
```

### Opmaak Flow
```mermaid
sequenceDiagram
    participant C as Content
    participant M as Markdown
    participant R as Rendering
    C->>M: Toepassing syntax
    M->>R: Parsing
    R->>C: Geformatteerde weergave
```

## 📚 Bronnen

- [GitHub Markdown Guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/)

## 🔗 Gerelateerde onderwerpen

- [[Richtlijnen]]
- [[Templates]]
- [[Kennisbank_Systeem]]

## 📝 Notities

Status: <span style="color: #22c55e;">●</span> Actief
Prioriteit: <span style="color: #22c55e;">●</span> Hoog

## 🏷️ Tags

#markdown #styling #documentatie #richtlijnen #opmaak
