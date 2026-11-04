# PALM · Desenvolvimento com intenção
## Guia completo do método

Propósito · Ação · Limites · Melhoria

Um pequeno guia para transformar capacidade de geração em produtos com direção.

Método v0.1 · Novembro de 2026

---

## 01 / Desenvolvimento com intenção

Imagine que todo produto precisasse caber na palma da mão. A tela teria pouco espaço. A atenção do usuário seria disputada pelo ambiente. Cada campo adicional exigiria esforço. A aplicação precisaria ajudar alguém a terminar uma tarefa, mesmo longe de uma mesa.

Essa imagem orienta o PALM deste livro. A inspiração vem do raciocínio que associamos ao desenvolvimento para palmtops: começar pela tarefa, encurtar o caminho, respeitar os recursos disponíveis e testar no contexto real. Reviver esse pensamento significa recuperar uma disciplina de escolha.

O PALM apresentado aqui é uma proposta criada a partir dessa inspiração. O nome significa Propósito, Ação, Limites e Melhoria. Não estamos recuperando um método histórico oficialmente chamado PALM, nem afirmando que todo software de palmtop seguia os mesmos princípios.

Nossa proposta é aplicar essa disciplina a uma situação contemporânea: desenvolver com assistência de inteligência artificial. Quando gerar telas, funções e estruturas fica mais acessível, precisamos de critérios para decidir o que merece existir.

O **PALM** estabelece uma abordagem metodológica estruturada para o desenvolvimento de software assistido por inteligência artificial, integrando princípios de engenharia de software, práticas de validação e mecanismos de controle ao longo do ciclo de desenvolvimento. Sua proposta é elevar a previsibilidade, a consistência e a eficiência dos processos, reduzindo a complexidade desnecessária, o retrabalho e o desperdício de recursos computacionais. A metodologia foi concebida para ser aplicada, mensurada e continuamente aprimorada em cenários reais de engenharia de software.

### O percurso deste guia

Primeiro, vamos reconhecer o excesso. Depois, apresentar o ciclo PALM, aplicá-lo a um caso e transformá-lo em instruções para trabalhar com IA. Ao final, você terá um roteiro para experimentar no próximo projeto.

> A capacidade de construir abre possibilidades. O propósito orienta quais delas merecem se tornar produto.

---

## 02 / Quando uma tarefa vira uma plataforma

Chamamos de expansão desnecessária de escopo a inclusão de capacidades sem relação demonstrada com a necessidade atual. Ela pode aparecer como excesso de funcionalidades (feature creep) ou como complexidade de implementação desproporcional (overengineering). O PALM orienta decisões para reconhecer e controlar esse crescimento.

O tamanho do código, sozinho, não define esse excesso. Um sistema grande pode ser adequado a um problema complexo. Uma aplicação com poucas telas pode desperdiçar atenção se exigir configurações sem utilidade para quem a usa.

O sinal central é a distância entre a necessidade e o que foi construído. A pessoa quer registrar um pedido. O produto exige configurar um espaço de trabalho, escolher um plano, criar uma equipe, montar um painel e aprender um fluxo de automação antes de salvar o primeiro registro.

### A ampliação por possibilidades

Em um projeto assistido por IA, essa distância pode surgir por uma sequência de decisões aparentemente pequenas. Um pedido genérico de “sistema completo” produz uma lista ampla de recursos. Cada recurso sugere outro: contas pedem perfis; perfis sugerem permissões; permissões convidam a uma área de administração.

Nada disso é necessariamente inadequado. O problema aparece quando a justificativa se resume a “já que podemos, vamos incluir”. Uma possibilidade passa a funcionar como requisito sem que alguém tenha demonstrado sua necessidade.

### O custo permanece depois da geração

Mesmo quando a IA ajuda a escrever uma funcionalidade, alguém precisa compreendê-la, verificá-la, operá-la e modificá-la. Uma nova configuração precisa de explicação. Um novo dado exige uma decisão de acesso e retenção. Uma integração precisa de resposta quando falhar.

O PALM propõe revisar essas obrigações antes de aceitar a expansão. A pergunta passa a ser: qual resultado justifica acrescentar essa responsabilidade ao produto?

> Construir uma funcionalidade também é assumir sua vida depois da entrega.

---

## 03 / O que muda no PALM

A inspiração do palmtop traz a ideia de trabalhar com restrições concretas. O PALM amplia o conjunto de restrições e transforma essa atenção em um ciclo explícito de desenvolvimento.

### Do espaço da tela ao espaço da atenção

Além de caber em um dispositivo, o fluxo precisa caber no contexto da pessoa. Um vendedor em visita, uma profissional entre atendimentos e alguém usando leitor de tela têm condições diferentes. A solução precisa considerar como essas pessoas percebem estados, tomam decisões e corrigem erros.

### Dos recursos do aparelho ao custo do sistema

Memória e processamento continuam relevantes quando limitam o uso. Somam-se a eles conexão, serviços externos, privacidade, manutenção e, quando houver IA no produto, custo por uso e variabilidade das respostas.

### Da primeira entrega ao aprendizado contínuo

Uma versão funcional permite observar o que acontece. O ciclo volta ao propósito quando o uso contradiz a hipótese inicial. Algumas melhorias acrescentam recursos; outras removem campos, consolidam telas ou encerram uma integração.

### Quatro compromissos

**P / Propósito.** Tornar explícito quem precisa de ajuda e qual resultado espera.

**A / Ação.** Construir o menor caminho completo para esse resultado.

**L / Limites.** Definir condições de uso, qualidade e operação que a solução precisa respeitar.

**M / Melhoria.** Observar a experiência e escolher mudanças a partir de evidências.

Esses compromissos podem trazer mais clareza para decisões de escopo e revisão. Seu efeito depende da qualidade das perguntas, da execução e do contato com usuários. A sigla, sozinha, não resolve um projeto.

> Propósito → Ação → Limites → Melhoria → novo ciclo.

---

## 04 / Propósito e Ação: dar direção à IA

### P / Escreva a necessidade antes do pedido

Antes de solicitar uma implementação, complete uma frase: “Para esta pessoa, nesta situação, precisamos permitir esta tarefa para alcançar este resultado”. Acrescente uma forma de observar o sucesso e declare o que fica fora desta versão.

Um propósito concreto seria: “Permitir que uma profissional autônoma registre seus atendimentos e identifique quais ainda não foram pagos”. Isso permite discutir um fluxo. “Criar uma plataforma inteligente de gestão” deixa abertas decisões demais.

O propósito também ajuda a responder a sugestões da IA. Se ela propuser um módulo de marketing, a equipe pode perguntar qual obstáculo da tarefa esse módulo remove. Uma boa ideia pode ser registrada para outro momento sem entrar automaticamente na entrega atual.

### A / Desenhe uma experiência completa

Para o exemplo dos atendimentos, um fluxo inicial seria: registrar atendimento, informar valor e situação do pagamento, salvar e consultar pendências. Faça o percurso existir de ponta a ponta antes de ampliar as áreas do produto.

“Completo” inclui o que acontece quando a pessoa erra, interrompe ou repete uma ação. É possível corrigir o valor? O registro continua disponível depois de fechar a aplicação? A confirmação deixa claro que o salvamento ocorreu?

Um caminho curto também pode precisar de etapas de proteção. A confirmação de uma exclusão irreversível ou uma verificação de acesso pode ser necessária. O objetivo é reduzir esforço desnecessário enquanto preserva o resultado e a confiança.

### A entrega desta etapa

Produza uma frase de propósito, um desenho do fluxo e exemplos do que significa concluir a tarefa. Peça à IA que aponte ambiguidades antes de implementar. Decida as questões que mudam o comportamento esperado e registre as hipóteses restantes.

> Um pedido delimitado permite avaliar a resposta com critérios que já existiam antes dela.

---

## 05 / Limites e Melhoria: sustentar a simplicidade

### L / Defina o que a solução precisa suportar

Limites são decisões de produto. Se o uso ocorre com conexão instável, é preciso decidir como salvar, informar pendências e recuperar falhas. Se há dados pessoais, é preciso definir quais são necessários e quem pode acessá-los.

Faça perguntas concretas: quais dispositivos serão usados? Como a tarefa funciona com teclado? Como a pessoa recupera um registro? Que volume e custo são aceitáveis? Quem vai cuidar da aplicação depois da entrega?

Quando houver IA dentro do produto, acrescente outras decisões: quais entradas podem ser enviadas ao serviço? Como revisar uma sugestão? Qual comportamento é aceitável se a resposta vier errada ou não chegar? Um fluxo alternativo pode ser necessário para manter a tarefa disponível.

Para cada limite relevante, registre uma verificação. “Não perder um atendimento ao reabrir a aplicação” pede um teste de persistência. “Usável com teclado” pede percorrer o fluxo sem mouse. Escale a profundidade da verificação conforme o risco.

### M / Observe antes de ampliar

Entregue o fluxo a pessoas representativas e observe onde hesitam, abandonam ou precisam de ajuda. Conte tarefas concluídas e erros relevantes. O número de telas entregues ou de linhas geradas não informa se a necessidade foi resolvida.

Se há dificuldade para encontrar pendências, investigue nomes, ordenação e visibilidade antes de acrescentar um painel. A causa pode ser simples. Se a dificuldade exige uma capacidade nova, formule uma hipótese e teste essa mudança.

### Uma decisão por ciclo

Registre: “Observamos este problema; acreditamos que esta mudança ajudará; vamos verificar desta forma”. Depois, compare o uso com o resultado esperado. Mantenha, revise ou remova a alteração conforme o que aprender.

O PALM admite crescimento. Cada expansão precisa de uma razão compreensível e de uma forma de verificar se valeu a pena.

---

## 06 / Um caso: do pedido genérico à primeira versão

Considere a profissional autônoma que quer acompanhar atendimentos e pagamentos. O caso abaixo é ilustrativo; não representa um estudo de resultados.

### O pedido aberto

“Crie um sistema completo para gerenciar meu negócio, com IA e um visual profissional.”

Esse pedido permite muitas interpretações. Uma resposta possível incluiria painel de indicadores, CRM, agenda, campanhas, equipe, assinaturas, relatórios e assistente de chat. Parte disso poderá fazer sentido no futuro, mas ainda falta saber qual necessidade é prioritária.

### A primeira versão orientada pelo PALM

**Propósito:** registrar atendimentos e reconhecer pagamentos pendentes.

**Ação:** criar registro, informar valor, marcar pagamento e consultar a lista. Permitir editar erros e localizar registros anteriores.

**Limites:** usar no celular; preservar dados entre sessões; definir acesso e recuperação; tornar o estado do salvamento claro; coletar somente os dados necessários. Se houver mais de um dispositivo ou usuário, decidir como acesso e sincronização funcionarão antes de escolher o armazenamento.

**Melhoria:** observar se a profissional registra e encontra pendências sem ajuda. Investigar campos confusos e operações repetidas.

### O que fica para depois

Marketing, gestão de equipe e chat com IA ficam fora desta versão por falta de necessidade demonstrada. A IA pode continuar ajudando a desenvolver, revisar e verificar o produto sem aparecer como funcionalidade para a usuária.

Se o uso mostrar que a profissional perde tempo repetindo cobranças, pode fazer sentido testar uma ajuda para redigir mensagens. Antes de automatizar o envio, será preciso decidir revisão, destinatários e autorização. O próximo recurso nasce de um problema observado e traz seus próprios limites.

> A primeira versão cria uma base para aprender sem assumir, de saída, todas as necessidades futuras do negócio.

---

## 07 / Como conversar com a IA usando PALM

Uma instrução útil combina contexto, escopo, limites e critérios de conclusão. O objetivo é dar à IA uma referência para propor e executar mudanças que você consiga avaliar.

### Um pedido reutilizável

“Vamos desenvolver usando PALM.

Propósito: [quem precisa, em qual contexto e qual resultado espera].

Ação: [fluxo principal e correções necessárias].

Limites: [dispositivos, acessibilidade, dados, conexão, custo e restrições relevantes].

Melhoria: [como verificaremos a conclusão e o que observaremos no uso].

Implemente uma primeira versão completa desse fluxo. Recursos adicionais ficam fora do escopo até serem justificados. Antes de implementar, identifique dúvidas que alterem o comportamento esperado. Para decisões pequenas e reversíveis, adote uma opção simples e registre a hipótese.

Ao concluir, explique o que mudou, como foi verificado, quais limitações permanecem e quais responsabilidades de manutenção foram acrescentadas.”

### Pedidos para revisar o excesso

Depois da primeira versão, peça: “Relacione as funcionalidades implementadas ao propósito. Aponte as que não têm relação clara com ele e descreva o impacto de removê-las”.

Para avaliar estrutura: “Explique por que cada dependência e serviço é necessário ao fluxo atual. Proponha simplificações com seus efeitos e riscos”. Essas perguntas ajudam a revisar; não tornam a resposta da IA uma prova de que a solução está correta.

### Autonomia com escopo

A equipe pode autorizar a IA a executar decisões pequenas dentro de um fluxo aprovado e reservar decisões que mudem escopo, acesso a dados ou compromissos externos para avaliação explícita. Isso evita pedir confirmação a cada detalhe e mantém visíveis as escolhas de maior consequência.

> A IA recebe espaço para executar quando o resultado e os limites estão claros.

---

## 08 / Como reconhecer uma melhoria de verdade

O PALM pretende tornar o desenvolvimento mais deliberado. Para saber se isso ocorreu, compare o produto com o problema que motivou sua criação e observe o uso. Uma aplicação menor pode continuar confusa; uma aplicação ampliada pode resolver uma necessidade que antes ficava descoberta.

### Observe resultado, esforço e responsabilidade

**Resultado:** a pessoa consegue concluir a tarefa? O registro está correto e disponível quando necessário?

**Esforço:** quanto tempo, quantas tentativas e quanta ajuda a tarefa exige? Quais escolhas geram dúvida?

**Responsabilidade:** a equipe entende a solução? Consegue corrigir falhas, recuperar dados e sustentar os custos e serviços adotados?

Escolha poucas medidas coerentes com o contexto. Uma primeira rodada de observação pode revelar problemas, mas não sustenta promessas gerais de produtividade. Evite percentuais de melhoria sem dados e comparações adequadas.

### Quando crescer é a decisão certa

Uma segunda pessoa pode exigir permissões. Um novo contexto pode exigir sincronização. Obrigações reais podem exigir registros de auditoria. Nesses casos, simplificar significa organizar a complexidade necessária e tornar o uso compreensível.

O método perde seu sentido se “evitar excesso” servir de justificativa para omitir segurança, acessibilidade ou recuperação de falhas. Esses requisitos fazem parte da qualidade da tarefa quando o contexto os exige.

### Uma pergunta para cada expansão

“Qual problema observado esta mudança resolve, que custo ela acrescenta e como saberemos se funcionou?” Se a resposta ainda não estiver clara, investigue antes de incluir a funcionalidade no próximo ciclo.

> Crescer com uma razão explícita torna o produto mais fácil de discutir, revisar e sustentar.

---

## 09 / Seu próximo projeto em uma página

Escolha uma tarefa real e preencha o roteiro abaixo. Use respostas curtas e concretas. Revise o roteiro conforme aprender; ele deve orientar decisões durante o trabalho.

### P / Propósito

Quem precisa de ajuda? Em qual situação? Qual tarefa deve conseguir concluir? O que observará para reconhecer o sucesso? O que ficará fora desta versão?

### A / Ação

Qual é o início e o fim do fluxo? Que decisões são necessárias? Como corrigir um erro? Como o usuário sabe que terminou?

### L / Limites

Onde e em quais dispositivos isso será usado? Que dados são necessários? Como acesso, falhas e recuperação funcionarão? Quais critérios de qualidade e custo precisam ser respeitados? Como serão verificados?

### M / Melhoria

Quem experimentará a versão? O que você observará? Que evidência justificará uma mudança? O que poderá ser removido se não trouxer valor?

### Antes de ampliar

Confirme que o fluxo funciona de ponta a ponta, que o resultado está claro para o usuário e que as falhas relevantes têm uma resposta. Registre as limitações conhecidas. Escolha a próxima mudança pelo que aprendeu.

### O compromisso do PALM

Reviver a inspiração do palmtop é recuperar a atenção ao que uma pessoa precisa fazer em condições concretas. Com IA, essa atenção pode orientar pedidos melhores, entregas mais delimitadas e revisões mais criteriosas.

Comece por uma tarefa que importa. Construa um caminho completo. Respeite os limites do contexto. Observe o uso e decida o próximo passo. É esse ciclo que propomos levar para o desenvolvimento assistido por IA.

---

## 10 / Três mecanismos de controle

### Contrato de escopo

Registre antes de implementar: pessoa, tarefa, resultado, dentro e fora do escopo, requisitos de qualidade e verificações. Esse registro dá uma referência comum à equipe e à IA. Atualize-o quando uma decisão mudar o escopo; preserve o motivo da mudança.

### Justificativa para adições

Cada nova funcionalidade, dependência ou serviço precisa de uma razão ligada ao resultado atual. Registre a evidência da necessidade, por que agir agora, a alternativa mais simples, a consequência de adiar e os custos de construir, verificar e manter. Decida incluir, adiar ou investigar.

Uma sugestão da IA é uma proposta a avaliar. Uma escolha pequena dentro do escopo pode ser executada autonomamente; mudanças que criam novas responsabilidades precisam de uma decisão explícita. O objetivo é manter decisões relevantes visíveis sem interromper o trabalho a cada detalhe.

### Critério de parada

Encerre a implementação do ciclo quando a tarefa e seus critérios estiverem atendidos. Registre limitações e passe à observação. A existência de mais ideias não impede uma entrega de estar concluída. Se uma verificação falhar, corrija a falha antes de declarar conclusão.

### Registro de decisão

Adição proposta: o que muda? Necessidade: qual evidência a sustenta? Alternativa: qual opção mais simples atende? Responsabilidade: o que será necessário operar e manter? Verificação: como reconhecer o benefício? Decisão: quem decidiu e em qual contexto? Reavaliação: o que justificará rever a escolha?

---

## 11 / Recursos computacionais e qualidade

O escopo também afeta processamento, armazenamento e chamadas a serviços. Antes de adicionar um processamento recorrente ou um modelo de IA, identifique a tarefa atendida, a frequência necessária e como observar o custo por tarefa concluída.

No desenvolvimento assistido, forneça contexto relevante, descreva critérios de conclusão e peça mudanças delimitadas. Quando uma tentativa falhar, investigue o resultado antes de repetir a mesma geração. Registre verificações e decisões para evitar reconstruir contexto já resolvido.

No produto, avalie se uma regra determinística atende à tarefa antes de adotar geração probabilística. Quando a IA for adequada, defina revisão, limites de uso, tratamento de erros e proteção dos dados. Cache, processamento em lote e modelos menores são opções a avaliar conforme qualidade, privacidade e atualização necessárias.

Observe consumo e custo junto com qualidade. Menos chamadas não representam melhoria se o usuário precisar repetir a tarefa ou se a solução perder confiabilidade. Compare cenários equivalentes e registre efeitos sobre tempo de resposta, erros, custo e experiência.

---

## 12 / Referências e próximos passos

PALM significa Propósito, Ação, Limites e Melhoria nesta proposta. A organização do ciclo e dos instrumentos foi desenvolvida neste projeto com assistência de IA, apoiando-se nas referências abaixo.

### Zen of Palm

Filosofia de design que inspira foco, simplicidade e atenção ao contexto de uso. Documento preservado pela Universidade de Massachusetts Lowell: https://www.cs.uml.edu/~fredm/courses/91.308-fall05/palm/zenofpalm.pdf

### Manifesto Ágil · Princípios

Referência para software funcionando, simplicidade e reflexão regular sobre o processo. Fonte: https://agilemanifesto.org/principles.html

### Martin Fowler · Yagni

Referência para evitar capacidades presumidas e considerar o custo de carregar funcionalidades. Artigo de 2015: https://martinfowler.com/bliki/Yagni.html

### Ryan Singer · Shape Up

O capítulo Set Boundaries orienta delimitação do problema e do investimento. Fonte: https://basecamp.com/shapeup/1.2-chapter-03

### Aplicação e contribuição

Use o guia de prompt, preencha o roteiro e registre uma decisão de escopo. Compartilhe contexto, resultados e dificuldades no repositório. Projeto: https://github.com/Willianjesusdasilva/palm-method

Projeto independente, sem afiliação com Palm/PalmSource ou com o Pedigreed Attribute eLicitation Method do SEI. Os exemplos deste guia são ilustrativos. As referências permanecem atribuídas a seus autores.
