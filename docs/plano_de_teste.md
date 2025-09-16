# Plano de Teste – Automation Practice (Campo de Busca)

## 1. Introdução
Este plano de teste descreve a estratégia e o escopo para validação da funcionalidade de **busca de produtos** no site [Automation Practice](http://automationpractice.com/).

---

## 2. Escopo
### 2.1 Escopo Incluído
- Pesquisa de produtos pela barra de busca.
- Retorno de resultados relacionados ao termo pesquisado.
- Mensagens exibidas quando não há resultados.
- Redirecionamento correto ao clicar em um produto.

### 2.2 Fora do Escopo
- Funcionalidades de login, cadastro ou checkout.
- Testes de performance e carga.
- Testes automatizados (neste projeto).

---

## 3. Estratégia de Teste
- **Tipo de teste:** Manual funcional.  
- **Técnicas:** Teste de caixa-preta, partição de equivalência e análise de valor limite.  
- **Nível de teste:** Teste de sistema.  
- **Critérios de aprovação:** O sistema deve retornar resultados corretos e mensagens adequadas, sem erros ou falhas visuais.

---

## 4. Ambiente de Teste
- **Aplicação:** [Automation Practice](http://automationpractice.com/)  
- **Navegadores:** Google Chrome (última versão), Microsoft Edge (última versão).  
- **Sistema Operacional:** Windows 10.  

---

## 5. Critérios
### 5.1 Critérios de Entrada
- Ambiente disponível e acessível.  
- Casos de teste documentados.  

### 5.2 Critérios de Saída
- Todos os casos de teste executados.  
- Evidências registradas em `docs/evidencias/prints_execucao/`.  
- Bugs documentados no `relatorio_de_bugs.md`.  

---

## 6. Riscos
- Instabilidade temporária do site (por ser ambiente de demonstração).  
- Alterações no layout que impactem os testes planejados.  
