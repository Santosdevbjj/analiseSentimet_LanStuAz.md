## Azure Speech Studio e o Azure Language Studio, projeto lúdico para ensino de matemática e português para crianças da APAE Belo Horizonte MG. Implementando a funcionalidade de Analise de Sentimentos.


![Screenshot_20250529-161700](https://github.com/user-attachments/assets/14f4fc33-1d96-4ef7-8f78-c10ea9a2f8c5)



## 🎙️ Azure Speech Studio

O Azure Speech Studio é uma plataforma baseada na web que permite criar, testar e implantar soluções de fala, como conversão de texto em fala (TTS), reconhecimento de fala (STT) e criação de vozes personalizadas, sem necessidade de codificação.

Principais Funcionalidades

1. Conversão de Texto em Fala (TTS)

**Descrição:** Transforma texto escrito em fala natural.

**Exemplo Prático:** Criar um assistente virtual que lê mensagens para usuários com deficiência visual.

**Detalhes Técnicos:** Utiliza modelos de voz neural, como a voz "Francisca" para português do Brasil, que oferece entonação e prosódia naturais  .


## 2. Conversão de Fala em Texto (STT)

**Descrição:** Transcreve fala em texto escrito.

**Exemplo Prático:** Transcrever reuniões corporativas para documentação.

**Detalhes Técnicos:** Estudos mostram que o serviço da Microsoft apresenta uma taxa de erro de transcrição de 9,09% em ambientes silenciosos, demonstrando alta precisão  .


## 3. Voz Neural Personalizada

**Descrição:** Permite criar vozes digitais exclusivas para sua marca.

**Exemplo Prático:** Desenvolver uma voz única para um assistente de voz corporativo.

**Detalhes Técnicos:** Requer gravações de alta qualidade e scripts específicos. O processo envolve etapas como criação de projeto, configuração do talento de voz, preparação de dados de treinamento, treinamento do modelo e implantação  .


## 4. Avaliação de Pronúncia

**Descrição:** Avalia a pronúncia de usuários, útil para aplicativos educacionais.

**Exemplo Prático:** Aplicativos de aprendizado de idiomas que fornecem feedback sobre a pronúncia do usuário. 


## Como Utilizar na Prática

**1. Acesse o Azure Speech Studio.**


2. Escolha a funcionalidade desejada (TTS, STT, Voz Personalizada, etc.).


## 3. Para TTS:

Digite o texto que deseja converter.

Selecione a voz e o idioma desejados.

Clique em "Reproduzir" para ouvir a conversão.


## 4. Para STT:

Faça upload de um arquivo de áudio ou grave diretamente.

O sistema transcreverá automaticamente o conteúdo.


## 5. Para Voz Personalizada:

Siga as etapas de criação de projeto, upload de gravações e treinamento do modelo conforme descrito na documentação  .


## 🧠  Azure Language Studio

O Azure Language Studio é uma interface gráfica que facilita a criação, treinamento e implantação de modelos de Processamento de Linguagem Natural (PLN) para análise de texto, compreensão de linguagem conversacional, extração de informações e muito mais.

## Principais Funcionalidades

# 1. Compreensão de Linguagem Conversacional

**Descrição:** Interpreta intenções e entidades em interações de linguagem natural.

**Exemplo Prático:*" Desenvolver chatbots que entendem e respondem a perguntas de clientes.

**Detalhes Técnicos:** Permite criar esquemas, rotular enunciados e treinar modelos personalizados  .


## 2. Reconhecimento de Entidades Nomeadas (NER)

**Descrição:** Identifica e classifica entidades mencionadas em texto (como nomes de pessoas, organizações, datas).

**Exemplo Prático:** Extrair informações relevantes de documentos jurídicos. 


## 3. Análise de Sentimento

**Descrição:** Determina o sentimento (positivo, negativo, neutro) expressado em um texto.

**Exemplo Prático:** Monitorar a opinião pública sobre um produto nas redes sociais. 


## 4. Resumo de Texto

**Descrição:** Gera resumos concisos de textos longos.

**Exemplo Prático:** Resumir artigos de notícias para aplicativos de leitura rápida. 


## Como Utilizar na Prática

## 1. Acesse o Azure Language Studio.


2. Escolha a funcionalidade desejada (Compreensão de Linguagem, NER, Análise de Sentimento, etc.).


3. Para Compreensão de Linguagem Conversacional:

Crie um novo projeto e defina as intenções e entidades.

Adicione enunciados de exemplo para cada intenção.

Treine o modelo e implante-o para uso em aplicativos  .



## 4. Para NER ou Análise de Sentimento:

Insira o texto que deseja analisar.

O sistema retornará as entidades identificadas ou a análise de sentimento correspondente. 



## 📊 Considerações Técnicas e Científicas

**Precisão de Transcrição:** Estudos demonstram que o serviço de conversão de fala em texto da Microsoft apresenta alta precisão, mesmo em ambientes com ruído de fundo  .

**Personalização de Voz:** A criação de vozes personalizadas permite que empresas desenvolvam identidades sonoras únicas, melhorando a experiência do usuário e reforçando a marca  .

**Processamento de Linguagem Natural:** O Azure Language Studio integra técnicas avançadas de PLN, facilitando a análise e compreensão de grandes volumes de texto de forma eficiente  .



 
Está implementação irá usar o **Azure Speech Studio e o Azure Language Studio**, para atender crianças da **APAE - de Belo Horizonte MG - Associação de Pais e Amigos dos Excepcionais.**

As crianças têm desenvolvimento mental atrasado, e necessitam ser estimuladas no seu dia a dia. 

O que eu tenho em mente, é algo para **ensinar matemática da tabuada básica: adição, subtração, multiplicação e divisão.**

E também **ensinar português: sinônimos,  antônimos.** Creio que isso será de imensa ajuda para as crianças da APAE. 



## 🎯 Objetivo

Criar uma aplicação interativa que utilize recursos de fala e linguagem natural para estimular o aprendizado de forma lúdica e acessível, considerando as necessidades específicas das crianças atendidas pela APAE. 



## 🛠️ Ferramentas Utilizadas

**Azure Speech Studio:** Para conversão de texto em fala (Text-to-Speech) e reconhecimento de fala (Speech-to-Text). 

**Azure Language Studio:** Para compreensão de linguagem natural, identificação de sinônimos e antônimos. 



## 🧩 Estrutura da Solução

# 1. Módulo de Matemática

**Funcionalidades:**

Apresentação de operações matemáticas básicas com feedback auditivo. 

Reconhecimento de respostas faladas pelas crianças. 


## Implementação:

**Azure Speech Studio:**

Utilize o recurso de Text-to-Speech para converter enunciados como "Quanto é 2 mais 3?" em áudio. 

Configure o Speech-to-Text para transcrever as respostas faladas pelas crianças. 


## Lógica de Verificação:

Compare a resposta transcrita com a resposta correta. 

Forneça feedback positivo ou encorajador conforme a resposta. 


## Exemplo de Fluxo:

**1. O sistema diz:** "Quanto é 4 vezes 2?" 


**2. A criança responde:** "Oito". 


**3. O sistema reconhece a resposta e responde:** "Muito bem! 4 vezes 2 é igual a 8." 



## 2. Módulo de Português

# Funcionalidades:

Apresentação de palavras para identificação de sinônimos e antônimos. 

Feedback auditivo com explicações simples. 


## Implementação:

**Azure Language Studio:**

Utilize o serviço de Compreensão de Linguagem Natural para identificar sinônimos e antônimos. 


## Azure Speech Studio:

Converta as instruções e feedbacks em áudio para facilitar a compreensão. 



## Exemplo de Fluxo:

**1. O sistema diz:** "Qual é o antônimo de 'feliz'?" 


**2. A criança responde:** "Triste". 


**3. O sistema reconhece a resposta e responde:** "Correto! O antônimo de 'feliz' é 'triste'." 



## 🎨 Interface e Usabilidade

Desenvolva uma interface com elementos visuais atrativos e botões grandes para facilitar a interação. 

Utilize cores vivas e personagens animados para manter o engajamento das crianças. 

Inclua opções de repetição de perguntas e dicas para auxiliar no aprendizado. 





📈 Benefícios Esperados

Estimulação cognitiva através de atividades interativas. 

Melhoria na compreensão de conceitos básicos de matemática e português. 

Desenvolvimento da autonomia e confiança das crianças ao interagirem com a tecnologia. 



🚀 Próximos Passos

1. Prototipagem: Desenvolver um protótipo da aplicação utilizando as ferramentas mencionadas. 


2. Testes Piloto: Implementar o protótipo em ambiente controlado com acompanhamento de profissionais da APAE. 


3. Ajustes e Melhorias: Coletar feedbacks e realizar ajustes para melhor atender às necessidades das crianças. 


4. Escalonamento: Expandir a aplicação para outras unidades da APAE e adaptar para diferentes faixas etárias e níveis de desenvolvimento.







## Protótipo inicial.



Vamos  criar  um protótipo interativo utilizando o Azure Speech Studio e o Azure Language Studio para **auxiliar no ensino de matemática básica e português para crianças da APAE BH.**

Este protótipo será adaptado às necessidades específicas dessas crianças, proporcionando uma experiência lúdica e acessível.




## 🧩 Etapa 1: Configuração do Ambiente no Azure



## 1.1 Criar uma Conta no Azure


Acesse o Portal do Azure e crie uma conta gratuita, caso ainda não possua. 



## 1.2 Criar Recursos Necessários



## Recurso de Fala:


No portal do Azure, vá em "Criar um recurso" e selecione "Serviço de Fala".



Escolha a região mais próxima (por exemplo, "Brasil Sul") e um nome identificador. 


## Recurso de Linguagem:


No portal do Azure, vá em "Criar um recurso" e selecione "Serviço de Linguagem".



Configure conforme as necessidades do projeto. 


## 🎙️ Etapa 2: Utilizando o Azure Speech Studio



## 2.1 Acessar o Speech Studio



Acesse o Azure Speech Studio e faça login com sua conta do Azure. 


## 2.2 Criar Conteúdo de Áudio



Utilize a ferramenta de Criação de Conteúdo de Áudio para converter texto em fala. 



## Exemplo de Frase para Matemática:


**Texto:** "Quanto é 2 mais 3?"


Selecione a voz "Francisca" para português do Brasil.



Ajuste a entonação e velocidade conforme necessário. 



## Exemplo de Frase para Português:


**Texto:** "Qual é o antônimo de 'feliz'?"



Utilize a mesma voz e faça os ajustes necessários. 


## 2.3 Exportar Áudio


Após gerar o áudio, faça o download dos arquivos para utilização na aplicação. 



**🧠 Etapa 3:** Utilizando o Azure Language Studio



## 3.1 Acessar o Language Studio



Acesse o Azure Language Studio e faça login com sua conta do Azure. 



## 3.2 Criar Projeto de Compreensão de Linguagem



Siga o Guia de Início Rápido para criar um projeto de compreensão de linguagem conversacional. 


## 3.3 Definir Intenções e Entidades


## Intenções:


"Responder Operação de Adição"


"Responder Antônimo" 



## Entidades:


Números (para operações matemáticas)


Palavras (para sinônimos e antônimos) 


## 3.4 Treinar e Publicar o Modelo


Após definir as intenções e entidades, treine o modelo e publique-o para utilização na aplicação. 



**🖥️ Etapa 4:** Desenvolver a Interface da Aplicação



## 4.1 Escolher a Plataforma de Desenvolvimento


Opte por uma plataforma que permita o desenvolvimento de interfaces acessíveis, como o Power Apps ou desenvolvimento web com HTML, CSS e JavaScript. 


## 4.2 Integrar Funcionalidades


#$ Reproduzir Áudio:


Utilize os arquivos de áudio gerados no Speech Studio para apresentar as perguntas. 


## Capturar Respostas:


Implemente a funcionalidade de reconhecimento de fala para capturar as respostas das crianças. 


## Processar Respostas:


Envie as respostas capturadas para o modelo do Language Studio para análise e verificação. 

## Fornecer Feedback:


Com base na análise, forneça feedback positivo ou encorajador, utilizando novamente o recurso de conversão de texto em fala. 


**📊 Etapa 5:**  Testar e Ajustar o Protótipo



## 5.1 Realizar Testes com Usuários


Apresente o protótipo para um grupo de crianças da APAE e observe a interação. 


## 5.2 Coletar Feedback


Converse com os educadores e terapeutas para obter insights sobre a eficácia e possíveis melhorias. 


## 5.3 Implementar Melhorias


Com base no feedback, ajuste a interface, entonação das vozes e complexidade das perguntas para melhor atender às necessidades das crianças. 


## 🚀 Próximos Passos


Expandir o conteúdo com mais operações matemáticas e vocabulário de português. 


Implementar um sistema de progressão para acompanhar o desenvolvimento das crianças. 


Explorar a criação de vozes personalizadas para tornar a experiência ainda mais envolvente.  





**Vamos elaborar um plano de aula** detalhado que integra o protótipo desenvolvido com o Azure Speech Studio e o Azure Language Studio, incorporando a funcionalidade de Análise de Sentimentos para **auxiliar no ensino de matemática básica e português para crianças da APAE.** 



## 🎯 Objetivo da Aula

Proporcionar uma experiência de aprendizado interativa e inclusiva, utilizando tecnologias de inteligência artificial para estimular o desenvolvimento cognitivo de crianças com necessidades especiais, focando em: 

Operações matemáticas básicas: adição, subtração, multiplicação e divisão. 

Conceitos de português: sinônimos e antônimos. 

Expressão emocional e reconhecimento de sentimentos. 


## ⏰ Duração

Aproximadamente 60 minutos. 



## 🧑‍🏫 Público-Alvo

Crianças atendidas pela APAE, com idades entre 7 e 12 anos, com desenvolvimento mental atrasado. 



## 🛠️ Recursos Necessários

Computador ou tablet com acesso à internet. 

Microfone e alto-falantes ou fones de ouvido. 

Acesso ao Azure Speech Studio e ao Azure Language Studio. 

Protótipo da aplicação interativa desenvolvido previamente. 



## 📋 Estrutura da Aula

1. Boas-vindas e Introdução (10 minutos)

Cumprimente as crianças de forma calorosa. 

Explique que a aula será uma brincadeira divertida com o "Amigo Virtual", que ajudará a aprender matemática e português. 

Apresente o "Amigo Virtual" (personagem animado com voz gerada pelo Azure Speech Studio). 


## 2. Atividade de Matemática (15 minutos)

O "Amigo Virtual" faz perguntas simples, como: 

"Quanto é 2 mais 3?" 

"Quanto é 5 menos 2?" 


A criança responde verbalmente. 

Utilize o Speech-to-Text para transcrever a resposta. 

Verifique a resposta e forneça feedback positivo ou encorajador. 


## 3. Atividade de Português (15 minutos)

O "Amigo Virtual" propõe desafios: 

"Qual é o sinônimo de 'alegre'?" 

"Qual é o antônimo de 'triste'?" 


A criança responde verbalmente. 

Utilize o Speech-to-Text para transcrever a resposta. 

Verifique a resposta e forneça feedback apropriado. 


## 4. Expressando Sentimentos (10 minutos)

O "Amigo Virtual" pergunta: 

"Como você está se sentindo hoje?" 


A criança responde livremente. 

Utilize a funcionalidade de Análise de Sentimentos do Azure Language Studio para identificar o sentimento expresso. 

Forneça feedback empático, por exemplo: 

"Fico feliz que você esteja se sentindo bem!" 

"Sinto muito que você esteja triste. Estou aqui para ajudar!" 



## 5. Encerramento e Feedback (10 minutos)

Reforce os aprendizados do dia. 

Pergunte o que as crianças mais gostaram. 

Agradeça a participação e destaque que o "Amigo Virtual" estará disponível para futuras interações. 



## 📈 Avaliação e Monitoramento

Registre as respostas das crianças para acompanhar o progresso individual. 

Utilize os dados da Análise de Sentimentos para entender o estado emocional das crianças ao longo do tempo. 

Adapte as atividades futuras com base nos resultados observados. 



## 🔗 Recursos Adicionais

Guia de Análise de Sentimentos com Azure AI Language Studio 

Documentação Oficial do Azure AI Text Analysis 





**Vamos elaborar materiais visuais** adaptados e ajustar o protótipo para **atender às necessidades específicas das crianças da APAE**, considerando a funcionalidade de Análise de Sentimentos do Azure Language Studio.



## 🎨 1. Criação de Materiais Visuais Adaptados

Para crianças com deficiência intelectual, é essencial utilizar materiais que sejam visuais, táteis e interativos. Aqui estão algumas sugestões:

## 📘 a) Cartazes Coloridos com Figuras

**Objetivo:** Auxiliar na associação de conceitos matemáticos e linguísticos com imagens. 

**Exemplo:** Um cartaz com a operação "2 + 3" ilustrada com duas maçãs de um lado e três do outro, totalizando cinco maçãs. 


## 🧩 b) Jogos de Associação

**Objetivo:** Estimular o raciocínio lógico e a compreensão de sinônimos e antônimos. 

**Exemplo:** Cartas com palavras e imagens correspondentes para que a criança associe "feliz" com "contente" (sinônimo) ou "triste" (antônimo). 


## 🎲 c) Materiais Táteis

**Objetivo:** Proporcionar estímulos sensoriais que auxiliem na aprendizagem. 

**Exemplo:** Números e letras em EVA ou feltro para que as crianças possam tocar e manipular. 


Para mais ideias e modelos de atividades adaptadas, você pode consultar recursos como o Portal Tudo Sala de Aula e o Mundo Indica. 



## 🤖 2. Adaptação do Protótipo para Necessidades Específicas

# 🧠 a) Simplificação da Linguagem

**Objetivo:** Tornar as interações mais compreensíveis para as crianças. 

Ação: Utilizar frases curtas e vocabulário simples nas perguntas e instruções do protótipo. 


## 🎤 b) Feedback Auditivo Personalizado

**Objetivo:** Fornecer respostas que incentivem e motivem as crianças. 

**Ação:*" Utilizar o Azure Speech Studio para criar áudios com entonação amigável, como "Muito bem!" ou "Vamos tentar novamente juntos!". 


## 📊 c) Integração da Análise de Sentimentos

**Objetivo:** Monitorar o estado emocional das crianças durante as interações. 

**Ação:** Implementar a funcionalidade de Análise de Sentimentos do Azure Language Studio para avaliar as respostas verbais das crianças e ajustar as interações conforme necessário. 


## 🖥️ d) Interface Visual Intuitiva

**Objetivo:** Facilitar a navegação e a compreensão das atividades. 

**Ação:** Desenvolver uma interface com ícones grandes, cores contrastantes e imagens representativas das atividades. 



## 📌 Conclusão

Ao combinar materiais visuais adaptados com um protótipo interativo e sensível às necessidades emocionais das crianças, podemos criar uma experiência de aprendizagem inclusiva e eficaz. 





A seguir, apresento um **guia técnico detalhado para implementar um projeto educacional interativo utilizando o Azure Speech Studio e o Azure Language Studio,** com foco na Análise de Sentimentos, adaptado às **necessidades específicas das crianças atendidas pela APAE.**



## 🧠 Visão Geral do Projeto

Objetivo: Desenvolver uma aplicação interativa que auxilie no ensino de matemática básica e português, utilizando recursos de fala e análise de sentimentos para adaptar o conteúdo às emoções e necessidades das crianças. 



## 🛠️ Etapas Técnicas de Implementação

**1. Configuração dos Recursos no Azure**

**a) Criar uma Conta no Azure**

Acesse o Portal do Azure e crie uma conta gratuita, caso ainda não possua. 


**b) Criar os Serviços Necessários**

Serviço de Fala (Speech Service):

No portal do Azure, vá em "Criar um recurso" e selecione "Serviço de Fala".

Escolha a região mais próxima (por exemplo, "Brasil Sul") e um nome identificador. 


## Serviço de Linguagem (Language Service):

No portal do Azure, vá em "Criar um recurso" e selecione "Serviço de Linguagem".

Configure conforme as necessidades do projeto. 



## 2. Desenvolvimento da Aplicação Interativa

**a) Escolha da Plataforma de Desenvolvimento**

Opte por uma plataforma que permita o desenvolvimento de interfaces acessíveis, como o Power Apps ou desenvolvimento web com HTML, CSS e JavaScript. 


**b) Funcionalidades da Aplicação**

Apresentação de Conteúdo:

Utilize o Azure Speech Studio para converter textos educativos em áudios com vozes naturais. 


## Interação com o Usuário:

Implemente a funcionalidade de reconhecimento de fala para capturar as respostas das crianças. 


## Análise de Sentimentos:

Utilize o Azure Language Studio para analisar o sentimento das respostas das crianças, adaptando o conteúdo conforme necessário. 


## Feedback Personalizado:

Forneça feedback positivo ou encorajador com base na análise de sentimentos, utilizando novamente o recurso de conversão de texto em fala. 


## 3. Análise de Sentimentos com Azure Language Studio

**a) Configuração da Análise de Sentimentos**

Acesse o Azure Language Studio e selecione "Análise de Sentimento". 

Configure o idioma como "Português" e insira os textos para análise. 


**b) Integração com a Aplicação**

Utilize a API REST do Azure para enviar as respostas das crianças para análise de sentimentos. 

Baseie-se na documentação oficial para implementar essa funcionalidade. 



## 4. Adaptação às Necessidades das Crianças da APAE

**a) Interface Acessível**

Desenvolva uma interface com ícones grandes, cores contrastantes e imagens representativas das atividades. 


**b) Conteúdo Personalizado**

Utilize exemplos do cotidiano das crianças para tornar o conteúdo mais relevante e compreensível. 


**c) Feedback Empático**

Baseie-se na análise de sentimentos para fornecer feedbacks que incentivem e motivem as crianças, adaptando o conteúdo conforme o estado emocional detectado. 


## 📊 Monitoramento e Avaliação

Registre as interações das crianças com a aplicação para acompanhar o progresso individual. 

Utilize os dados da análise de sentimentos para entender o estado emocional das crianças ao longo do tempo. 

Adapte as atividades futuras com base nos resultados observados. 



## 🔗 Recursos Adicionais

Guia de Análise de Sentimentos com Azure AI Language Studio 

Documentação Oficial do Azure AI Text Analysis 



 

 




