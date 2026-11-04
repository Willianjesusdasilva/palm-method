<p align="center"><img src="assets/palm-logo.png" alt="palm — marca tipográfica verde-lima sobre preto" width="640"></p>

# PALM · Desenvolvimento com intenção

**Dê à IA um propósito. Dê ao produto um limite.**

Um método aberto e experimental para desenvolver com IA e controlar a expansão desnecessária de escopo.

[Explore o site](https://willianjesusdasilva.github.io/palm-method/) · [Use com sua IA](PROMPT.md) · [Preencha o roteiro](templates/palm.md) · [Veja um exemplo](examples/atendimentos.md)

> Versão 0.1.0 · Proposta em validação · Sem promessas de ganhos comprovados

## O problema

Você pede um cadastro. A entrega vira uma plataforma: painel, equipes, permissões complexas, automações e integrações. Cada adição pode ser útil; cada uma também precisa de uma justificativa.

Chamamos de **expansão desnecessária de escopo** a inclusão de capacidades sem relação demonstrada com a necessidade atual. Ela pode se manifestar como excesso de funcionalidades (*feature creep*) ou complexidade de implementação desproporcional (*overengineering*). Esses fenômenos não começaram com a IA. Nossa hipótese é que a facilidade de gerar soluções torna ainda mais importante revisar o que entra no produto.

## O ciclo

| Etapa | Pergunta | Resultado verificável |
|---|---|---|
| **P · Propósito** | Quem precisa concluir qual tarefa? | Necessidade, critério de sucesso e fora de escopo |
| **A · Ação** | Qual caminho completo entrega esse resultado? | Fluxo com correção de erros e estados compreensíveis |
| **L · Limites** | Quais condições a solução precisa respeitar? | Critérios de qualidade, dados, custo e operação |
| **M · Melhoria** | O uso justifica a próxima mudança? | Observação, hipótese e decisão de manter, revisar ou remover |

## Comece agora

1. Copie [PROMPT.md](PROMPT.md) para a IA ou forneça seu endereço, se ela conseguir ler links.
2. Preencha [o roteiro PALM](templates/palm.md) com uma tarefa real.
3. Peça uma primeira entrega de ponta a ponta.
4. Revise cada adição com o registro de decisão abaixo.
5. Observe pessoas usando e registre o próximo aprendizado.

## Três mecanismos para trabalhar com IA

**1. Contrato de escopo.** Antes de implementar, registre o resultado, o que entra, o que fica de fora e como verificar a conclusão. Hipóteses devem ser identificadas.

**2. Justificativa para adições.** Para cada nova funcionalidade, dependência ou serviço, responda: qual necessidade atende, por que agora, qual alternativa mais simples foi considerada, qual responsabilidade acrescenta e como será verificado? [Modelo de decisão](templates/decisao.md).

**3. Critério de parada.** Encerre o ciclo quando o fluxo e os critérios acordados estiverem atendidos. Sugestões adicionais voltam para avaliação; não entram automaticamente na implementação.

Segurança, acessibilidade e recuperação de falhas necessárias ao contexto fazem parte do escopo. Reduzir funcionalidades não autoriza reduzir qualidade essencial.

## Como avaliar a hipótese

Registre tempo para concluir a tarefa, erros, pedidos de ajuda, custo de operação e esforço de manutenção antes e depois. Documente participantes, contexto e alterações. Relate resultados negativos também. Linhas geradas e número de telas não demonstram valor. Veja [o protocolo de piloto](docs/piloto.md).

## Origem e referências

PALM significa **Propósito, Ação, Limites e Melhoria** nesta proposta. A organização do ciclo e dos instrumentos foi desenvolvida neste projeto com assistência de IA; não alegamos ineditismo dos princípios ou validação científica.

- **Zen of Palm**: inspiração histórica de foco e simplicidade no design de aplicações portáteis. [Documento preservado pela UMass Lowell](https://www.cs.uml.edu/~fredm/courses/91.308-fall05/palm/zenofpalm.pdf).
- **Manifesto Ágil, princípios (2001)**: software funcionando, simplicidade e reflexão regular. [Fonte original](https://agilemanifesto.org/principles.html).
- **Martin Fowler, Yagni (2015)**: evitar capacidades presumidas e considerar seu custo de manutenção. [Artigo](https://martinfowler.com/bliki/Yagni.html).
- **Ryan Singer, Shape Up, Set Boundaries**: delimitar o problema e o investimento antes de expandir a solução. [Capítulo](https://basecamp.com/shapeup/1.2-chapter-03).

Essas fontes fundamentam os princípios; não validam os resultados deste método com IA. Não há afiliação, patrocínio ou continuidade oficial com Palm/PalmSource. Existe também o **Pedigreed Attribute eLicitation Method**, outro PALM voltado a objetivos e arquitetura, descrito pelo [SEI](https://www.sei.cmu.edu/blog/reducing-project-failures-by-aligning-acquisition-strategy-and-software-architecture-with-stakeholder-needs-first-in-a-series/). Este projeto é independente dele.

## Contribua

Experimente em uma tarefa e abra uma issue com contexto, decisões, resultado e limitações. [Como contribuir](CONTRIBUTING.md) · [Identidade visual](docs/brand.md) · [Material de lançamento](launch/linkedin.md).

Mantido por [Willianjesusdasilva](https://github.com/Willianjesusdasilva). Licença MIT para o material original deste repositório. Fontes externas mantêm suas próprias condições.
