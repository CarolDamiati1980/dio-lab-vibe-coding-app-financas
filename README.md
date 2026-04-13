### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

- Seu **prompt final** (PRD);  

# 💸 App de Finanças Pessoais da Carol com Vibe Coding

PRD refinado com Copilot web:
...
# PRD Revisado – App de Organização de Finanças Pessoais com Design Universal

## 1. Visão Geral
Aplicativo de finanças pessoais baseado em conversas naturais, que promove acessibilidade e inclusão desde o início. O design universal garante que qualquer pessoa, com diferentes capacidades e contextos, consiga usar o app sem barreiras.

## 2. Problema
Apps tradicionais exigem entradas manuais complexas e não consideram diversidade de usuários. Isso desmotiva iniciantes e exclui pessoas com necessidades específicas. O objetivo é oferecer uma experiência simples, inclusiva e personalizada.

## 3. Público-Alvo
- Pessoas iniciantes no controle financeiro.
- Usuários que buscam praticidade e orientação amigável.
- Pessoas com diferentes níveis de letramento digital.
- Usuários com necessidades de acessibilidade (visão, audição, mobilidade, cognição).

## 4. Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural.
2. Classificação automática das transações.
3. Metas financeiras definidas e acompanhadas pelo usuário.
4. Agente Financeiro inclusivo, que oferece dicas personalizadas em linguagem clara.
5. Relatórios simples e visuais, com opções de acessibilidade (contraste, leitura em voz alta, ícones intuitivos).

## 5. Princípios de Design Universal
- Equidade de uso: experiência funcional para todos, sem necessidade de adaptações extras.
- Flexibilidade: múltiplas formas de interação (texto, voz, ícones).
- Simplicidade: interface clara, sem sobrecarga cognitiva.
- Perceptibilidade: informações apresentadas de forma acessível (visual, auditiva, textual).
- Tolerância a erros: sistema que previne falhas e oferece correções automáticas.
- Baixo esforço físico e cognitivo: navegação intuitiva e fluida.
- Espaço adequado: design adaptável a diferentes dispositivos e contextos.

## 6. Requisitos Não Funcionais
- Interface responsiva e acessível.
- Segurança de dados financeiros.
- Escalabilidade para futuras integrações inclusivas.

## 7. Métricas de Sucesso
- Engajamento diário no chat.
- Taxa de usuários que configuram metas financeiras.
- Feedback positivo sobre acessibilidade e clareza da experiência.

## Plano de MVP com Design Universal

### Telas Principais
- Tela de Conversa: chat com suporte a texto e voz.
- Tela de Metas: definição simples, com ícones e linguagem acessível.
- Tela de Relatórios: gráficos com contraste adequado, opção de leitura em voz alta e legendas claras.

### Recursos Necessários
- Motor de NLP inclusivo (interpretação de linguagem natural com suporte a variações de escrita).
- Algoritmo de classificação automática.
- Sistema de notificações acessíveis (texto, áudio, visuais).
- Banco de dados seguro.

### Validação Inicial
- Testes com usuários diversos (incluindo pessoas com necessidades de acessibilidade).
- Feedback qualitativo sobre clareza, simplicidade e inclusão.
- Métricas rápidas: tempo médio para registrar um gasto, satisfação com acessibilidade.
...
  
- Prints ou pequenos vídeos das interações com a IA;

- *Olá, por favor crie um APP de finanças pessoais a partir de um PRD: # PRD Revisado – App de Organização de Finanças Pessoais com Design Universal*

- <img width="887" height="250" alt="image" src="https://github.com/user-attachments/assets/19319c01-7e50-42ed-aa62-8726d635175a" />

- 
- Um resumo do que o seu **App de Finanças Pessoais** faz;

- App de Finanças Pessoais – Plano de Implementação

Visão Geral

App de finanças pessoais com interface conversacional, design acessível e inclusivo. O usuário registra gastos via chat em linguagem natural, define metas financeiras e visualiza relatórios.

Arquitetura
Frontend: React + Tailwind CSS, design responsivo e acessível
Backend: Lovable Cloud (Supabase) para banco de dados, autenticação e edge functions
IA: Lovable AI Gateway para processamento de linguagem natural (classificação de gastos, agente financeiro)

Telas e Funcionalidades

1. Autenticação
Login/cadastro com email e senha
Tela simples com boa acessibilidade (labels, contraste, foco visível)

2. Tela de Conversa (Principal)
Chat onde o usuário digita gastos em linguagem natural (ex: "gastei 50 reais no mercado")
IA classifica automaticamente a transação (categoria, valor, data)
Agente financeiro responde com confirmação e dicas personalizadas
Histórico de mensagens persistido
Botão de entrada por voz (Web Speech API)
Markdown rendering nas respostas da IA

3. Tela de Metas Financeiras
Criar metas com nome, valor alvo e prazo
Barra de progresso visual com ícones intuitivos
Cards grandes e legíveis

4. Tela de Relatórios
Gráficos de gastos por categoria (pizza/barras) com alto contraste
Resumo mensal com valores totais
Legendas claras e texto alternativo

5. Navegação
Bottom navigation bar com ícones + texto (Chat, Metas, Relatórios)
Navegação por teclado funcional
Banco de Dados (Supabase)
profiles: dados do usuário
transactions: valor, categoria, descrição, data, user_id
categories: categorias padrão (Alimentação, Transporte, Moradia, Lazer, Saúde, etc.)
goals: meta, valor_alvo, valor_atual, prazo, user_id
chat_messages: histórico de conversas, role, content, user_id
Edge Functions
chat: recebe mensagem do usuário, envia para Lovable AI com system prompt para extrair transações e responder como agente financeiro
A IA extrai dados estruturados (valor, categoria, descrição) e salva automaticamente na tabela de transações

Design Universal
Cores com contraste WCAG AA mínimo
Tamanhos de fonte generosos (base 16px+)
Focus rings visíveis em todos os elementos interativos
Ícones acompanhados de texto
Paleta acessível com tons de azul/verde para finanças

Layout espaçoso, sem sobrecarga visual
...

- Uma breve **reflexão sobre o processo**:
### O que funcionou bem?
  - O refinamento do Copilot fui muito importante.
### O que não funcionou como o esperado?
  - O app funcionou bem, porém os creditos do lovable acabaram já na primeira interação.
### O que aprendeu sobre conversar com IAs?
  - Para esse inicio copiei Venilton pois ainda não sei conversar com a IA. Mas fiquei impressionada com o resultado.
    
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.
>
https://b57c2e02-cf57-4516-afbe-1f62568d0ec5.lovableproject.com/


