# 💸 App de Organização de Finanças Pessoais com Vibe Coding

## PRD Revisão no Copilot Web

```markdown

### PRD Revisado - Aplicativo de Finanças Pessoais Interativo com Design Universal

#### Contexto
Criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas naturais com o usuário.  
O objetivo é simplificar o controle financeiro, eliminando a necessidade de formulários complexos ou planilhas.

#### Problema
Usuários desistem de controlar seus gastos porque os aplicativos atuais exigem muita entrada manual e oferecem pouca personalização.  
A solução proposta é uma experiência conversacional com recomendações automáticas de economia.

#### Público-Alvo
- Pessoas que desejam iniciar o controle financeiro de forma prática.  
- Usuários iniciantes que buscam simplicidade e orientação.

#### Princípio de Design Universal
A solução deve ser construída com design universal, garantindo que o aplicativo ofereça uma experiência acessível e inclusiva para o maior número possível de usuários. Isso inclui:
- Interfaces claras e intuitivas.  
- Compatibilidade com leitores de tela e recursos de acessibilidade.  
- Uso de linguagem simples e compreensível.  
- Flexibilidade para diferentes perfis de usuários, respeitando diversidade cultural e de necessidades.  

#### Funcionalidades-Chave
- Registro de gastos via chat em linguagem natural.  
- Classificação automática das transações.  
- Definição e acompanhamento de metas financeiras por meio de conversas.  
- Agente Financeiro que fornece dicas de economia personalizadas.  
- Relatórios simples e gráficos com extratos das transações.  
- Alertas por e-mail quando os gastos atingirem 90% da receita.  

#### MVP - Plano de Entregável
**Telas Principais**
- Tela de Conversa: interface central para registrar gastos e interagir com o Agente Financeiro.  
- Tela de Metas: acompanhamento das metas definidas.  
- Tela de Relatórios: gráficos simples e extratos.  
- Tela de Configurações: preferências de alertas e personalização.  

**Recursos Necessários**
- Processamento de linguagem natural para interpretar mensagens.  
- Motor de classificação automática de transações.  
- Sistema de notificações e envio de e-mails.  
- Módulo de geração de relatórios e gráficos.  
- Implementação de recursos de acessibilidade (design universal).  

**Validação Inicial**
- Testes com grupo piloto de usuários iniciantes.  
- Coleta de feedback sobre a experiência conversacional.  
- Avaliação da acessibilidade e inclusão.  
- Ajustes nas recomendações do Agente Financeiro.  

---

### Conceitos Explicados

#### O que é um PRD (Product Requirements Document)?
Um PRD é um documento que descreve os requisitos de um produto. Ele serve como guia para o time de desenvolvimento, garantindo que todos entendam:
- O problema que o produto resolve.  
- O público-alvo.  
- As funcionalidades principais.  
- O que deve estar presente no MVP (Minimum Viable Product).  

Em resumo, o PRD é o mapa que orienta a criação do produto.

#### O que é Vibe Coding?
Vibe Coding é uma prática que foca em criar experiências digitais de forma leve, criativa e colaborativa.  
Em vez de apenas escrever código, o objetivo é experimentar ideias rapidamente, testar interações e ajustar conforme o “vibe” do usuário.  

No contexto do Lovable, significa:
- Prototipar de forma ágil.  
- Validar conceitos com usuários reais.  
- Criar soluções que sejam não só funcionais, mas também agradáveis e envolventes.  

#### Síntese Didática
- **PRD**: documento que organiza requisitos e funcionalidades de um produto.  
- **Vibe Coding**: abordagem criativa e iterativa para desenvolver experiências digitais.  
- **Design Universal**: princípio que garante acessibilidade e inclusão, ampliando o alcance e a usabilidade do produto.  

Esse PRD revisado já está pronto para servir como base de desenvolvimento do MVP do aplicativo de finanças pessoais interativo, com foco em acessibilidade e experiência inclusiva.
---
```
## Resumo das Interações com o Lovable

### Contexto
Foi solicitado ao Lovable a criação de um aplicativo de finanças pessoais interativo com base em um PRD.  
O objetivo era validar a experiência conversacional e garantir sincronização entre chat, metas e relatórios.

### Principais Ajustes e Correções

#### Sincronização
- Inicialmente, os lançamentos feitos no chat não eram refletidos nas telas de **Metas** e **Relatórios**.  
- Inclusão de exclusão seletiva e total de lançamentos.  
- Chat passou a assimilar palavras similares para comandos de gastos e receitas (*comprei, paguei, saquei, depositei, investi*).  

#### Tela Metas
- Correção de metas congeladas (Reserva de Emergência, Viagem de Férias, Novo Notebook).  
- Inclusão de botões: **Excluir todas**, **+ Nova Meta** funcional e **Alteração** para edição.  
- Correção do bug no campo **valor alvo**.  
- Ajuste para transações de investimento:  
  - Em **Metas**: somadas como positivas.  
  - Em **Relatórios**: lançadas como despesas.  

#### Tela Relatórios
- Inclusão do botão **Excluir todos**.  
- Transações de investimento passaram a ser registradas.  
- Aplicativo inicia sem transações, com campos zerados (Receitas, Despesas, Saldo, Extrato Recente).  

#### Classificação de Transações
- Correção de valores monetários (ex.: “10 mil reais” → R$ 10.000,00).  
- Consideração de escrita natural e conjugações verbais.  
- Classificação mais precisa dos produtos informados (ex.: “camisa” → Vestuário).  
- Ajuste para lojas de departamento: classificação depende do produto informado.  

### Resultado
- Aplicativo inicia sem transações, mas com sugestões de metas zeradas.  
- Chat e telas sincronizados.  
- Inclusão de exclusões seletivas e totais.  
- Classificação de transações mais precisa.  
- Correção de bugs nos formulários e valores monetários.  

### Aprendizado
- Importância da sincronização entre chat e telas.  
- Flexibilidade linguística para interpretar comandos naturais.  
- Design universal e acessibilidade.  
- Classificação contextual para evitar categorias genéricas.  

---

## Resumo do Site Finanças Chat Interativo

### Visão Geral
- **Nome:** FinChat – Seu Assistente Financeiro  
- **Plataforma:** Lovable (no-code, AI-driven)  
- **Objetivo:** Facilitar o controle de finanças pessoais por meio de conversas naturais, sem formulários complexos.  

### Funcionalidades Principais
- **Chat:** Registro de gastos em linguagem natural.  
- **Metas:** Definição e acompanhamento de objetivos financeiros.  
- **Relatórios:** Visualização de gráficos e extratos personalizados.  
- **Ajustes:** Configurações de preferências e alertas.  

### Estrutura de Navegação
- Chat  
- Metas  
- Relatórios  
- Ajustes  

### Experiência
- Interface simples e direta, baseada em design universal para acessibilidade.  
- Interações naturais com o “Agente Financeiro”.  
- Possibilidade de receber alertas quando os gastos atingem limites pré-definidos.  

---

## Considerações Finais
O **App de Finanças Pessoais Interativo com Vibe Coding** realiza:
1. Registro de transações dos usuários por chat interativo, com dicas financeiras.  
2. Alocação automática das transações em **Metas** e **Relatórios**, com gráficos percentuais.  
3. Sincronização entre tela **Metas** e chat.  
4. Menu de ajustes para configuração
