# Test Cases - Testes Manuais em Sites Públicos

---

## CT-01: Validação de busca de produto - Mercado Livre

**Prioridade:** Alta  
**Severidade:** Alta  
**Tipo de teste:** Funcional  

**Passos:**
1. Acessar o site
2. Buscar por "notebook"
3. Validar os resultados exibidos
4. Aplicar filtros (marca, preço)
5. Ordenar por menor preço

**Resultado esperado:**
- Sistema deve exibir produtos relacionados a "notebook"
- Resultados devem ser relevantes
- Filtros devem ser aplicados corretamente
- Ordenação deve respeitar o critério selecionado

**Evidência:**

![Busca de produtos](../evidencias/CT-01-busca-resultados.png)

![Filtro aplicado](../evidencias/CT-01-filtro-aplicado.png)

![Ordenação por preço](../evidencias/CT-01-ordenacao-preco.png)

---

CT-02: Abertura do menu lateral

Prioridade: Média  
Severidade: Média  
Tipo de teste: Usabilidade / Interface  

Passos:

1. Acessar a página inicial da Amazon
2. Clicar no menu "Todos"
3. Observar a abertura do menu lateral

Resultado esperado:

- O menu lateral deve abrir corretamente
- As categorias devem ser exibidas
- O layout deve estar organizado e legível

Evidência:

![Menu lateral aberto](../evidencias/CT-02-menu-lateral.png)

![Categorias exibidas](../evidencias/CT-02-categorias.png)

![Interação com menu](../evidencias/CT-02-interacao.png)
---

## CT-03: Validação de formulário - LinkedIn

**Prioridade:** Alta  
**Severidade:** Alta  
**Tipo de teste:** Funcional  

**Passos:**
1. Acessar página de cadastro
2. Inserir email inválido
3. Deixar campos vazios
4. Inserir senha fora do padrão
5. Tentar continuar cadastro

**Resultado esperado:**
- Sistema deve validar email
- Sistema deve exigir preenchimento dos campos
- Sistema deve validar regras de senha
- Cadastro não deve prosseguir com dados inválidos

**Evidência:**
(ADICIONAR AQUI DEPOIS)

---

## CT-04: Validação de login - Magazine Luiza

**Prioridade:** Alta  
**Severidade:** Alta  
**Tipo de teste:** Funcional  

**Passos:**
1. Inserir email válido + senha incorreta
2. Inserir email inválido
3. Deixar senha vazia
4. Deixar email vazio
5. Testar opção "mostrar senha"
6. Testar limite mínimo de senha

**Resultado esperado:**
- Sistema deve validar credenciais
- Deve exibir mensagens de erro apropriadas
- Campos obrigatórios devem ser validados
- Funcionalidade de mostrar senha deve funcionar corretamente

**Evidência:**

