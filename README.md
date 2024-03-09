# Projeto: Sistema para Edição de imagens e áudios

Este projeto faz parte da avaliação do Módulo 03 - Técnicas de Programação I do programa Santander Coders 2023. O objetivo é validar os conhecimentos adquiridos em aula através da implementação de um programa em Python para manipulação de imagens e áudios. Abaixo está um [índice](#índice) de conteúdo que lista alguns dos tópicos aprendidos em aula e onde eles foram aplicados no projeto.


## Conteúdo desse projeto 

Nesse projeto temos três scripts python:
  - image_process.ipynb
  - audio_process.ipynb
  - log_analysis.ipynb

Cada script aborda diferentes aspectos do processamento de imagens e áudios, proporcionando uma experiência completa de aprendizado e prática dos conceitos apresentados no curso. A seguir decreve-se o contéudo apresentado em cada script:

#### `image_process.ipynb`

Este script realiza diversas operações de processamento de imagens, incluindo alteração de cor de fundo, rotação, inversão horizontal, deslocamento e zoom. Além disso, o script também registra informações sobre as operações realizadas em um arquivo de log ***log_image.csv***.

#### `audio_process.ipynb` 

Este script implementa as seguintes operações de processamento de áudio:

   - **Leitura de arquivo WAV**: Utiliza a função `scipy.io.wavfile.read()` para carregar um arquivo WAV em uma variável numpy array, contendo os dados de áudio e a taxa de amostragem;

   - **Convolução de áudio**: A convolução é uma operação matemática comum em processamento de sinais que combina duas funções para produzir uma terceira, representando como uma é afetada pela outra ao longo do tempo;

   - **Normalização de áudio**: Normaliza o áudio para ajustar os níveis de amplitude;

   - **Corte de áudio**: Recorta parte do áudio, selecionando apenas uma parte específica;

   - **Concatenação de áudio**: Junta dois ou mais arquivos de áudio em um único arquivo;

   - **Aplicação de filtros**: Aplica filtros, como passa-baixa ou passa-alta, para alterar as características do som.

Assim como no script de processamento de imagens, este script também registra informações em um arquivo de log ***log_audio.csv***.


----------------------------------------------------------------------------------------------------------------------------------------------
<div style="background-color: #f2f2f2; padding: 10px;">

**`Arquivos de Log`**

Os arquivos de log ( *log_image.csv* | *log_audio.csv* ) irão incluir as seguintes informações:

- **Data e hora**: Registrar a data e hora em que o processamento foi realizado;

- **Tipo de processamento**: Indicar o tipo de processamento de imagem/áudio realizado (rotação, mudança de cor de fundo, corte, concatenação, etc.);

- **Tempo de processamento**: Indicar o tempo de processamento;

- **Nome do arquivo de imagem**: Indicar o nome do arquivo de imagem/áudio processado;

- **Tamanho do arquivo**: Indicar o tamanho em MB do arquivo processado;

- **Resultado do processamento**: Indicar se o processamento foi bem-sucedido ou se ocorreu algum erro;

- **Mensagem de erro**: Em caso de erro, registrar a mensagem de erro específica.

</div>
----------------------------------------------------------------------------------------------------------------------------------------------


#### `log_analysis.ipynb`

Este script realiza análises dos arquivos de log de processamento de imagens e áudios usando a biblioteca Pandas. As análises incluem:

- **Tempo de processamento médio por tipo** (imagem ou áudio);
- **Distribuição do tempo de processamento** (visualização da distribuição do tempo de processamento para identificar outliers ou padrões incomuns);
- **Tempo médio de processamento por tipo de processamento** (identificação das manipulações que exigem mais performance);
- **Arquivos com tempo de processamento abaixo da média**;
- **Comparação de desempenho entre tipos de processamento** (comparação do tempo médio de processamento entre diferentes tipos para identificar os mais demorados e que podem precisar de otimização);
- **Tipos de erros mais frequentes**;
- **Análise de correlação entre tamanho do arquivo e tempo de processamento** (verificação de correlação entre o tamanho do arquivo e o tempo de processamento);
- **Análise de frequência por tipo de processamento** (identificação dos tipos de processamento mais frequentes e se há algum padrão relacionado a eles);
- **Análise de erros por tipo de processamento** (verificação se há tipos de processamento com mais erros e investigação das causas desses erros).

&nbsp;

## Índice

[... FAZER ÍNDICE ...]

&nbsp;

## Autores

- [@andreaseliass](https://github.com/andreaseliass)
- [@AnthonyHeimlich](https://github.com/AnthonyHeimlich)
- [@evertondcavalcante](https://github.com/evertondcavalcante)
- [@JuliaMidoriRW](https://github.com/JuliaMidoriRW)
- [@luana-kruger](https://github.com/luana-kruger)
