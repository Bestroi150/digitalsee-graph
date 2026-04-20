# DigitalSEE: Site Object Knowledge Graph Visualization

## Overview

DigitalSEE presents an interactive knowledge graph visualization framework for exploring archaeological and historical site data. This web-based application integrates multidisciplinary research collections encompassing epigraphy, architectural analysis, historical documentation, and contemporary scholarship. The visualization employs network analysis methodologies to reveal relational patterns among sites, archaeological classifications, historical periods, and scholarly contributions.

## Technical Capabilities

The platform provides the following analytical features:

- **Network Visualization Engine**: Interactive graph-based interface enabling exploration of nodal relationships and edge connectivity among archaeological entities
- **Full-Text Query Interface**: Semantic search functionality supporting site name and identifier-based queries
- **Hierarchical Filtering**: Dynamic node and edge filtering mechanisms organized by classification (category, chronological age, authorship)

## Nodal Classification Schema

The visualization employs color-coding and morphological differentiation to denote entity types:
  - 🔴 **Red**: Digital Inscriptions (DI) — Epigraphic records
  - 🟢 **Green**: Travel Accounts (IV) — Historical documentation
  - 🔵 **Blue**: Schad Materials (MB) — Eighteenth-century surveys
  - 🔷 **Cyan**: Racheva Research (VR) — Contemporary analysis
  - 🟣 **Purple**: Architecture Materials (KA) — Structural studies
  - 🟡 **Yellow**: Categorical Taxonomy — Object classification nodes
  - 🩷 **Pink**: Chronological Entities — Historical period designations
  - 🔺 **Triangle**: Authorial Attribution — Publication contributor nodes

## Dataset Composition

The aggregated dataset comprises the following components:

- **Site Entities**: 272 archaeological and historical sites
- **Categorical Taxonomy**: 39 object classification categories
- **Chronological Framework**: 5 historical periods spanning Iron Age through Ottoman Period
- **Authorial Attribution**: 50 publication and research contributors
- **Relational Edges**: 883 documented connections and associations


## Repository Architecture

```
repository-root/
├── digitalsee-graph.html    # Primary visualization application
├── README.md                # Technical documentation
├── config.json              # Configuration reference
└── .gitignore               # Version control exclusions
```

## System Requirements

### Hardware Specifications
- **Memory**: Minimum 2GB RAM; 4GB+ recommended
- **Display**: Modern rendering capabilities supporting WebGL

### Software Requirements

The application has been tested on current-generation versions of major browser engines:

- Chromium/Chrome (latest)
- Mozilla Firefox (latest)
- Apple Safari (latest)
- Microsoft Edge (latest)

## Performance Characteristics

The visualization system exhibits the following computational properties:

- **Network Density**: Approximately 272 nodes with 883 edges
- **Initial Load Time**: 2-3 seconds to complete graph rendering and stabilization
- **Rendering Technology**: WebGL-accelerated visualization for optimal throughput
- **Query Responsiveness**: Sub-second response time for search and filter operations

## Extensibility and Configuration

### Visual Parameter Modification

Chromatic values within the node definition schema may be adjusted through direct manipulation of hexadecimal color codes (format: `"color": "#XXXXXX"`).

### Physics Engine Configuration

The underlying graph layout algorithm may be configured through the `physics` configuration object, enabling adjustment of gravitational constants, spring length parameters, and stabilization iterations.

### Dataset Expansion

Additional nodes and edges may be incorporated through modification of the `allNodes` and `allEdges` data structures within the primary HTML document.

## Constituent Research Collections

The integrated dataset synthesizes materials from the following specialized archives and research initiatives:

- **Digital Inscriptions (DI)**: Epigraphic database and analytical materials
- **Travel Accounts (IV)**: Historical narrative documentation and observational records
- **Schad Materials (MB)**: Eighteenth-century archival and survey documentation
- **Racheva Research (VR)**: Contemporary scholarly analysis and interpretive frameworks
- **Architectural Materials (KA)**: Structural and morphological analysis datasets

## License

See LICENSE file for details.

## Contact & Support

For questions about the DigitalSEE project, visit the project website or contact the research team.
