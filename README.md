Desafio de Projeto DIO: Explorando os Serviços de IA da Azure para Fala e Linguagem
📖 Descrição
Este repositório documenta a jornada de aprendizado e exploração prática das ferramentas de Inteligência Artificial da Microsoft Azure: o Speech Studio e o Language Studio. O projeto foi desenvolvido como parte do Desafio de Projeto "Construindo um Perfil de Destaque na DIO", com o objetivo de aplicar conceitos teóricos sobre processamento de voz e linguagem natural em um ambiente prático.

🤖 Tecnologias Utilizadas
Microsoft Azure (Plataforma de Nuvem)

Azure AI Speech Studio (Serviços de Fala)

Azure AI Language Studio (Serviços de Linguagem Natural)

GitHub (Versionamento e Documentação do Projeto)

Markdown (Linguagem de Marcação para Documentação)

🗣️ Azure AI Speech Studio: A Voz da IA
O Speech Studio é uma plataforma poderosa que permite testar e integrar serviços de conversão de texto em fala e reconhecimento de fala. A seguir, estão documentadas as principais funcionalidades exploradas.

1. Conversão de Texto em Fala (Text-to-Speech)
Esta ferramenta converte texto escrito em uma fala que soa natural. Realizei testes para explorar a qualidade e a variedade das vozes disponíveis.

Processo:

Acesse o recurso "Text-to-speech" no Speech Studio.

Insira o texto desejado na caixa de diálogo.

Selecione o idioma (ex: Português (Brasil)).

Escolha uma das vozes neurais disponíveis (ex: pt-BR-FranciscaNeural).

Ajuste parâmetros como velocidade, tom e estilo da fala.

Exemplo de Texto Utilizado:

Olá, mundo! Esta é uma demonstração da capacidade de síntese de voz da Inteligência Artificial da Azure. As vozes neurais são incrivelmente realistas e podem ser usadas em diversas aplicações, como assistentes virtuais e audiolivros.
Captura de Tela:
Aqui você pode inserir uma imagem da interface com seu teste.

Insights:

A qualidade das vozes neurais é impressionante, especialmente a fluidez e a entonação natural. A voz FranciscaNeural se mostrou muito clara e agradável. A capacidade de ajustar o estilo de fala (como "calmo" ou "alegre") abre um leque de possibilidades para criar experiências de usuário mais ricas e personalizadas.

2. Reconhecimento de Fala (Speech-to-Text)
A funcionalidade de "Speech-to-text" em tempo real transcreve o áudio capturado pelo microfone em texto com alta precisão.

Processo:

Acesse a funcionalidade "Real-time speech to text".

Selecione o idioma de origem.

Clique no ícone de microfone e comece a falar.

A transcrição aparece na tela instantaneamente.

Captura de Tela:
Aqui você pode inserir uma imagem da ferramenta transcrevendo sua fala.

Insights:

A ferramenta demonstrou uma excelente acurácia, mesmo com uma fala rápida e com pouco ruído de fundo. Ela reconheceu corretamente a pontuação, como vírgulas e pontos finais, quando ditados. É uma ferramenta robusta para aplicações que necessitam de transcrição ao vivo, como legendagem automática ou sistemas de comando por voz.

✍️ Azure AI Language Studio: A Compreensão da Linguagem
O Language Studio oferece um conjunto de ferramentas para extrair insights de textos não estruturados. Abaixo estão os principais recursos explorados.

1. Análise de Sentimento e Mineração de Opinião
Esta ferramenta avalia um texto e o classifica como positivo, negativo, neutro ou misto, atribuindo pontuações de confiança para cada sentimento.

Exemplo de Texto Analisado (Review de um produto):

Adorei o design do celular, é muito bonito e leve. A câmera é fantástica e tira fotos incríveis, mas a bateria não dura o dia todo, o que é um ponto bem negativo.
Resultado da Análise:

Sentimento Geral: Misto

Sentença 1 ("Adorei o design..."): Positivo (Confiança: 98%)

Sentença 2 ("A câmera é fantástica..."): Positivo (Confiança: 99%)

Sentença 3 ("...mas a bateria não dura..."): Negativo (Confiança: 95%)

Captura de Tela:
Aqui você pode inserir uma imagem com o resultado da análise.

Insights:

A ferramenta foi capaz de identificar com precisão os sentimentos mistos dentro do mesmo texto, analisando cada sentença individualmente. Isso é extremamente útil para empresas que desejam analisar feedbacks de clientes e identificar os pontos fortes e fracos de seus produtos de forma detalhada.

2. Extração de Entidades Nomeadas
Esta funcionalidade identifica e categoriza entidades em um texto, como pessoas, locais, organizações e datas.

Exemplo de Texto Analisado:

A Microsoft anunciou durante o evento Ignite em São Paulo que a nova versão do Azure será lançada oficialmente em 1 de Dezembro de 2025. Satya Nadella, o CEO da empresa, confirmou a notícia.
Entidades Extraídas:

Organização: Microsoft, Azure

Evento: Ignite

Local: São Paulo

Data: 1 de Dezembro de 2025

Pessoa: Satya Nadella

Cargo: CEO

Captura de Tela:
Aqui você pode inserir uma imagem mostrando as entidades identificadas no texto.

Insights:

A capacidade de extrair e categorizar informações estruturadas de um texto não estruturado é fundamental para automatizar processos. Aplicações práticas incluem a organização automática de documentos, a criação de bases de conhecimento ou a melhoria de mecanismos de busca. A precisão da ferramenta foi excelente.

🏁 Conclusão
Este desafio foi uma excelente oportunidade para ter um contato prático e aprofundado com os serviços de IA da Microsoft Azure. As ferramentas são intuitivas e extremamente poderosas, permitindo que desenvolvedores integrem funcionalidades complexas de processamento de voz e linguagem com relativa facilidade. A documentação desta jornada reforçou o aprendizado e criou um material de consulta valioso para projetos futuros.
