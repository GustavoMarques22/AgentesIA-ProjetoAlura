**Sistema de Criação de Posts para Instagram com 4 Agentes (Google Gemini)**

---

````markdown
# 🤖 Sistema de Criação de Posts para Instagram com 4 Agentes (Google Gemini)

Este projeto demonstra um fluxo completo de criação de conteúdo para redes sociais usando agentes inteligentes integrados com a API do **Google Gemini**. Ele foi desenvolvido para rodar em **Google Colab**, utilizando ferramentas de busca em tempo real e modelos generativos para criar, planejar, redigir e revisar posts voltados para o Instagram.

## 📌 Funcionalidades

- 🔎 **Agente Buscador**: Localiza os lançamentos mais relevantes e recentes sobre um tópico específico.
- 🧠 **Agente Planejador**: Planeja os principais pontos a serem abordados em um post com base nas tendências identificadas.
- ✍️ **Agente Redator**: Cria um rascunho de post criativo, engajador e otimizado para o Instagram.
- 📝 **Agente Revisor**: Analisa e revisa o post com foco em clareza, tom e adequação ao público jovem.

## 📅 Exemplo de Uso

Você pode executar esse projeto no Google Colab para gerar posts sobre temas atuais, como por exemplo:

```bash
❓ Por favor, digite o TÓPICO sobre o qual você quer criar o post de tendências:
````

**Exemplo de entrada**: `Inteligência Artificial na Educação`

O sistema então:

1. Busca lançamentos recentes sobre o tópico.
2. Planeja os pontos principais do post.
3. Redige o conteúdo.
4. Revisa e sugere melhorias.

## 🛠️ Tecnologias e Bibliotecas Utilizadas

* `google-genai`: Integração com a API do Gemini
* `google-adk`: Framework para construção de agentes com ferramentas como `google_search`
* `Google Colab`: Ambiente de execução interativo
* `IPython.display`, `textwrap`, `requests`, `datetime`, `warnings`

## 🧪 Requisitos

* Conta Google com acesso ao Google Colab
* Chave de API do Google Gemini (GOOGLE\_API\_KEY) configurada via `google.colab.userdata`
* Pacotes instalados:

  ```python
  %pip install -q google-genai
  %pip install -q google-adk
  ```

## 🧠 Modelo Utilizado

* `gemini-2.0-flash` (para buscas e planejamento)
* `gemini-2.5-pro-preview-03-25` (para redação e revisão)

## 📂 Estrutura do Código

* Funções auxiliares para comunicação com os agentes
* Execução sequencial dos agentes
* Entrada interativa via `input()`
* Impressões formatadas com `Markdown` no Colab

## 🚀 Como Executar

1. Clone este repositório.
2. Abra o notebook no Google Colab.
3. Insira sua chave da API do Google Gemini.
4. Execute célula por célula.
5. Insira um tópico de interesse e acompanhe a geração do post.

## 📸 Exemplo de Resultado Final

> Você terá um post pronto para publicar no Instagram, com hashtags e linguagem otimizada!

## 📝 Licença

Este projeto é de uso educacional e segue os termos de uso da API do Google Gemini.

---

Feito com ❤️ por \[Gustavo Marques] — Projeto educacional com foco em IA generativa para criação de conteúdo.

```

---
