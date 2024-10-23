# 🗄️ Kennisbank Systeem

## 📝 Samenvatting

Dit kennisbank systeem is een gestructureerde verzameling van markdown bestanden, georganiseerd in categorieën en verrijkt met consistente styling via Everforest theming. Het systeem combineert de kracht van VS Code, markdown en CSS voor een prettige documentatie ervaring.

## 🎯 Belangrijkste punten

- <span class="highlight-success">✓</span> Gestructureerde mappenstructuur voor optimale organisatie
- <span class="highlight-success">✓</span> Consistente styling met Everforest thema
- <span class="highlight-success">✓</span> Markdown-gebaseerd voor maximale compatibiliteit
- <span class="highlight-success">✓</span> Uitgebreide opmaak mogelijkheden via CSS classes
- <span class="highlight-info">ℹ</span> Werkt zowel in VS Code als Obsidian

## 🔍 Details

### Technische Architectuur

1. <span class="highlight-info">📂</span> **Bestandsstructuur**

plaintext
knowledge/
├── Technologie/
│ ├── Programmeren/
│ ├── Netwerken/
│ ├── Databases/
│ └── AI en Machine Learning/
├── Wetenschap/
├── Persoonlijke ontwikkeling/
├── Projecten/
└── Referenties/

2. **Bestandsverwerking**
- Nieuwe .md bestanden worden automatisch gecategoriseerd op basis van rules
- Templating systeem voor consistente documentstructuur
- Variabelen worden dynamisch ingevuld bij creatie

3. **Technische Componenten**
- **Parser**: Verwerkt markdown syntax naar HTML
- **Rules Engine**: 
  - Matcht bestanden op basis van extensie/pad
  - Voert gedefinieerde acties uit (move, rename, etc)
- **Template Engine**:
  - Ondersteunt variabele substitutie
  - Biedt voorgedefinieerde layouts
  - Handhaaft consistente structuur

4. **Styling Systeem**

/ Voorgedefinieerde kleuren /
:root {
--success: #22c55e;
--warning: #ef4444;
--info: #3b82f6;
--neutral: #eab308;
}
/ Highlight classes /
.highlight-success { color: var(--success); }
.highlight-warning { color: var(--warning); }
.highlight-info { color: var(--info); }
.highlight-neutral { color: var(--neutral); }


5. **Integraties**
- VS Code extensies:
  - Markdown All in One
  - Markdown Preview Enhanced
  - Paste Image
- Obsidian plugins:
  - Dataview
  - Calendar
  - Graph View

## 📚 Bronnen

- [VS Code Markdown Documentation](https://code.visualstudio.com/docs/languages/markdown)
- [Obsidian Help](https://help.obsidian.md)

## 🔗 Gerelateerde onderwerpen

- [[Markdown Syntax]]
- [[VS Code Setup]]
- [[Obsidian Setup]]
- [[Knowledge Management]]

## 📝 Notities

Status: <span style="color: #22c55e;">●</span> Actief  
Prioriteit: <span style="color: #eab308;">●</span> Medium

## 🏷️ Tags

#kennismanagement #markdown #vscode #obsidian #documentatie
