# Transcrição e Tradução de Áudio com Azure AI Speech

Este projeto demonstra como utilizar o Azure AI Speech para transcrição e tradução de áudios em diferentes idiomas.
A solução é útil tanto em contextos corporativos quanto cotidianos, auxiliando pessoas que não são bilíngues ou não têm fluência em outros idiomas, tornando a comunicação mais clara e acessível.

## Premissa do Projeto

Muitas vezes, devido a sotaques ou variações regionais, a compreensão de falas em outros idiomas pode ser difícil.

 Com o Azure AI Speech, é possível:

- Fazer upload de áudios salvos no computador.
- Obter a transcrição do conteúdo falado.
- Usar o recurso de tradução automática para compreender em outro idioma.

#### O objetivo principal é usar a opção Tradução de Fala, mas a ferramenta oferece outros recursos poderosos, como:

- Transcrição em tempo real
- Avaliação de pronúncia
- Reconhecimento multilíngue

## Requisitos

Para utilizar o projeto, você precisa apenas de:

Uma conta Microsoft gratuita

Acesso ao portal do Azure Speech:
- ->https://speech.microsoft.com/portal

## Como utilizar

Acesse o portal do Azure AI Speech:
- -> https://speech.microsoft.com/portal
- Faça login com sua conta Microsoft.
- Selecione a opção Tradução de fala.

![Opção 1](/imgs/ops1.png)

- Configure o idioma de entrada (o idioma em que o áudio está).
- Escolha o idioma de saída (idioma para tradução, se desejar).

![Opção 1](/imgs/ops2.png)

- Faça o upload do arquivo de áudio salvo no computador.
- Aguarde alguns segundos e o Azure IA fornecerá a transcrição e, caso configurado, a tradução.

## Exemplo utilizado neste projeto

No meu caso de teste, utilizei o áudio extraído do vídeo do YouTube:

 **"That Performance Was Scouse As **." | Liverpool v Arsenal 3-1 | Fan Cam

- Este vídeo contém um forte sotaque Scouse, típico da região de Liverpool (noroeste da Inglaterra), o que torna a compreensão mais desafiadora.

Com o Azure AI Speech, foi possível transcrever o áudio e obter uma tradução para melhor compreensão.

## Possíveis usos e aplicações

- Suporte em reuniões corporativas internacionais.
- Entendimento de conteúdos acadêmicos ou palestras em outros idiomas.
- Acessibilidade para pessoas que não dominam uma segunda língua.
- Estudo de sotaques e pronúncia.

## License

[MIT](https://choosealicense.com/licenses/mit/)
