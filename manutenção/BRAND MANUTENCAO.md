![BRAND MANUTENCAO](https://i.imgur.com/dh83aOy.png)


# Sistema de Alocação de Professores - Escola do Futuro

## Contextualização
**Assistente Técnico da Coordenação (Neto)** - Responsável pelo suporte à coordenação e gerenciamento dos cursos técnicos regulares da Escola do Futuro. Entre suas inúmeras atividades está a **escalação de professores**, verificando disponibilidade para lecionar aulas nos cursos técnicos e de capacitação.

## Processo Original e Problemática
O processo **demandava muito tempo** por ser realizado manualmente. Para otimizar esta atividade, foi proposto um **Sistema de Alocação**.

## Sistema Proposto
Neto solicita a professores qualificados que preencham uma **grade de horários**, selecionando:
-   Dias/horários **disponíveis**
-   Dias/horários **indisponíveis**
-   Horários **ministrando aula no Bittencourt**
Após o preenchimento, o sistema **calcula automaticamente as horas** de cada professor.

## Bugs e Melhorias Necessárias

### Correção (Bug Crítico)
-   **Problema**: O sistema exporta arquivos CSV mesmo sem dados válidos (ex.: quando o professor não seleciona nada na grade).
-   **Ação Necessária**: Correção da lógica de exportação para gerar arquivo apenas com dados preenchidos.

### Melhorias de Experiência (UX)
1.  **Interface Modo Noturno**: Adicionar opção de tema escuro para reduzir fadiga visual e melhorar usabilidade.
2.  **Legenda na Grade de Horários**:
    -   **Local**: Parte inferior da grade.
    -   **Texto**: `Dois cliques para ministrar aula no Bittencourt.`
    -   **Objetivo**: Instrução clara para o preenchimento correto.
