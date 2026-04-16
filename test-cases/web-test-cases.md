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

CT-03: Validação de email inválido no cadastro(Linkedin)

Prioridade: Alta  
Severidade: Média  
Tipo de teste: Funcional  

Passos:

1. Acessar a página de cadastro do LinkedIn
2. Inserir um email inválido (ex: giordanocaruso)
3. Clicar em "Aceite e cadastre-se"

Resultado esperado:

- O sistema deve exibir mensagem de erro informando email inválido
- O campo deve ser destacado visualmente (ex: borda vermelha)

Evidência:

![Email inválido](../evidencias/CT-03-email-invalido.png)

---

CT-04: Validação de campos obrigatórios vazios(Linkedin)

Prioridade: Alta  
Severidade: Alta  
Tipo de teste: Funcional  

Passos:

1. Acessar a página de cadastro do LinkedIn
2. Deixar os campos de email e senha vazios
3. Clicar em "Aceite e cadastre-se"

Resultado esperado:

- O sistema deve exibir mensagens informando que os campos são obrigatórios
- Os campos devem ser destacados visualmente

Evidência:

![Campos vazios](../evidencias/CT-04-campos-vazios.png)


---

CT-05: Validação de senha com baixo nível de segurança

Prioridade: Alta  
Severidade: Média  
Tipo de teste: Funcional  

Passos:

1. Acessar a página de cadastro do LinkedIn
2. Inserir um email válido
3. Inserir uma senha fraca (ex: 123456)
4. Clicar em "Aceite e cadastre-se"

Resultado esperado:

- O sistema deve exibir mensagem informando que a senha não atende aos requisitos de segurança
- O usuário não deve conseguir prosseguir com o cadastro

Evidência:

![Senha fraca](../evidencias/CT-05-senha-fraca.png)
