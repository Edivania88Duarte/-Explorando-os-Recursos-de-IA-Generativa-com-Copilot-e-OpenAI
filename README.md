# Explorando-os-Recursos-de-IA-Generativa-com-Copilot-e-OpenAI
Teste 5 do Bootcamp Azure Fundamentals AI 900 da DIO


<h1>IA Generativa</h1>
<br>

## O que é IA generativa?

<b>IA:</b> Imita o comportamento humano usando aprendizado de máquina para interagir com o ambiente e executar tarefas sem instruções explícitas sobre o que gerar.
<br>
<br>

<b>IA generativa:</b> cria conteúdo original, como IA gerativa que foi incorporada a aplicativos de chat. Os aplicativos de IA gerativa usam entrada em linguagem natural e retornam respostas apropriadas em uma variedade de formatos:
<br>

 - Geração de linguagem natural (onde se pode trazer uma instrução, como melhorar ou criar um texto no chat GPT)
<br>

 - Geração de cógido (ajuda na automação e processo de aprendizado)
<br>

 - Geração de imagem (impagens pixar ou de persona através de instruções passadas para a IA)
<br>
<br>

## Modelos de linguagem grandes

Os aplicativos de IA gerativa são alimentados por LLMs (modelo de linguagem grandes), que são um tipo especializado de modelo de machine learning que você pode usar para executar tarefas de PLN (processamento de linguagem natural), incluindo:
<br>
<br>
 - Determinar sentimento ou classimar de outra forma o texto em idioma natural.
 - Resumir um texto.
 - Comparar várias fontes de texto quanto à similaridade semântica.
 - Geração de nova linguagem natural.
<br>
<br>

## Modelos de linguagem grandes - transformador

A arquitetura do modelo do transformador consiste em dois componentes principais, ou blocos:
<br>
 - Um bloco codificador que cria representações semânticas do vocabulários de treinamento.
 - Um bloco decodificador que gera novas sequências de linguagem.
 - O texto é tokenizado para que cada palabra ou frase seja representada por um token numérico exclusivo.
 - Inserções (valores de vetor com várias dimensões) são atribuídas aos tokens.
 - As camadas de atenção examinam cada token por vez e determinam valores incorporados que refletem os relacionamentos semânticos entre os tokens.
 - No decodificador, essas relações são usadas para prever a sequência mais provável de tokens.
<br>

![Imagem do WhatsApp de 2024-04-20 à(s) 18 47 01_f4a1c3fd](https://github.com/Edivania88Duarte/-Explorando-os-Recursos-de-IA-Generativa-com-Copilot-e-OpenAI/assets/120994730/4db12138-34bc-47ce-957f-38b349105109)

<br>

## Modelos de linguagem grandes - tokenização
<br>
<i>Etapa 1: tokenização </i> 

 - A primeira etapa no treinamento de um modelo de transformador é decompor o texto de treinamento de tokens.
<br>

<i> Etapa 2: inserções ou incorporações </i> 

 - As inserções entre tokens são capturadas como vetores, conhecidos como inserções.
<br>

![Imagem do WhatsApp de 2024-04-20 à(s) 20 16 52_48965502](https://github.com/Edivania88Duarte/-Explorando-os-Recursos-de-IA-Generativa-com-Copilot-e-OpenAI/assets/120994730/335c5321-a9a4-4876-89b5-3db6cb8e306a)

<br>

## Modelos de linguagem grandes - atenção
<br>
 <i>Etapa 3:</i> 
 - Captura a força das relações entre tokens usando a técnica de atenção. 
<br>

![Imagem do WhatsApp de 2024-04-20 à(s) 20 24 24_80ea460b](https://github.com/Edivania88Duarte/-Explorando-os-Recursos-de-IA-Generativa-com-Copilot-e-OpenAI/assets/120994730/13bb4296-cf2c-46c1-b10a-70acc1fd837e)


<br>

## Copilotos
<br>

 - Os copilotos são frequentemente integrados a outros aplicativos e fornecem uma maneira para os usuários obterem ajuda com tarefas comuns a partir de um modelo generativo de IA.
<br>

 - Os desenvolvedores podem criar copilotos que enviam prompts para grandes modelos de linguagem e geram conteúdo para uso em aplicativos.
<br>
<br>

## Aprimorar as respostas de IA generativa com a engenharia de prompts

 - O termo engenharia de prompt descreve o processo de aprimoramento de prompts.
<br>

 - Os desenvolvedores que projetam aplicativos e consumidores que usam aplicativos podem aprimoar a qualidade das respostas da IA gerativa usando linguagem direta, mensagem do sistema, exemplos e/ou dados de fundamentação.
<br>

## Fundamentos do Serviço Azure OpenAI

O que é o OpenAI do Azure?

 - O Serviço OpenAI do Azure é a solução de nuvem da Microsoft para implantar, personalizar e hospedar modelos de linguagens grandes.
<br>
Os serviços OpenAI do Azure consiste em:
<br>

 - Modelos de IA gerativa predinidos.  
 - Funcionalidades de personalização.
 - Ferramentas integradas para detectar e mitigar casos de uso prejudiciais para que os usuários possam implementar a IA com responsabilidade.
 - Segurança corporativa com RBAC (controle de acesso baseado em função) e redes privadas.
 - 
<br>
É possível usar vários métodos para desenvolver soluções do Azure OpenAI:
<br>

 - Estúdio de IA do Azure;
 - API REST;
 - SDKs com suporte de CLI do Azure.


## Como usar o OpenAI do Azure

<b><i>Estúdio Azure OpenAI:</i></b>
<br>

 - Criar e implantar modelos de IA para aplicativos de software.
   
 - Alimentado por modelos de IA gerativa otimizados para tarefas diversas.
   
 - Modelos Azure OpenAI incluem: modelos GPT-4, GPT-3.5, Embeddings e DALL-E
   
<br>
<b><i>Playgrounds:</i></b>
<br>
 
 - Experimente modelos Azure OpenAI sem codificação
 
 - Use a configuração do assistente para instruir o modelo sobre como ele deve se comportar

<br>
Funcionalidade de linguagem natural do OpenAI do Azure
<br>

 - Os modelos de GPT (transformadores pré-treinados generativos) são excelentes para entender e criar linguagem natural.
 - Os modelos GPT traduzem linguagem natural ou trechos de código em código.
 - A geração de código vai além de apenas escrever código a partir de prompts em linguagem natural.
 - Os modelos de IA gerativa podem editar e criar imagens. O modelo que funciona com imagens é chamado DELL-E, que dá suporte à criação de imagem, edição de imagem e criação de variações de imagem.

<br>

<b>Geração de imagens:</b> Com o DALL-E é possível até solicitar uma imagem em um determinado estilo. Os estilos também podem ser usados para edições e variações.
<br>

<b>Editando uma imagem:</b> DALL-E pode editar a imagem conforme solicitado, alterando seu estilo, adicionando ou removendo itens ou gerando novo conteúdo para adicionar. 
<br>

<b>Variações de imagem:</b> Variação de imagem podem ser criadas fornecendo uma imagem especificando quantas variações da imagem você deseja.
<br>

## IA generativa responsável

Planejar uma solução de IA generativa responsável
<br>
 - As quatros fases do processo para desenvolver e implementar um plano de IA responsável são:
<br>

       Identificar, Medida, Mitigar e Operar

<br>
<br>

![Imagem do WhatsApp de 2024-04-21 à(s) 09 37 47_edfea694](https://github.com/Edivania88Duarte/-Explorando-os-Recursos-de-IA-Generativa-com-Copilot-e-OpenAI/assets/120994730/94c898d5-36fc-4dc4-bdcf-f876b8709ce0)


<br>

## Links: 

https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/12-generative-ai.html

<br>

https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/13-azure-openai.html

<br>

https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/14-azure-openai-content-filters.html

