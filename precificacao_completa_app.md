# 💰 Quanto cobrar pelo desenvolvimento de um aplicativo?

## Da proposta à manutenção — guia completo com estudo de caso

---

## 📺 Assista ao vídeo

[![Assista ao vídeo no YouTube](https://img.youtube.com/vi/BrkTXOdWyqg/maxresdefault.jpg)](https://www.youtube.com/watch?v=BrkTXOdWyqg)

Ou clique diretamente aqui:  
👉 [https://www.youtube.com/watch?v=BrkTXOdWyqg](https://www.youtube.com/watch?v=BrkTXOdWyqg)

## 🧠 Introdução

"Quanto custa um app?" é a pergunta mais comum — e mais difícil — de responder.  
Cada projeto é único, e precificar corretamente exige muito mais do que um chute.

Neste guia você vai entender:

- Como levantar requisitos de forma correta
- Como estimar horas de trabalho com mais precisão
- Como calcular o valor do projeto
- Como incluir custos de publicação
- Como precificar manutenção
- Como transformar um projeto em receita recorrente

---

## ✅ Etapa 1: Levantamento de Requisitos

Essa é a etapa mais **negligenciada** — e onde nasce a maior parte dos erros de precificação.

Muita gente pergunta “quantas telas o app vai ter?”, mas isso é **superficial**.  
Precisamos entender:

### 🔍 Funcionalidades (requisitos funcionais):

- O que o app precisa fazer?
- Quais interações ele vai ter?
- Quais permissões ele exige?

### 🛠️ Requisitos técnicos (não funcionais):

- Qual o nível de performance esperado?
- Haverá suporte offline?
- Requer autenticação? E-mails? Push notifications?
- O backend já existe ou precisa ser desenvolvido?

### 🧩 Integrações:

- Vai integrar com gateways de pagamento?
- Com sistemas legados? APIs de terceiros?

### 🧩 Exclusividade e propriedade intelectual:

- Vai ter contrato de exclusividade e não concorrência?

## 🎓 Estudo de caso fictício — App para loja de produtos naturais

### 📌 Briefing inicial:

Uma loja de produtos naturais quer um app com:

- Catálogo de produtos
- Carrinho de compras
- Pagamento online
- Notificações push
- Login com e-mail e redes sociais
- Painel administrativo para cadastro de produtos
- Relatórios de vendas

---

### 📋 Levantamento detalhado (Exemplo prático)

#### 🧾 Tela de login:

- UI da tela (campos, validações, feedback visual)
- Sistema de autenticação (email/senha, Google, Facebook)
- Esqueci minha senha (tela + fluxo)
- Verificação de email (opcional?)
- Backend: já existe? Se não, precisamos:
  - Criar endpoints de login
  - Gerar tokens (JWT, session?)
  - Armazenar usuários
  - Gerenciar senhas, tokens de recuperação

#### 📦 Catálogo de produtos:

- Tela com lista + filtros
- Detalhe do produto
- Integração com banco de dados
- Backend: endpoints para listar, filtrar, buscar

#### 🛒 Carrinho:

- Adicionar/remover item
- Calcular total
- Validar estoque
- Backend: lógica de carrinho (em memória? persistente?)

#### 💳 Pagamento:

- Integração com gateway (ex: MercadoPago, Stripe)
- Validação de status do pagamento
- Segurança dos dados
- Backend: webhook para confirmação

#### 📲 Notificações:

- Push (OneSignal, Firebase)
- Backend para agendamento/envio

#### 📊 Painel admin:

- Web app separado?
- Login admin
- Cadastro/edição de produtos
- Visualização de pedidos

---

## ⏱️ Estimativa de horas

| Etapa                       | Horas estimadas |
| --------------------------- | --------------- |
| Levantamento + documentação | 10h             |
| UX/UI Design                | 20h             |
| Frontend do app             | 50h             |
| Backend + APIs              | 40h             |
| Testes                      | 10h             |
| Publicação                  | 5h              |
| **Total**                   | **135 horas**   |

---

## 💵 Valor por hora

Defina de acordo com:

- Nível de experiência
- Complexidade do projeto
- Custo operacional
- Média de mercado

**Exemplo:** R$ 150/h → **135h x R$150 = R$ 20.250,00**

---

## 🚀 Publicação

- **Google Play:** US$ 25 (taxa única)
- **Apple Store:** US$ 99/ano
- Tempo de revisão e ajustes pode variar

---

## 🛠️ Manutenção

Manutenção não é um "extra", é parte do ciclo de vida do app.

Inclui:

- Correções de bugs
- Ajustes por mudanças no Android/iOS
- Suporte ao cliente
- Atualizações de segurança

**Como cobrar?**

- 💳 Mensal: R$ 400 a R$ 1.000/mês (ou mais)
- 📈 Percentual do projeto: 10% a 20%
- 💼 Contrato recorrente com escopo definido

---

## 🔁 Recorrência

Não dependa só de novos projetos.  
Transforme clientes em **clientes permanentes**:

- Suporte contínuo
- Pacotes de horas para melhorias
- Infraestrutura, hospedagem, backups

---

## ✅ Conclusão

A precificação correta começa no **levantamento de requisitos**.  
Quanto mais claro o escopo, mais justo o valor.

Não venda apenas o app.  
Venda **resultado**, **continuidade** e **confiança**.

---

👉 Curtiu? Compartilhe esse conteúdo com quem desenvolve ou contrata apps!
