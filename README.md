# 📊 Planilha de Gestão de Imposto de Renda

Projeto desenvolvido para organizar, automatizar e facilitar a consolidação de informações para a declaração do **Imposto de Renda**. A planilha conta com navegação interativa, validação de dados e proteção de dados.

---

## 🛠️ Etapas de Desenvolvimento

### 1️⃣ Menu Interativo e Navegação
- **Painel Central:** Criação de um menu principal intuitivo com botões de navegação.
- **Navegação Dinâmica:** Acesso rápido e direto para qualquer guia da planilha através de cliques.

### 2️⃣ Organização e Alinhamento com VBA
- **Automação de Layout:** Utilização de rotinas VBA fornecidas pelo professor para alinhar com precisão os botões e objetos visuais em todas as guias, garantindo um visual padronizado e profissional.

### 3️⃣ Construção e Estilização das Guias

#### 🎨 Identidade Visual
- Criação de um **template de design padrão** (cores, fontes e cabeçalhos) replicado em todas as guias para manter a coerência estética do projeto.

---

#### 👤 Guia 1: Titular
Desenvolvida para armazenar os dados cadastrais e pessoais essenciais do contribuinte.

- **Campos Cadastrais:**
  - Nome, CPF, Data de Nascimento e Título de Eleitor.
  - Endereço completo (Rua, Rua Abreviada e CEP).
  - Contatos (Telefone, Celular e E-mail).
  - Informações de Cônjuge.
- **Controles e Regras de Negócio:**
  - *Houve alterações da entrega anterior?*
  - *Dependente Cônjuge?*
  - *Residente no exterior?*
- **Validação de Dados:** Aplicação de regras de validação em campos específicos para evitar inconsistências de digitação.

---

#### 🏦 Guia 2: Informes de Rendimentos
Focada na consolidação dos saldos bancários e financeiros.

- **Padronização:** Replicação da identidade visual.
- **Informações Bancárias:** Registro centralizado dos dados dos bancos e instituições financeiras.
- **Automação:** Formulas para soma do valor total acumulado por banco.
- **Validação de Dados:** Restrições para garantir a integridade dos dados inseridos.
- **🏆 Desafio Cumprido:** Adição de um **gráfico dinâmico** extra para visualização clara da distribuição dos saldos por instituição financeira.

---

#### 🧾 Guia 3: Notas e Saídas
Estruturada para o controle e acompanhamento de despesas e saídas financeiras.

- **Tabela de Lançamentos:**
  - Data da ocorrência.
  - Categoria da despesa.
  - Valor.

---

### 🔒 Recursos Adicionais e Segurança

- **Navegação Global:** Botões de navegação rápida implementados em todas as guias para facilitar o retorno ao menu principal.
- **Proteção e Segurança:** Bloqueio das planilhas ativado, garantindo que o usuário interaja **apenas com as células de entrada de dados**, prevenindo edições acidentais em fórmulas e layouts.

---

## 🚀 Tecnologias e Recursos Utilizados

- **Microsoft Excel**
- **VBA (Visual Basic for Applications)** para alinhamento de objetos
- **Validação de Dados**
- **Fórmulas e Funções de Agregação**
- **Gráficos Dinâmicos**
- **Proteção de Células e Planilhas**
