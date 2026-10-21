
# Inteligência Artificial🤖

### O que é IA?

A inteligência artificial (IA) é um ramo da ciência da computação que busca criar sistemas que imitam ou simulam a inteligência humana.

Desde suas origens na década de 1950, a IA evoluiu significativamente e agora abreange uma série de técnicas e tecnologias, incluindo aprendizado de máquina, processamento de linguagem natural e visão computacional.

A IA está se tornando cada vez mais comum em nossas vidas cotidianas, alimentando tudo, desde assistentes virtuais como a Siri e a Alexa, e até carros autônomos e recomendações de filmes na Netflix.

### Como funciona a IA?

A IA opera através do aprendizado a partir dos dados.

Assim como os humanos aprendem com a experiência, os sistemas de IA aprendem com os dados.

Isso é chamado de “aprendizado de máquina”.

Por exemplo, um sistema de IA pode aprender a identificar imagens de gatos depois de analisar milhares de imagens de gatos.

### Datas

**Conferência de Dartmouth 1956** a IA é considerada como tendo nascido como um campo de estudo.

**Era do otimismo (décadas de 1950 e 1960) -** Há grandes expectativas em relação à chegada das mpáquinas inteligentes.

**Inverno da IA -** Um período de desilusão e redução de financiamento porque o progresso não correspondeu às expectativas. O **primeiro inverno** de 1974 a 1980 e o segundo inverno de 1987 a 1993 (com efeitos estendidos até o final da década de 1990
### Conceitos

**Machine Learning -** é um subconjunto da IA que foca em sistemas que aprendem com dados e melhoram sem serem explicitamente programados para cada regra. Em vez de escrever código do tipo “se isso, então aquilo”, você alimenta o algoritmo com dados e deixa que ele encontre padrões.

O **machine learning** se divide em três paradigmas principais, cada um adequado a um tipo de problema:

- **Aprendizado Supervisionado:** O mais comum nos negócios. Usa dados rotulados (pares entrada-saída) para treinar algoritmos. Por exemplo, você mostra ao modelo 1.000 e-mails rotulados como "Spam" ou "Não é spam", e ele aprende a classificar o próximo e-mail. Algoritmos comuns incluem regressão linear, K-Nearest Neighbors (KNN) e árvore de decisão.
- **Aprendizado não supervisionado:** O algoritmo recebe dados sem rótulos e precisa encontrar estruturas ou padrões ocultos por conta própria. É muito usado para segmentação de clientes (clustering). K-means e análise de componentes principais (PCA) estão entre os mais usados.
- **Reinforcement Learning (RL):** Seguindo um caminho diferente, o RL ensina agentes por tentativa e erro usando um sistema de recompensas e penalidades. Um agente de RL recebe feedback sobre sua interação com o ambiente e aprende gradualmente quais comportamentos maximizam recompensas acumuladas ao longo do tempo. É o método usado para treinar robôs e IAs de jogos avançadas, como a AlphaGo.

**Deep Learning -** É um subconjunto do aprendizado de máquina orientado por redes neurais de várias camadas cujo design é inspirado na estrutura do cérebro humano. Modelos de deep learning servem de base para a maioria das IAS de ultima geração atualmente. Ao contrário da lógica matemática explicitamente definida dos algoritmos de aprendizado de máquina tradicionais, as redes neurais artificiais dos modelos de deep learning abrangem muitas camadas interconectadas de "neurônios", onde cada uma realiza uma operação matemática.

**GANs (Redes adversárias generativas) -** Modelo de aprendizado de máquina projetado para gerar dados realistas ao aprender padrões com conjuntos de dados de treinamento existentes. Ela opera dentro de um framework de aprendizado não supervisionados, usando técnicas de deep learning, onde duas redes neurais trabalham em oposição: uma gera dados, enquanto a outra avalia se os dados são reais ou gerados. A arquitetura de GAN consiste em duas redes neurais profundas - redegeradora e rede discriminatória.  O processo de treinamento da GAN envolve o gerador iniciando com entradas aleatórias (ruído) e criando dados sintéticos, como imagens, texto ou som que imitam os dados reais do conjunto de treinamento fornecido. O discriminador avalia as amostras geradas e os dados do conjunto de treinamento e decide se são reais ou falsos. Ele atribui uma pontuação entre 0 e 1: uma pontuação de 1 significa que os dados parecem reais e uma pontuação de 0 significa que são falsos. A retropropagação é, então, usada para otimizar ambas as redes. Isso significa que o gradiente da função de perda é calculada de acordo com os parâmetros da rede, e esses parâmetros são ajustados para minimizar a perda. Em seguida, o gerador usa o feedback do discriminador para melhorar, tentando criar dados mais realistas.

**Modelos autorregressivos -** São uma classe de modelos de aprendizado de máquina (Machine Learning) que predizem automaticamente o próximo componente em uma sequência fazendo medições de entradas anteriores na sequência.

**GPT (Generative Pre-trained Transformer) -** São transformadores pré-treinados generativos, comumente conhecidos como GPT, são uma família de modelos de rede neural que usa a arquitetura de transformadores e são um avanço fundamental na IA que impulsiona aplicações de IA generativa, como o ChatGpt. Os modelos GPT oferecem ás aplicações capacidade de criar texto e conteúdo semelhantes aos humanos (imagens, músicas e muito mais) e responder perguntas de forma conversacional.

**VAE (Autocodificador Variacional) -** São modelos generativos usados no aprendizado de máquina (ML) para gerar novos dados na forma de *variações* dos dados de entrada nos quais foram treinados. Além disso, eles também executam tarefas comuns a outros autocodificadores, como a redução de ruído. Como todos os autocodificadores, os autocodificadores variacionais são modelos de deep learning compostos por um codificador que aprende a isolar as variáveis latentes importantes dos dados de treinamento e um decodificador que, então, utiliza essas variáveis latentes para reconstruir os dados de entrada. No entanto, enquanto a maioria das arquiteturas de autocodificadores codifica uma representação *discreta* e fixa de variáveis latentes, os VAEs codificam uma representação *contínua* e probabilística desse espaço latente. Isso permite que um VAE não apenas reconstrua com precisão a entrada original, mas também use inferência variacional para gerar novas amostras de dados que se assemelham aos dados de entrada originais.

**PLN (Processamento de Linguagem Natural) -** É uma tecnologia que permite que os computadores interpretem, manipulem e compreendam a linguagem humana. Atualmente, as organizações têm grandes volumes de dados de voz e texto de vários canais de comunicação, como e-mails, mensagens de texto, feeds de notícias de mídia social, vídeo, áudio e muito mais.

**Visão computacional -** É uma tecnologia que as máquinas usam para reconhecer imagens automaticamente e descrevê-las com precisão e eficiência. Governos e empresas usam a visão computacional para melhorar a segurança de ativos, locais e instalações.

**IA generativa -** São sistemas capazes de criar novos conteúdos a partir de grandes volumes de dados existentes. Elas aprendem padrões desses dados durante o treinamento e, com isso, conseguem gerar informações inéditas, porém baseadas nos exemplos previamente analisados.

**IA discriminativa -** Esses modelos não criam novos dados; em vez disso, aprendem a fronteira entre classes para classificar entradas ou prever valores futuros.

**IA subsimbólica -** é uma abordagem de inteligência artificial que aprende diretamente a partir de dados brutos e padrões numéricos, sem usar regras ou símbolos lógicos criados por humanos.

**IA preditiva -** Envolve o uso de análise estatística e aprendizado de máquina (ML) para identificar padrões, antecipar comportamentos e prever eventos futuros. As organizações utilizam a IA preditiva para prever possíveis resultados futuros, causas, exposição a riscos e muito mais.

**IA Estreita (ou Fraca) -** Refere-se a sistemas projetados e treinados para realizar uma tarefa específica sem a consciência de sua própria existência. Esses sistemas operam sob um conjunto limitado de condições e para fins específicos. Exemplos incluem reconhecimento de voz, assistentes virtuais como Siri e Alexa, e sistemas de recomendação, como os usados por plataformas de streaming de vídeo e lojas online. A IA Estreita é a forma mais comum de inteligência artificial e está integrada em muitas das tecnologias que usamos diariamente.

**IA Geral (ou Forte) -** É um objetivo a ser alcançado e refere-se a sistemas que possuem a capacidade de entender, aprender, e aplicar conhecimento em uma gama tão ampla de tarefas quanto um ser humano. Diferentemente da IA Fraca, a IA Forte seria capaz de raciocinar, solucionar problemas genéricos, e ter consciência de si mesma. Esse tipo de IA envolve não apenas a aplicação de dados e algoritmos para resolver tarefas específicas, mas também a habilidade de transferir conhecimento e aprender de forma autônoma em diferentes contextos. A realização da IA Forte marcaria um ponto de virada na história da tecnologia, oferecendo possibilidades tanto maravilhosas quanto desafiadoras.

**Bid data -**  Refere-se a conjuntos de dados extremamente grandes, complexos e de crescimento rápido que os sistemas tradicionais de processamento não conseguem gerenciar ou analisar com eficácia. Quando combinado com a Inteligência Artificial (IA), ele serve como a "matéria-prima" essencial para treinar modelos de Machine Learning (Aprendizado de Máquina) e gerar previsões de alta precisão.

**Regressão -** É uma técnica de aprendizado supervisionado usada para prever valores numéricos contínuos com base em dados de entrada.  Ela encontra a relação matemática entre uma **variável dependente** (o resultado que você quer prever) e uma ou mais **variáveis independentes** (os dados ou características usados para fazer a previsão).

**Agrupamento -** É uma técnica de aprendizado de máquina não supervisionado usada para organizar dados sem rótulos em grupos coerentes, de modo que os elementos dentro do mesmo grupo sejam semelhantes entre si e diferentes dos de outros grupos.

**Classificação -**  É uma tarefa de aprendizado de máquina supervisionado cujo objetivo é atribuir um rótulo ou categoria a um conjunto de dados de entrada.

**Aprendizado de Reforço -** É um método de inteligência artificial em que um agente autônomo aprende a tomar decisões e realizar tarefas por meio de tentativa e erro, interagindo com um ambiente

**Conferência relacionada à origem da IA -** Dartmouth.

**Espaço Latente -** É uma representação matemática compacta e abstrata onde dados complexos (como imagens, textos ou sons) são traduzidos em vetores de menor dimensão. Nesse "mapa" geométrico oculto, conceitos semelhantes ficam próximos uns dos outros, permitindo que a IA entenda relações e crie novos conteúdos.

**Ajuste fino - É** a técnica de continuar o treinamento de um modelo de inteligência artificial já pronto (pré-treinado) utilizando um conjunto de dados menor e específico. Em vez de criar uma IA do zero, o que consome tempo e recursos enormes, aproveita-se a base de conhecimento geral que ela já possui.

**PNL (Processamento de Linguagem Natural) -** É um campo da inteligência artificial e da ciência da computação. Ele permite que os computadores leiam, compreendam, interpretem e gerem a linguagem humana, seja por texto escrito ou fala.

**Alucinação -** É um fenômeno em que um modelo de inteligência artificial (como um chatbot ou gerador de imagens) cria informações, fatos, citações ou imagens falsas, mas os apresenta com total convicção e aparência de correção

**Modelos de Difusão -**  São modelos generativos utilizados principalmente para geração de imagens e outras tarefas de visão computacional. Redes neurais baseadas em difusão são treinadas por meio de deep learning para “difundir” progressivamente amostras com ruído aleatório e, em seguida, reverter esse processo de difusão para gerar imagens de alta qualidade. Os modelos de difusão estão entre as arquiteturas de redes neurais na vanguarda da IA generativa, representadas principalmente por modelos populares de conversão de texto em imagem, incluindo o Stable Diffusion da Stability AI, o DALL-E da OpenAI (começando com o DALL-E-2), o Midjourney e o Images do Google.

**LLM (Modelo de Linguagem Amplo) -** É um sistema de inteligência artificial treinado em imensas bases de dados de texto para entender, resumir, traduzir e gerar linguagem natural de forma semelhante à humana, previndo estatisticamente a próxima palavra de uma sequência.

**Lógica difusa -**  É um modelo de Inteligência Artificial que substitui o padrão binário rígido (verdadeiro/1 ou falso/0) por graus de verdade entre 0 e 1. Ela permite que os sistemas processem informações vagas, subjetivas e do mundo real

**Conjunto fuzzy -** É uma extensão do conjunto clássico em que os elementos possuem um grau de pertinência entre 0 e 1, em vez de pertencerem a ele de forma absoluta (0 ou 1). Isso permite que sistemas computacionais processem conceitos vagos, subjetivos e humanos

**Transformer -**  É uma arquitetura de rede neural introduzida pelo Google em 2017, base do Processamento de Linguagem Natural(PLN). Ele analisa dados em sequência (como palavras de um texto) de forma simultânea, entendendo o contexto e as relações entre eles através do mecanismo de **autoatenção** (*self-attention*).

**PCA (Análise de Componentes Principais) -** É uma técnica estatística e de aprendizado de máquina não supervisionado usada para reduzir a dimensionalidade de grandes volumes de dados.

