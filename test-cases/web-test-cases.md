# Test Cases - Login

---

## CT-01: Login com senha inválida
**Prioridade:** Alta  
**Severidade:** Alta  
**Tipo de teste:** Funcional  

**Passos:**
1. Acessar página de login
2. Inserir email válido
3. Inserir senha incorreta
4. Clicar em "Entrar"

**Resultado esperado:**
Sistema deve exibir mensagem informando senha inválida

---

## CT-02: Validação de email inválido
**Prioridade:** Média  
**Severidade:** Média  
**Tipo de teste:** Funcional  

**Passos:**
1. Inserir email em formato inválido
2. Inserir senha válida
3. Clicar em "Entrar"

**Resultado esperado:**
Sistema deve exibir mensagem informando email inválido

---

## CT-03: Validação de senha vazia
**Prioridade:** Alta  
**Severidade:** Alta  
**Tipo de teste:** Funcional  

**Passos:**
1. Inserir email válido
2. Deixar senha em branco
3. Clicar em "Entrar"

**Resultado esperado:**
Sistema deve exibir mensagem de campo obrigatório

---

## CT-04: Validação de email vazio
**Prioridade:** Alta  
**Severidade:** Alta  
**Tipo de teste:** Funcional  

**Passos:**
1. Deixar email em branco
2. Inserir senha válida
3. Clicar em "Entrar"

**Resultado esperado:**
Sistema deve exibir mensagem solicitando email

---

## CT-05: Funcionalidade mostrar senha
**Prioridade:** Baixa  
**Severidade:** Baixa  
**Tipo de teste:** Usabilidade  

**Passos:**
1. Inserir senha
2. Clicar em "mostrar senha"

**Resultado esperado:**
Sistema deve exibir senha em texto visível

