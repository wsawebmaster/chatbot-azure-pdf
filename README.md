# 🚀 Chatbot Baseado em Conteúdo de PDFs no Azure  

## 📌 Visão Geral  
Este projeto tem como objetivo criar um **chatbot interativo** que responde com base no conteúdo de arquivos PDF. Utilizaremos **IA generativa, embeddings e buscas vetorizadas** para estruturar um sistema capaz de entender, processar e responder perguntas a partir de documentos específicos.  

Essa abordagem permitirá que você crie um modelo personalizado de **assistência virtual**, focado em um conjunto de informações proprietárias, sem depender unicamente do conhecimento geral de modelos pré-treinados.  

---

## 🎯 Cenário  
Imagine que você é um **estudante de Engenharia de Software**, prestes a escrever seu **Trabalho de Conclusão de Curso (TCC)**. Para isso, você precisa revisar e correlacionar diversos artigos científicos. Entretanto, à medida que acumula mais documentos, torna-se cada vez mais difícil **extrair informações relevantes e conectar ideias entre diferentes textos**.  

Diante desse desafio, você decide utilizar **inteligência artificial** para facilitar esse processo, criando um **sistema de busca inteligente** capaz de interpretar os PDFs, organizar informações e gerar respostas relevantes com base no conteúdo carregado.  

---

## 🎯 Objetivo  
O objetivo deste projeto é permitir que você:  

✅ **Carregue arquivos PDF** contendo informações relevantes para seu estudo ou projeto.  
✅ **Implemente um sistema de busca vetorial** para indexar e recuperar informações dos PDFs.  
✅ **Utilize inteligência artificial** para gerar respostas baseadas no conteúdo dos documentos carregados.  
✅ **Desenvolva um chat interativo** onde seja possível realizar perguntas e obter respostas contextuais fundamentadas nos arquivos.  

---

## 🛠️ Tecnologias Utilizadas  
- **Azure OpenAI** (para IA generativa)  
- **Azure Cognitive Search** (para buscas vetorizadas)  
- **Azure Storage** (para armazenar PDFs)  
- **Python** (para processamento de dados)  
- **LangChain** (para integração de IA)  
- **FastAPI** (para criar a API do chatbot)  
- **Streamlit** (para interface interativa)  

---

## 🚀 Passos para Criar o Chatbot  

### 1️⃣ **Configurar o Ambiente no Azure**  
1. **Criar um Workspace no Azure Machine Learning**  
   - Acesse o [Portal do Azure](https://portal.azure.com/)  
   - Crie um **Azure Machine Learning Workspace**  
   - Configure permissões e recursos necessários  

2. **Configurar o Azure OpenAI**  
   - Solicite acesso ao **Azure OpenAI**  
   - Crie um recurso **Azure OpenAI**  
   - Gere uma **chave de API** para integração  

3. **Criar um Armazenamento para PDFs**  
   - Configure um **Azure Blob Storage**  
   - Crie um **container** para armazenar os arquivos PDF  

---

### 2️⃣ **Processar os PDFs e Criar Embeddings**  
1. **Extrair texto dos PDFs** usando `PyMuPDF` ou `pdfplumber`  
2. **Gerar embeddings** com `OpenAI Embeddings`  
3. **Armazenar embeddings** no **Azure Cognitive Search**  

---

### 3️⃣ **Criar o Chatbot Interativo**  
1. **Desenvolver uma API** com `FastAPI` para processar perguntas  
2. **Integrar IA generativa** com `LangChain`  
3. **Criar uma interface** com `Streamlit` para interação  

---

## 📊 Exemplo de Fluxo do Sistema  
1️⃣ **Usuário faz upload de PDFs**  
2️⃣ **O sistema processa e indexa os documentos**  
3️⃣ **Usuário faz perguntas no chat**  
4️⃣ **O chatbot busca informações nos PDFs e responde**  

---

## 📌 Insights Obtidos  
- A IA pode identificar **temas principais** e **relações entre frases**.  
- O aprendizado de máquina permite **classificação automática** de textos.  
- O processamento de linguagem natural ajuda a **responder perguntas** com base no conteúdo.  

---

## 🚀 Possibilidades Futuras  
- Criar um chatbot baseado nos textos.  
- Implementar busca semântica para encontrar informações rapidamente.  
- Utilizar IA para **resumir** documentos extensos.  

---
---

## 📧 Contato

[LinkedIn](https://www.linkedin.com/in/wsawebmaster/)

[wsawebmaster@yahoo.com.br](mailto:wsawebmaster@yahoo.com.br)