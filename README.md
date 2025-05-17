```markdown
# 🚀 Sistema Inteligente de Criação de Posts para Instagram com Agentes Gemini

Este projeto apresenta uma solução automatizada para a **criação de conteúdo para Instagram**, utilizando **inteligência artificial generativa** com o **Google Gemini**. Por meio da arquitetura de **agentes especializados**, o sistema executa as etapas de pesquisa, planejamento, redação e revisão de posts com foco em tendências atuais.

> 💡 Ideal para criadores de conteúdo, profissionais de marketing digital e entusiastas de IA que desejam automatizar a produção de posts criativos e relevantes.

---

## 🧠 Arquitetura de Agentes

O sistema é dividido em 4 agentes colaborativos, cada um com uma função específica:

| Agente          | Função                                                                 |
|-----------------|------------------------------------------------------------------------|
| 🔎 **Buscador**     | Pesquisa os lançamentos mais recentes e relevantes sobre um tema.     |
| 🧭 **Planejador**   | Estrutura os principais tópicos e pontos-chave do post.               |
| ✍️ **Redator**      | Redige o conteúdo com tom engajador e linguagem otimizada para o IG. |
| 🪄 **Revisor**       | Ajusta o texto, melhora o estilo e garante a clareza da mensagem.     |

---

## 📷 Exemplo de Aplicação

Durante a execução no Google Colab, o usuário insere um **tópico** de interesse:

```

📌 Digite o tema sobre o qual deseja criar o post (ex: Inteligência Artificial na Saúde):

````

O sistema então:
1. Coleta informações relevantes com base nas tendências.
2. Planeja a estrutura do post.
3. Gera o conteúdo.
4. Revê o texto com foco em clareza, criatividade e impacto.

---

## 🧰 Tecnologias Utilizadas

- 🧠 **[Google Gemini API](https://ai.google.dev/)**
- 🧩 `google-genai` e `google-adk` (Agentes e Ferramentas)
- ☁️ **Google Colab**
- 🐍 Python 3
- 📦 Bibliotecas auxiliares: `requests`, `datetime`, `IPython.display`, `textwrap`

---

## ⚙️ Como Executar

1. Faça o clone deste repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
````

2. Acesse o [notebook no Google Colab]([(https://colab.research.google.com/drive/1bmCwOWTjo5bliCzaTdhIaVwZCKAc7vPP?usp=sharing)]).
3. Insira sua chave de API Gemini:

   ```python
   from google.colab import userdata
   userdata.set('GOOGLE_API_KEY', 'sua-chave-aqui')
   ```
4. Execute célula por célula.
5. Insira o tópico desejado e acompanhe a geração do post.

---

## 📄 Resultado Esperado

* Post completo e otimizado para Instagram.
* Linguagem criativa e direcionada ao público jovem.
* Sugestões de melhorias feitas por IA.
* Conteúdo pronto para publicação!

---

## 📌 Requisitos

* Conta no Google com acesso ao Colab
* Chave de API Gemini ativa
* Instalação dos pacotes:

  ```python
  %pip install -q google-genai
  %pip install -q google-adk
  ```

---

## 📜 Licença

Projeto desenvolvido para fins educacionais. O uso da API Gemini deve respeitar os termos de uso oficiais do Google.

---

## 👨‍💻 Autor

Desenvolvido por \[Gustavo Marques]
🔗 [Seu LinkedIn]((https://www.linkedin.com/in/gustavo-marques-5a3723294/)) | 🐙 [@seu-usuario]((https://github.com/GustavoMarques22))

---
