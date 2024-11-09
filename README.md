# Projeto - Azure AI Translator 🌐

Este repositório contém dois projetos desenvolvidos e aprendidos durante as aulas sobre **IA da Azure no Bootcamp da DIO**. Utilizando o Google Colab, cada projeto aplica diferentes serviços de tradução da Azure para oferecer soluções precisas e eficientes.

### 📑 Índice
- [📌 Introdução](#-introdução)
- [⚙️ Tecnologias Utilizadas](#️-tecnologias-utilizadas)
- [🗂️ Projetos](#️-projetos)
  - [1. Tradutor de Frases](#1-tradutor-de-frases)
  - [2. Tradutor de Artigos](#2-tradutor-de-artigos)
- [🛠️ Como Usar](#️-como-usar)
- [💡 Exemplos](#-exemplos)
- [🤝 Contribuições](#-contribuições)
- [📄 Licença](#-licença)

---

## 📌 Introdução

Este repositório reúne dois projetos focados em tradução automática usando serviços da **Azure AI**, que foram desenvolvidos e aprendidos durante o Bootcamp da DIO:

1. **Tradutor de Frases**: Utiliza o serviço **Azure Translator** para traduzir frases curtas ou arquivos com letras de músicas inseridos pelo usuário diretamente no Google Colab.
2. **Tradutor de Artigos**: Usa o serviço **Azure OpenAI** para traduzir artigos completos a partir de uma URL fornecida, com formatação em Markdown.

Esses projetos são ideais para quem deseja aprender a integrar serviços de tradução baseados em IA em suas próprias aplicações.

---

## ⚙️ Tecnologias Utilizadas
- [Google Colab](https://colab.research.google.com/)
- [Azure Cognitive Services](https://azure.microsoft.com/en-us/services/cognitive-services/)
  - Azure Translator
  - Azure OpenAI Service
- Python

---

## 🗂️ Projetos

### 1. Tradutor de Frases
Este projeto utiliza o serviço **Azure Translator** para traduzir frases inseridas pelo usuário ou até mesmo arquivos com letras de músicas.

- **Funcionalidade**: 
  - Tradução rápida de frases curtas.
  - Se o usuário fornecer um arquivo `.txt` contendo a letra de uma música, o sistema traduz o conteúdo e gera um novo arquivo com o nome formatado como `talmúsica_pt-br.docx`.
- **Serviço Usado**: Azure Translator.
- **Ideal para**: Quem precisa traduzir textos pequenos ou testar funcionalidades do Azure Translator, além de traduzir letras de músicas de forma automatizada.

#### 🚀 Como Executar
1. Abra o arquivo `tradutor_frases.ipynb` no Google Colab.
2. Siga as instruções para configurar suas **Azure API Keys**.
3. Insira a frase ou faça o upload do arquivo `.txt` com a letra da música que deseja traduzir e execute a célula para obter a tradução.

---

### 2. Tradutor de Artigos
Este projeto utiliza o serviço **Azure OpenAI** para traduzir artigos completos a partir de uma URL, formatando o texto traduzido em **Markdown**.

- **Funcionalidade**: Tradução de artigos completos com formatação automática.
- **Serviço Usado**: Azure OpenAI (similar ao ChatGPT).
- **Ideal para**: Quem deseja traduzir artigos acadêmicos ou técnicos de forma rápida e organizada.

#### 🚀 Como Executar
1. Abra o arquivo `tradutor_artigos.ipynb` no Google Colab.
2. Configure suas **Azure API Keys**.
3. Insira a URL do artigo em inglês que deseja traduzir.
4. Execute a célula para visualizar o artigo traduzido em Markdown diretamente no Colab.

---

## 🛠️ Como Usar
1. **Clone este repositório**:
   ```bash
   git clone https://github.com/seu-usuario/azure-ai-translator.git
   cd azure-ai-translator
   ```

2. **Abra os notebooks no Google Colab**:
   - Tradutor de Frases: [tradutor_frases.ipynb](https://colab.research.google.com/drive/1QZdGRI-L1rXvB-FlnSjaibLsW0CSf_ws#scrollTo=9oeFQQkQAurn)
   - Tradutor de Artigos: [tradutor_artigos.ipynb](https://colab.research.google.com/drive/1-58tBIqoLNxug8LgvZvpedGVqfH-nCVF)

3. **Adicione suas chaves de API**:
   - Siga as instruções nos notebooks para adicionar suas **Azure API Keys**.

---

## 💡 Exemplos
### Exemplo 1: Tradutor de Frases
```python
# Exemplo de uso do tradutor de frases
frase = "Hello, how are you?"
traducao = traduzir_frase(frase)
print(traducao)  # Resultado: "Olá, como você está?"
```

### Exemplo 2: Tradutor de Arquivo de Música
```python
# Upload do arquivo com a letra da música
arquivo = "letra-musica.txt"
traduzir_musica(arquivo)
# Resultado: "letra-musica_pt-br.docx" gerado com tradução
```

### Exemplo 3: Tradutor de Artigos
```python
# Exemplo de uso do tradutor de artigos
url = "https://example.com/artigo-em-ingles"
traducao_artigo = traduzir_artigo(url)
print(traducao_artigo)  # Artigo traduzido exibido em Markdown
```

---

## 🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

---

## 📄 Licença
Este projeto é licenciado sob a [MIT License](LICENSE).
