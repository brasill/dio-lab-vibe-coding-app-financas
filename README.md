# 💸 FinIA — Organização de Finanças Pessoais com IA

> Desafio de projeto **Vibe Coding** — Digital Innovation One (DIO)
> Conceito de aplicativo desenvolvido guiando ferramentas de IA (Claude / Lovable) com prompts claros, criativos e orientados a segurança (SecOps).

---

## 🚀 Sobre o Projeto

O **FinIA** é o conceito de um aplicativo de organização financeira pessoal que funciona **por meio de conversas naturais**, eliminando formulários manuais e planilhas complexas. Em vez de o usuário preencher categorias e valores, ele simplesmente conversa com um **Agente Financeiro de IA**, que registra, classifica e orienta suas finanças automaticamente.

Este repositório documenta todo o processo de **Vibe Coding**: da criação do PRD (Product Requirements Document) até as interações com a IA para gerar o plano de MVP, o fluxo de telas e a definição do agente.

---

## 📌 Prompt Final (PRD) usado com a IA

```text
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de
conversas naturais com o usuário. A ideia é simplificar o controle financeiro sem
formulários complexos ou planilhas manuais, trazendo uma experiência leve e intuitiva
no estilo Vibe Coding.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita
entrada manual e não oferecem personalização real. Quero resolver isso com uma
experiência conversacional, onde a IA atua como um Agente Financeiro que entende o
usuário e sugere planos automáticos de economia.

# Público-Alvo
Pessoas que desejam começar a organizar suas finanças de forma prática e sem
complicação, principalmente iniciantes que nunca usaram apps financeiros ou que se
frustraram com soluções tradicionais.

# Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural.
2. Classificação automática das transações.
3. Definição de metas financeiras personalizadas.
4. Agente Financeiro que dá dicas de economia e acompanha o progresso.
5. Relatórios simples e personalizados, com visualização clara.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de
validação inicial. Definir o comportamento e tom de voz do Agente Financeiro
(educativo, acessível e motivador). Criar o fluxo de telas baseado nas
funcionalidades descritas. Usar linguagem acessível e em português.

# Requisitos de Segurança (SecOps / Privacidade)
- Criptografia ponta a ponta para dados financeiros sensíveis.
- Autenticação forte (biometria e/ou 2FA) e sessões com expiração automática.
- Logs de auditoria para rastrear acessos e alterações de dados.
- Conformidade com a LGPD: minimização de dados, consentimento explícito e
  possibilidade de exclusão de conta e dados a qualquer momento.
- Nenhum dado financeiro deve ser usado para treinar modelos de IA de terceiros
  sem consentimento explícito do usuário.

# Tom de Voz do Agente Financeiro
Amigável, educativo e motivador — sem jargões técnicos. Transparente: sempre
explica o "porquê" de uma recomendação antes de sugeri-la.
