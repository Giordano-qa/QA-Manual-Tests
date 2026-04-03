# Test Cases - Login

---

## CT-01: Login com credenciais válidas

**Prioridade:** Alta
**Severidade:** Crítica
**Tipo de teste:** Funcional

**Pré-condição:** Usuário já cadastrado

**Passos:**

1. Acessar página de login
2. Inserir email válido
3. Inserir senha válida
4. Clicar em "Entrar"

**Resultado esperado:**
Usuário deve ser redirecionado para a página inicial logado

---

## CT-02: Login com senha inválida

**Prioridade:** Alta
**Severidade:** Alta
**Tipo de teste:** Funcional

**Passos:**

1. Inserir email válido
2. Inserir senha incorreta
3. Clicar em "Entrar"

**Resultado esperado:**
Sistema deve exibir mensagem: "Email ou senha inválidos"

---

## CT-03: Validação de campos obrigatórios

**Prioridade:** Média
**Severidade:** Média
**Tipo de teste:** Funcional

**Passos:**

1. Clicar em "Entrar" sem preencher os campos

**Resultado esperado:**
Sistema deve exibir mensagens informando que os campos são obrigatórios

---

## CT-04: Validação de formato de email inválido

**Prioridade:** Média
**Severidade:** Baixa
**Tipo de teste:** Funcional

**Passos:**

1. Inserir email em formato inválido (ex: teste@)
2. Inserir qualquer senha
3. Clicar em "Entrar"

**Resultado esperado:**
Sistema deve exibir mensagem informando formato de email inválido

---

## CT-05: Validação de campo senha mascarado

**Prioridade:** Baixa
**Severidade:** Baixa
**Tipo de teste:** Usabilidade

**Passos:**

1. Digitar senha

**Resultado esperado:**
Senha deve ser exibida como caracteres ocultos (****)

