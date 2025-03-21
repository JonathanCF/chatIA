# ChatIA 🤖

O **ChatIA** é um assistente virtual inteligente que utiliza tecnologias avançadas de processamento de linguagem natural (NLP) para responder perguntas com base em conteúdos fornecidos pelo usuário. Ele pode aprender a partir de PDFs, vídeos do YouTube, sites ou arquivos Excel, garantindo respostas precisas e contextualizadas.

## Funcionalidades Principais

- **Chat Interativo**: Converse com o ChatIA e obtenha respostas baseadas no conteúdo fornecido.
- **Suporte a Múltiplas Fontes de Dados**:
  - **PDFs**: Carregue arquivos PDF para o ChatIA estudar.
  - **YouTube**: Forneça URLs de vídeos do YouTube para extrair e analisar o conteúdo.
  - **Sites**: Insira URLs de sites para o ChatIA aprender com o conteúdo da página.
- **Respostas Contextuais**: O ChatIA responde apenas com base no conteúdo fornecido, recusando educadamente perguntas fora do escopo.
- **Interface Amigável**: Desenvolvido com **Streamlit**, oferece uma experiência de usuário simples e intuitiva.

## Como Usar

1. **Selecione a Fonte de Dados**:
   - No menu lateral, escolha entre **Site**, **PDF** ou **YouTube**
   - Carregue o arquivo ou insira a URL correspondente.

2. **Inicie a Conversa**:
   - Após carregar o conteúdo, digite suas perguntas no campo de chat.
   - O ChatIA responderá com base no material fornecido.

3. **Reiniciar Conversa**:
   - Use o botão **🔄 Reiniciar Conversa** no menu lateral para começar uma nova interação.

## Tecnologias Utilizadas

- **Streamlit**: Para a interface gráfica do usuário.
- **LangChain**: Para integração com modelos de linguagem e processamento de documentos.
- **ChatGroq**: Para interação com o modelo de linguagem **LLaMA 3.1**.
- **dotenv**: Para gerenciamento de variáveis de ambiente.

## Requisitos

- Python 3.8 ou superior.
- Bibliotecas listadas no arquivo `requirements.txt`.

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/chatia.git
   cd chatia
