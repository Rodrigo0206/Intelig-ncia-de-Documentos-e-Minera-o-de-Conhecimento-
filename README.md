# Inteligencia-de-Documentos-e-Mineraçao-de-Conhecimento-
resumo da aula de Inteligência de Documentos e Mineração de Conhecimento 

# Inteligência de Documentos e Mineração de Conhecimento

Assisti às aulas sobre **Inteligência de Documentos e Mineração de Conhecimento no Azure** e tive a oportunidade de explorar na prática os conceitos apresentados, além de fazer alguns comentários nas imagens anexadas.

Durante o conteúdo, compreendi como o **Azure AI Document Intelligence** permite extrair dados estruturados de documentos, identificar regiões de interesse e utilizar modelos pré-construídos (como para faturas, recibos e identificadores) ou modelos personalizados treinados com documentos próprios da organização. A plataforma oferece ainda uma análise semântica dos formulários, indo além da simples leitura de texto.

Também vi o **Document Intelligence Studio**, que permite testar tudo isso de forma intuitiva e sem necessidade de programação, bastando criar os recursos e escolher modelos para análise.

Na parte de **Pesquisa Cognitiva do Azure**, entendi como a plataforma usa mineração de conhecimento com IA para transformar documentos como PDFs e anotações manuscritas em dados pesquisáveis. O processo envolve ingestão de dados, enriquecimento com IA (como reconhecimento de entidades, tradução e análise de sentimentos), indexação e exploração via mecanismos de busca e visualização.

Essa combinação de ferramentas permite às organizações automatizar o entendimento de grandes volumes de documentos, tornando o conteúdo mais acessível, útil e eficiente para a tomada de decisões.

---

## 📋 Tópicos abordados nas aulas

### Agenda
- Inteligência de Documentos de IA do Azure
- Pesquisa Cognitiva do Azure

### Objetivos de Aprendizado
- Entender o que o Azure AI Document Intelligence faz e por que as organizações o utilizam.
- Descrever a mineração de conhecimento e os problemas que ela resolve.

---

## 🧠 Inteligência de Documentos de IA do Azure

### Serviços de inteligência de documentos de IA – Análise de documentos
- Retorna representações de dados estruturados.
- Regiões de interesse e relacionamentos.
- Configurar opções de análise para análise gratuita e cobrada.

### Modelos pré-construídos
- Faturas
- Recibos
- Identificadores
- Reconhece e extrai pares de valores-chave.

### Modelos personalizados
- Treine modelos com pelo menos cinco dados de amostra.
- Identifique campos de interesse para sua organização.

### Analisando formulários com o serviço Document Intelligence
- Extraia informações de formulários digitalizados em formato de imagem ou PDF.
- Use modelos pré-treinados para documentos como faturas, recibos, IDs, etc.
- Treine um modelo personalizado com seus próprios formulários.
- Os modelos realizam reconhecimento semântico – não apenas extração de texto.

---

## 🛠 Estúdio de Inteligência de Documentos

- Uso sem código.
- Permite explorar funcionalidades com exemplos ou seus próprios documentos.

**Etapas:**
1. Criar um recurso:
   - Recurso de Inteligência de Documentos
   - Recurso de serviços de IA
2. Habilitar no Document Intelligence Studio.
3. Na página de primeiros passos, selecionar um modelo para experimentar.

---

## 🔍 Pesquisa Cognitiva do Azure

- Os dados geralmente estão bloqueados em PDFs, documentos e notas manuscritas.
- A mineração de conhecimento encontra insights em larga escala.
- O Azure Cognitive Search é a plataforma de mineração de conhecimento alimentada por IA.

### Soluções de Pesquisa Cognitiva do Azure

#### Ingestão de dados
- Azure Blob Storage containers
- Azure Data Lake Storage Gen2
- Azure Table Storage

#### Enriquecimento e indexação de IA
- Permite uma compreensão mais profunda com:
  - Visão computacional
  - Processamento de linguagem natural
- A indexação torna o conteúdo pesquisável

#### Exploração
- Pesquisa em índices
- Acesso via aplicativos
- Visualizações de dados

---

### Enriquecimento de IA

- Torna o conteúdo mais útil para fins de pesquisa.
- Criado por conjuntos de habilidades como:
  - Reconhecimento de entidades
  - Tradução de texto
  - Análise de sentimento

Os documentos enriquecidos:
- São utilizados durante a indexação
- Têm seus dados serializados e enviados ao mecanismo de pesquisa




