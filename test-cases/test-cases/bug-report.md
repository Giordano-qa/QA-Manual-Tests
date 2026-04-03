# Bug Report

---

## BUG-01: Sistema permite login com senha vazia

**Severidade:** Alta  
**Prioridade:** Alta  

**Ambiente:**
Chrome / Windows 10

**Passos para reproduzir:**
1. Acessar a tela de login
2. Inserir email válido
3. Deixar o campo senha em branco
4. Clicar em "Entrar"

**Resultado atual:**
Sistema permite tentativa de login sem senha

**Resultado esperado:**
Sistema deve bloquear a ação e exibir mensagem de campo obrigatório

---

## BUG-02: Campo senha não está mascarado

**Severidade:** Média  
**Prioridade:** Média  

**Passos para reproduzir:**
1. Acessar a tela de login
2. Digitar senha no campo

**Resultado atual:**
Senha é exibida em texto visível

**Resultado esperado:**
Senha deve ser exibida como caracteres ocultos (****)
