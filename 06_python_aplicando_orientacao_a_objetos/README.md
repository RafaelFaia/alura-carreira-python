# Python: aplicando a Orientação a Objetos

Este diretório contém os códigos e exercícios desenvolvidos durante o curso **[Python: aplicando a Orientação a Objetos](https://cursos.alura.com.br/course/python-aplicando-orientacao-objetos)** da [Alura](https://www.alura.com.br/), que faz parte da trilha **Carreira de Desenvolvimento Back-End Python**.

---

## 📂 Estrutura
- **oo_sabor_express/** → Projeto principal desenvolvido ao longo do curso.   
  - `oo_sabor_express/app.py` — entrypoint/integração do projeto.  
  - `oo_sabor_express/modelos/restaurante.py` — definição da classe `Restaurante`.  
  - `oo_sabor_express/modelos/avaliacao.py` — definição da classe `Avaliação`.  
- **hora_da_pratica/** → Exercícios práticos propostos ao final de cada módulo.  

---

## 📚 Conteúdos aprendidos
Durante este curso, foram explorados e praticados os seguintes conceitos:

- Conceito de **classe** e sua utilidade na organização modular e reutilizável do código;  
- Criação de classes (ex.: `Restaurante`) com atributos de instância (`nome`, `categoria`, `ativo`) e uso do construtor `__init__` (com `ativo` inicializado como `False` por padrão);  
- Distinção entre **atributos de classe** e **atributos de instância**; práticas de acesso e manipulação de atributos;  
- Uso de underscore para indicar atributos protegidos;  
- Uso de **`@property`** para acesso controlado de atributos (ex.: `categoria`, `ativo`);  
- Criação e uso de **métodos de classe** (`@classmethod`) para operações que agem sobre a classe;  
- Integração entre classes (ex.: associação entre `Restaurante` e `Avaliação`) e manipulação de listas de objetos;  
- Técnicas de listagem/iteração para exibir avaliações e outros dados agregados;  
- Boas práticas de documentação com **docstrings** (quando usar e por quê).

---

## 🚀 Projeto desenvolvido: OO Sabor Express
O projeto principal (pastas dentro de `oo_sabor_express/`) aplica POO para modelar um sistema simples de gerenciamento de restaurantes, com:

- Modelos orientados a objetos (`Restaurante`, `Avaliação`);  
- Operações de listagem e apresentação de dados (ex.: listar restaurantes e suas avaliações);  
- Encapsulamento de comportamento via métodos e propriedades;  
- Arquitetura simples pensada para ser compreensível e extensível em exercícios posteriores.

---

## 📝 Observações
- Exercícios complementares estão na pasta **hora_da_pratica/**.  
- O projeto principal está na pasta **oo_sabor_express/**.