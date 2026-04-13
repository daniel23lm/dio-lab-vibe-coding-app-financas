# 💸 App de Organização de Finanças Pessoais com Vibe Coding

PRD revisao no Copilot Web

```markdown 

PRD Revisado - Aplicativo de Finanças Pessoais Interativo com Design Universal

Contexto

Criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas naturais com o usuário. O objetivo é simplificar o controle financeiro, eliminando a necessidade de formulários complexos ou planilhas.

Problema

Usuários desistem de controlar seus gastos porque os aplicativos atuais exigem muita entrada manual e oferecem pouca personalização. A solução proposta é uma experiência conversacional com recomendações automáticas de economia.

Público-Alvo

Pessoas que desejam iniciar o controle financeiro de forma prática.

Usuários iniciantes que buscam simplicidade e orientação.

Princípio de Design Universal

A solução deve ser construída com design universal, garantindo que o aplicativo ofereça uma experiência acessível e inclusiva para o maior número possível de usuários. Isso inclui:

Interfaces claras e intuitivas.

Compatibilidade com leitores de tela e recursos de acessibilidade.

Uso de linguagem simples e compreensível.

Flexibilidade para diferentes perfis de usuários, respeitando diversidade cultural e de necessidades.

Funcionalidades-Chave

Registro de gastos via chat em linguagem natural.

Classificação automática das transações.

Definição e acompanhamento de metas financeiras por meio de conversas.

Agente Financeiro que fornece dicas de economia personalizadas.

Relatórios simples e gráficos com extratos das transações.

Alertas por e-mail quando os gastos atingirem 90% da receita.

MVP - Plano de Entregável

Telas Principais

Tela de Conversa: interface central para registrar gastos e interagir com o Agente Financeiro.

Tela de Metas: acompanhamento das metas definidas.

Tela de Relatórios: gráficos simples e extratos.

Tela de Configurações: preferências de alertas e personalização.

Recursos Necessários

Processamento de linguagem natural para interpretar mensagens.

Motor de classificação automática de transações.

Sistema de notificações e envio de e-mails.

Módulo de geração de relatórios e gráficos.

Implementação de recursos de acessibilidade (design universal).

Validação Inicial

Testes com grupo piloto de usuários iniciantes.

Coleta de feedback sobre a experiência conversacional.

Avaliação da acessibilidade e inclusão.

Ajustes nas recomendações do Agente Financeiro.

Conceitos Explicados

O que é um PRD (Product Requirements Document)?

Um PRD é um documento que descreve os requisitos de um produto. Ele serve como guia para o time de desenvolvimento, garantindo que todos entendam:

O problema que o produto resolve.

O público-alvo.

As funcionalidades principais.

O que deve estar presente no MVP (Minimum Viable Product).

Em resumo, o PRD é o mapa que orienta a criação do produto.

O que é Vibe Coding?

Vibe Coding é uma prática que foca em criar experiências digitais de forma leve, criativa e colaborativa. Em vez de apenas escrever código, o objetivo é experimentar ideias rapidamente, testar interações e ajustar conforme o “vibe” do usuário. No contexto do Lovable, significa:

Prototipar de forma ágil.

Validar conceitos com usuários reais.

Criar soluções que sejam não só funcionais, mas também agradáveis e envolventes.

Síntese Didática

PRD: documento que organiza requisitos e funcionalidades de um produto.

Vibe Coding: abordagem criativa e iterativa para desenvolver experiências digitais.

Design Universal: princípio que garante acessibilidade e inclusão, ampliando o alcance e a usabilidade do produto.

Esse PRD revisado já está pronto para servir como base de desenvolvimento do MVP do aplicativo de finanças pessoais interativo, com foco em acessibilidade e experiência inclusiva.

```
Interações com o Lovable:

Poderia criar um aplicativo de finanças pessoais interativo com base no PRD (product requirements documents).

Ótimo, mas os lançamentos realizados no chat não foram incluídos (sincronizados) nas telas Metas e Relatórios. Além disso, tanto o chat quanto as telas Metas e Relatórios deveriam ter a opção de limpar (excluir) lançamentos, se possível, permitir selecionar cada lançamento que será excluído, também possibilite que as exclusões sejam solicitadas pelo chat. Consegue resolver isso, mantendo a estrutura do aplicativo?

Ok, ficou bom, mas a tela Metas ainda não está sincronizada com o chat e não tem a opção de exclusão seletiva. Gentileza realizar nova verificação e incluir a sincronização para que os comandos do chat para limpar tudo, excluir tudo e exclusão seletivas sejam realizados como na tela Relatórios na própria tela. Além disso quero que o chat assimile palavras similares para os comandos de gastos e receitas como exemplo comprei, paguei, saquei, depositei, investi, etc. Enfim, analise a palavra utiliza e classifique como despesas (débitos) e receitas (créditos)

Eu dei um comando "Investi 5000 em reserva de emergência" q mas a conta ResevateMetas consta as metas financeiras Reserva de Emergência, Viagem de Férias e Novo notebook que estão congelados, não foram alterados com os comandos no chat.

Incluir na tela Metas a opção de excluir todas as Metas Financeiras e também exclusão seletiva para cada Meta Financeira (Reserva de emergência, Viagem de Férias e Novo notebook). O botão "+ Nova meta” deve permitir incluir uma nova meta financeira, mas nao esta funcionando. Os lançamentos na tela Meta devem ser apenas referente as transações classificadas automaticamente como investimento, tanto entradas como saídas de recursos. Poderia fazer uma correção mais profunda para que esses erros não se repitam. 

Na tela Relatórios incluir o botão "Excluir todos" para exclusão de todos os lançamentos. As transações classificadas como investimento também devem ser lançados na tela de Relatórios. Na tela Metas as transações classificadas como investimento entram como positivas e soma a meta, já em relatórios entram nirmalmente como despesa, reduz a receita. Poderia verificar se os lançamentos estão corretos seguinte o modelo bancário.

Na tela Meta, gentileza incluir um botão Alteração em cada Meta Financeira, onde abre um formulário funcional igual ao formulário utilizado para criar nova meta.Verifique o funcionamento.

Ao ser iniciaado aplicativo, a tela Metas, vem com três Metas Financeiras (Reserva de emergência, Viagem de férias e Novo notebook) previamente preenchidas, entretanto há um bug, pois quando edito o formulário, campo valor arlvo, altera na meta financeira no item faltam R$ quando deveria alterar o valor inicial da meta financeira, ou seja, o campo alvo ele é somado

Ficou ótimo, agora para finalizar tanto na tela Metas quanto na tela Relatórios, gentileza iniciar o aplicativo sem nenhuma transação. Pode manter as três sugestões de Metas Financeiras, mas com os campo atual, meta (valor alvo) e faltam zerados para que o usuário possa preenchê-los. Proceda da mesma forma na tela Relatórios, iniciando com todos os campos (Receitas, Despesas, Saldo), inclusive Extrato Recente, pois todos serão preenchidos após lançamentos do usuário. Gentileza verificar o funcionamento correto após alteração na programação.

Revise os parâmetros de classificação e monetário das transações, pois registrei o recebimento de 10 mil reais de salário e foi registrado R$ 10,00 com classificação (outros) quando deveria ser registrado R$ 10.000,00 com classificaçao Renda ou Remuneração. Considere a escrita natural das pessoas que descrevem valores utiliando a forma numeral e por extenso juntas, como 1 mil reais, 1 milhão de reais, etc. Também considere as conjugações verbais pagar conta, pagamento de ao invés de paguei, gastei, etc para iniciar na interaçao do chat.

Verifique novamente a classificação das transações, pois informei que gastei 100 com camisa na loja Riachuello e foi classificado como outros, quando deveria ser roupas, vestuário, etc, uma vez que informei que a compra foi de uma camisa. Portanto, quero que considere o produto informado para determinar a classificação, evite ao máximo utilizar a classificação Outros. Corriga e verifique, por favor

nem sempre a loja Riachuello será classificado como Vestuário, pois vende produtos diversos, incluindo relógios, aparelho de celular, etc. Você pode classificar como loja de departamentos ou se for informado o produto categorizar conforme interaçao do usuário. São exemplos de lojas de departamento como Lojas Renner, Lojas Americanas, C&A, dentre outras.

site: https://financas-chat-interativo.lovable.app



- Seu **prompt final** (PRD);  
- Prints ou pequenos vídeos das interações com a IA;  
- Um resumo do que o seu **App de Finanças Pessoais** faz;  
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?  
  - O que não funcionou como o esperado?  
  - O que aprendeu sobre conversar com IAs?

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
