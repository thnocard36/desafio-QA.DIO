# Desafio: Prática de Testes Manuais Funcionais - O Dia a Dia de um QA

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![DIO](https://img.shields.io/badge/Digital_Innovation_One-EE2E5D?style=for-the-badge)
![Almaviva Solutions](https://img.shields.io/badge/Almaviva_Solutions-blue?style=for-the-badge)
![Testing Library](https://img.shields.io/badge/Testing%20Library-E33332?style=for-the-badge&logo=testing-library&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira&logoColor=white)

Este projeto tem como foco o levantamento de requisitos e a execução de testes funcionais manuais no sistema Swag Labs (SauceDemo). A prática simula o dia a dia de um profissional de Quality Assurance (QA), documentando cenários de teste, mapeando fluxos e estruturando evidências de execução.

| **Categoria** | **Detalhes** |
| :--- | :--- |
| **Autor** | [Thiago Cardoso](https://github.com/thnocard36) |
| **Professora** | [Carolina Santana Louzada](https://github.com/CarolinaSL) |


> a real grandeza é o que se faz com as cartas que ganha.

*Uncharted 3*


---

## 🚀 Sobre o Projeto

O **Swag Labs** é uma aplicação web de e-commerce simulada, muito utilizada na área de testes de software para aprendizado e validação de fluxos de usuário. O objetivo deste desafio é aplicar conceitos de teste de caixa preta, garantindo a qualidade da interface, regras de negócio e usabilidade da aplicação.

---

## 📋 Requisitos e Mapeamento de Fluxos

Durante a análise, foram mapeados os principais fluxos da aplicação para garantir a cobertura dos testes:

-   **Autenticação e Login:** Validação do acesso com diferentes tipos de usuários (usuário padrão, usuário bloqueado e usuário com problema de performance).
    
-   **Catálogo de Produtos:** Verificação das funcionalidades de ordenação (por nome e preço) e visualização do inventário.
    
-   **Carrinho de Compras:** Adição e remoção de itens, mantendo a consistência dos dados ao navegar pelo site.
    
-   **Fluxo de Checkout (Compra):** Validação de campos obrigatórios no formulário de preenchimento de dados e conclusão da compra.

---

## 🔍 Cenários de Teste Mapeados

Abaixo estão alguns dos principais cenários estruturados durante o desafio:

| **ID** | **Cenário / Funcionalidade** | **Pré-condição** | **Resultado Esperado** | **Status** |
| :--- | :--- | :--- | :--- | :--- |
| **CT01** | Efetuar login com credenciais válidas | Na página de login | Usuário é redirecionado para a página de produtos. | ✅ Sucesso
| **CT02** | Tentar login com usuário bloqueado | Na página de login | Exibir mensagem de erro: `Epic sadface: Sorry, this user has been locked out`. | ✅ Sucesso
| **CT03** | Adicionar produto ao carrinho | Na página de produtos | O botão muda para "Remove" e o badge do carrinho é atualizado. | ✅ Sucesso
| **CT04** | Efetuar checkout com carrinho vazio | No carrinho de compras | O sistema não deve permitir avançar para o pagamento sem itens. | ✅ Sucesso.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

-   **Metodologias:** Testes Manuais Funcionais, Caixa Preta, Modelagem de Casos de Teste.
    
-   **Controle de Versão:** Git e GitHub para versionamento do projeto.
    
-   **Documentação:** Markdown e diagramação de cenários.

---

## 💡 Próximos Passos e Melhorias

-   Integração dos cenários em ferramentas de gestão de testes (como Xray/Jira).
    
-   Automação dos fluxos críticos utilizando Java com Selenium WebDriver ou Cypress.

---

### 📜 Licença

Este projeto está sob a licença MIT. Isso significa que você pode copiar, modificar e distribuir o código, desde que inclua o aviso de copyright original.