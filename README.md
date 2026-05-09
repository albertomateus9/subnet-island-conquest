# Conquista das Ilhas de Sub-redes

Jogo de sub-redes em que equipes conquistam ilhas ao distribuir faixas IP, VLANs e rotas sem sobreposição.

> Projeto educacional inspirado na EETEPA Vilhena Alves. Não é sistema oficial institucional e não usa dados reais de estudantes.

## Visão Geral

**Código:** L-03  
**Foco disciplinar:** Redes, Lógica e Planejamento de Infraestrutura  
**Formato:** jogo web conduzido pelo professor  
**Tempo sugerido:** 25 a 35 minutos  
**Demonstração pública:** https://albertomateus9.github.io/subnet-island-conquest/

Este projeto transforma uma aula técnica em uma missão guiada. O professor cria equipes fictícias, inicia o cronômetro, revela fases, pontua evidências e exporta relatório da aula.

## Roteiro Do Professor

- **Objetivo:** Treinar endereçamento IP como uma disputa por territórios bem planejados.
- **Preparação:** Mostre um exemplo simples de CIDR e combine que sobreposição perde pontos.
- **Condução:** Peça que cada equipe defenda sua escolha de faixa antes de avançar.
- **Fechamento:** Compare desperdício, capacidade e organização das tabelas propostas.
- **Critérios:** use a rubrica do app para pontuar evidência, colaboração, comunicação e melhoria.

## Missões

- **Conquistar a Ilha Base (7 min):** Escolher um bloco CIDR que suporte 30 hosts sem desperdiçar espaço demais. Evidência: Escolha CIDR e quantidade de hosts utilizáveis.
- **Construir Pontes VLAN (8 min):** Atribuir VLAN e faixa de rede para cada ilha sem sobreposição. Evidência: Tabela de VLANs.
- **Abrir a Rota Segura (9 min):** Encontrar a sobreposição e propor uma sub-rede corrigida. Evidência: Tabela de planejamento IP corrigida.

## Competências

- planejamento IP
- raciocínio lógico
- estimativa de capacidade
- documentação de rede

## Como Rodar

Abra `index.html` diretamente ou sirva a pasta:

```bash
python -m http.server 8000
```

Depois abra `http://localhost:8000`.

## Política De Dados

- Usa apenas missões sintéticas e equipes fictícias.
- Guarda estado apenas no `localStorage` do navegador.
- Não possui login, servidor, API externa ou registro real de estudante.

## Licença

MIT. Consulte [LICENSE](LICENSE).
