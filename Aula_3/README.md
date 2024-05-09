# Desafios da Aula 1
## Desafio 1
**OBJETIVO:** Criar um áudio e realizar um prompt para análise pelo Google AI Studio.

Como pedido, gravei um áudio no próprio `AI Sttudio` sobre  pré-processamento de imagens com python, mas inclui a palavra "batata-frita" no áudio para que o `Gemini` indentificasse que não há nenhuma relação com o assusnto tratado no áudio.

![resposta audio 1](https://github.com/BeatrizVencio/Imersao-Alura-2/blob/main/Aula_3/imgs/resp_audio1.png)

Resposta do `Gemini`:

**Análise do áudio sobre Introdução ao pré-processamento de imagens**
O áudio apresenta uma introdução clara e concisa sobre o conceito de pré-processamento de imagens no contexto de visão computacional e aprendizado de máquina.
1. **Pontos positivos:**
- **Definição clara:** O áudio define o pré-processamento de imagens como um conjunto de técnicas aplicadas antes da modelagem para preparar as imagens e melhorar sua qualidade.
- **Importância do pré-processamento:** Destaca a relevância do pré-processamento para a qualidade dos modelos de visão computacional, enfatizando melhorias como:
    * **Qualidade da imagem:** Aumenta a qualidade das imagens, destacando características importantes para facilitar a interpretação pelos algoritmos.
    * **Redução da variabilidade:** Minimiza as diferenças irrelevantes entre as imagens do conjunto de dados, permitindo que o modelo se concentre nas características essenciais.
    * **Destaque de características importantes:** Utiliza técnicas específicas para realçar detalhes cruciais para o problema em questão.
- **Exemplos:** Menciona o exemplo do reconhecimento facial, onde o pré-processamento pode enfatizar contornos do rosto e olhos.

2. **Sugestões para melhorias:**
- **Exemplos mais diversificados:** Incluir exemplos de pré-processamento em diferentes aplicações de visão computacional, como segmentação de imagens, detecção de objetos, etc.
- **Técnicas específicas de pré-processamento:** Apresentar algumas técnicas comuns de pré-processamento, como redimensionamento, normalização, aumento de dados, filtragem de ruído, etc.
- **Ferramentas e bibliotecas:** Mencionar ferramentas e bibliotecas populares para pré-processamento de imagens, como OpenCV, Pillow, scikit-image, etc.

3. **Conclusão:**\
O áudio fornece uma excelente base para compreender a importância do pré-processamento de imagens. Ao incluir mais detalhes sobre as técnicas e ferramentas, o conteúdo se tornaria ainda mais informativo e útil para iniciantes na área de visão computacional e aprendizado de máquina.

Eu não esperava que o `Gemini` não indentificasse a palavra que foge do contexto, por isso perguntei se não havia a palavra "batata-frita" no áudio.

![resposta audio 2](https://github.com/BeatrizVencio/Imersao-Alura-2/blob/main/Aula_3/imgs/resp_audio2.png)

E essa foi a resposta do `Gemini`:\
Você está absolutamente certo! Peço desculpas pelo erro. Eu analisei o texto transcrito e não notei a palavra "batata-frita" fora de contexto.

É importante revisar o texto com atenção para identificar qualquer elemento que possa parecer estranho ou fora de lugar. Agradeço por apontar esse erro e me ajudar a melhorar minha capacidade de análise.

 
#

## Desafio 2
**OBJETIVO:** Pesquise como colocar a imagem do Google AI Studio dentro do código de Pyhton no Google Colab.

Abrindo a [galeria de prompts](https://ai.google.dev/examples?hl=pt-br) do Google AI Studio, eu consigo acessar o prompt "Redatora de descrição de marketing" (exemplo usado na aula). 

![prompt](https://github.com/BeatrizVencio/Imersao-Alura-2/blob/main/Aula_3/imgs/prompt.png)

Logo em seguida, clicando com o botão direito do mouse na imagem, eu salvei as imagens na minha pasta de arquivos do computador.

Depois de baixá-las ([imagem 1](https://github.com/BeatrizVencio/Imersao-Alura-2/blob/main/Aula_3/imgs/images1.jpg), [imagem 2](https://github.com/BeatrizVencio/Imersao-Alura-2/blob/main/Aula_3/imgs/images2.jpg) e [imagem 3](https://github.com/BeatrizVencio/Imersao-Alura-2/blob/main/Aula_3/imgs/images3.jpg)), eu selecionei elas e arrastei para a barra de arquivos do Google Colab (já com um novo notebook criado).

![arquivos](https://github.com/BeatrizVencio/Imersao-Alura-2/blob/main/Aula_3/imgs/arquivos.png)

#

## Desafio 3
**OBJETIVO:** Pegue os códigos que não contenham imagens do AI Studio e exporte para o Google Colab.

O próprio `AI Studio` possui um botão onde nós podemos pegar o código, mas somente na versão 1.0.

![botao](https://github.com/BeatrizVencio/Imersao-Alura-2/blob/main/Aula_3/imgs/bot%C3%A3o.png)

Depois de clicar, aparecerá essa tela onde nós podemos escolher em qual linguagem queremos o código (Curl, JavaScript, Python, Adroid - Kotlin e Swift).

![tela code](https://github.com/BeatrizVencio/Imersao-Alura-2/blob/main/Aula_3/imgs/linguagens.png)

Feito isso, é só copiar o código e colar no notebook.

![colab](https://github.com/BeatrizVencio/Imersao-Alura-2/blob/main/Aula_3/imgs/colab.png)

> [!WARNING]
> Sempre lembrar de trocar o "YOUR_API_KEY" pela própria chave API e de trocar o caminho onde estão alocada as imagens!
 
> [!NOTE]
> Irei deixar o notebook do Google Colab nesta mesma pasta!












