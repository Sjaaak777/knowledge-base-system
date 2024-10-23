# 📚 AngularJS

## 📝 Samenvatting

AngularJS is een JavaScript-framework ontwikkeld door Google voor het bouwen van dynamische web applicaties. Het volgt het MVC (Model-View-Controller) patroon en biedt two-way data binding, dependency injection en directive functionaliteit.

## 🎯 Belangrijkste punten

- <span style="color: #22c55e;">✓</span> Two-way data binding voor automatische UI updates
- <span style="color: #22c55e;">✓</span> Dependency Injection voor betere modulariteit
- <span style="color: #22c55e;">✓</span> Directives voor herbruikbare componenten
- <span style="color: #ef4444;">⚠</span> Performance issues bij grote applicaties
- <span style="color: #ef4444;">⚠</span> Verouderde technologie (Angular 2+ wordt aangeraden)

## 🔍 Details

> [!NOTE]+ Belangrijke concepten
> - Scopes ($scope)
> - Controllers
> - Services
> - Directives
> - Filters
> - Modules

> [!WARNING]+ Let op
> - AngularJS (1.x) wordt niet meer actief ontwikkeld
> - Migreer naar Angular 2+ voor nieuwe projecten
> - Performance optimalisatie is cruciaal bij grote applicaties

## 📊 Visualisaties

### Architectuur Flow
```mermaid
graph TD
    A[Start] -->|Initialisatie| B[Angular Module]
    B --> C[Config/Routes]
    B --> D[Controllers]
    D --> E[Scope]
    E --> F[View/Template]
    B --> G[Services]
    D --> G
    F -->|Two-way Binding| E
```

### Component Interactie
```mermaid
sequenceDiagram
    participant U as User
    participant V as View
    participant C as Controller
    participant S as Service
    
    U->>V: Interactie
    V->>C: Event Trigger
    C->>S: Service Call
    S-->>C: Data Response
    C-->>V: View Update
    V-->>U: UI Feedback
```

### Dependency Injectie
```mermaid
graph TD
    A[Module] -->|Registreert| B[Service Provider]
    B --> C[Injector]
    C -->|Injecteert| D[Controller]
    C -->|Injecteert| E[Directive]
    C -->|Injecteert| F[Factory]
```
