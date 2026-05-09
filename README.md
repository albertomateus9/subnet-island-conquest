# Subnet Island Conquest

CIDR and VLSM classroom game where teams conquer islands by allocating safe network ranges and VLANs.

> Educational project inspired by EETEPA Vilhena Alves. It is not an official institutional system and does not use real student data.

## Overview

**Code:** L-03  
**Discipline focus:** Networks, Logic, and Infrastructure Planning  
**Format:** Teacher-led classroom web game  
**Suggested duration:** 25 to 35 minutes  
**Public demo:** https://albertomateus9.github.io/subnet-island-conquest/

This project turns a technical lesson into a guided mission. The teacher creates fictional teams, starts a timer, reveals mission phases, scores evidence and exports a classroom report.

## Classroom Flow

- **Claim The Base Island:** Choose a CIDR block that supports 30 hosts without wasting too much space.
- **Build The VLAN Bridges:** Assign a VLAN and network range to each island without overlap.
- **Open The Safe Route:** Find the overlap and propose a corrected subnet.

## Competencies

- IP planning
- logical reasoning
- capacity estimation
- network documentation

## Run Locally

Open `index.html` directly or serve the folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Data Policy

- Uses synthetic missions and fictional teams only.
- Stores state only in browser `localStorage`.
- Has no login, backend, external API or real student record.

---

# Subnet Island Conquest

CIDR and VLSM classroom game where teams conquer islands by allocating safe network ranges and VLANs.

> Projeto educacional inspirado na EETEPA Vilhena Alves. Nao e sistema oficial institucional e nao usa dados reais de estudantes.

## Visao Geral

**Codigo:** L-03  
**Foco disciplinar:** Redes, Logica e Planejamento de Infraestrutura  
**Formato:** jogo web conduzido pelo professor  
**Tempo sugerido:** 25 a 35 minutos  
**Demo publica:** https://albertomateus9.github.io/subnet-island-conquest/

Este projeto transforma uma aula tecnica em uma missao guiada. O professor cria equipes ficticias, inicia cronometro, revela fases, pontua evidencias e exporta um relatorio da aula.

## Dinamica De Aula

- **Claim The Base Island:** Choose a CIDR block that supports 30 hosts without wasting too much space.
- **Build The VLAN Bridges:** Assign a VLAN and network range to each island without overlap.
- **Open The Safe Route:** Find the overlap and propose a corrected subnet.

## Competencias

- IP planning
- logical reasoning
- capacity estimation
- network documentation

## Como Rodar

Abra `index.html` diretamente ou sirva a pasta:

```bash
python -m http.server 8000
```

Depois abra `http://localhost:8000`.

## Politica De Dados

- Usa apenas missoes sinteticas e equipes ficticias.
- Guarda estado apenas no `localStorage` do navegador.
- Nao possui login, backend, API externa ou registro real de estudante.

## License

MIT. See [LICENSE](LICENSE).
