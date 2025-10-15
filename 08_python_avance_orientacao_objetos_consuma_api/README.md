# Python: Avance — Orientação a Objetos e Consuma API

Este diretório contém os códigos e exercícios desenvolvidos durante o curso **[Python: Avance — Orientação a Objetos e Consuma API](https://cursos.alura.com.br/course/python-avance-orientacao-objetos-consuma-api)** da [Alura](https://www.alura.com.br/), que faz parte da trilha **Carreira de Desenvolvimento Back-End Python**.

---

## 📂 Estrutura
- **oo_sabor_express/** → Projeto principal que complementa o que foi desenvolvido no **06_python_aplicando_orientacao_a_objetos**.
- **oo_sabor_express_api/** → Um segundo projeto principal desenvolvido mais para o final do curso, aplicando conceitos de API.
- **hora_da_pratica/** → Exercícios práticos propostos ao final de cada módulo.  
- **requirements.txt** → (opcional) dependências do projeto.

---

## 📚 Conteúdos aprendidos
Durante este curso, foram explorados os seguintes conceitos:

- Criação da classe base `ItemCardapio` com construtor e atributos principais;  
- Herança aplicada em `Prato` e `Bebida`, utilizando `super()` para reaproveitamento de comportamento;  
- Uso de `@property` para expor e controlar acesso a informações do cardápio;  
- Implementação de método abstrato (ex.: `aplicar_desconto`) para demonstrar polimorfismo entre tipos de itens;  
- Métodos para adicionar e listar itens no cardápio que aceitam instâncias de `ItemCardapio`;  
- Consumo de APIs externas usando `requests`, tratamento de respostas JSON e gravação em arquivos locais;  
- Criação de uma API com **FastAPI** para listar e filtrar restaurantes/dados consumidos, com documentação automática em `/docs` e `/redoc`;  
- Exercícios práticos para consolidar OOP e integração com APIs.

---

## 🚀 Projeto desenvolvido: Cardápio OOP + Consumo de API

Projeto final que une conceitos de orientação a objetos com integração e exposição de APIs. Principais funcionalidades:

- Modelos OOP: implementação das classes `ItemCardapio`, `Prato` e `Bebida` com herança, propriedades e polimorfismo;
- Adição e listagem de itens do cardápio utilizando métodos e propriedades customizadas;
- Aplicação de descontos específicos para cada tipo de item, demonstrando uso de métodos abstratos;
- Consumo de API externa para obtenção de dados de restaurantes, manipulação de respostas JSON e persistência em arquivos locais;
- Criação de uma API REST com FastAPI, incluindo endpoints para listar e filtrar restaurantes;
- Documentação automática e interativa dos endpoints via Swagger (`/docs`) e ReDoc (`/redoc`).

---

## 📝 Observações
- Exercícios complementares estão na pasta **hora_da_pratica/**.  
- O projeto principal está dividido nas pastas **oo_sabor_express/** e **oo_sabor_express_api/**.  
- Recomendações: criar/ativar um `venv` antes de instalar dependências; manter `requirements.txt` atualizado; adicionar docstrings e testes básicos (unitários e de endpoint) para garantir qualidade.
