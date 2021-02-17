[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/icaroc/blender-render-colab/blob/main/blender_render.ipynb)

# blender-render-colab
Google Colab para renderizar arquivos .Blend pela GPU.

Esse notebook não é meu, apenas traduzi pro português e deixei mais friendly user.\
Assim que descobrir o criador, colocarei o Github dele aqui.

Para utilizar esse colab vamos usar o Google Drive.\
O código já entende que os arquivos vem do /My Drive/, então não é necessário colocar isso nos caminhos que vamos configurar.

## Início e Configurações
`blender_version`: Selecione a versão do blender que você quer renderizar seu arquivo.\
`caminho_arquivo_blend`: Caminho do Google Drive que se encontra o arquivo blend. eg: /files/arquivo.blend\
`caminho_saida_render`: Caminho do Google Drive que vai usar para salvar o render. eg: /files/output/<nome_do_arquivo>\
`gpu_enabled`, `cpu_enabled`: Selecione se vai querer usar a GPU ou CPU

## Instalação do Blender
Rode todas células que tem dentro da parte de instalação do Blender.

## Renderização
Rode a célula de montagem do Drive e siga os passsos dela.\
Após isso rode a célula de renderização da um frame só ou a célula de animação.

### Parametros de Render
Se você for renderizar apenas 1 frame, utilize o parâmetro `-f <número do frame>`\
Se for renderizar uma animação, utilize o parâmetro `-s` especifica o frame inicial e o `-e`. eg: `-s <frame_inicial> -e <frame_final>`
