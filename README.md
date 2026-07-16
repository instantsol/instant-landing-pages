# Portal Soluções — Instant Solutions

Página estática criada para a raiz `https://solucoes.instant.com.br/`.

## Estrutura

- `index.html`: página principal, estilos, interações e logotipos incorporados.
- `assets/`: logotipos e imagens utilizadas localmente.
- `CNAME`: domínio personalizado para GitHub Pages.

## Publicação no GitHub Pages

1. Envie todo o conteúdo desta pasta para a raiz do repositório.
2. Em **Settings → Pages**, selecione **Deploy from a branch**.
3. Escolha a branch `main` e a pasta `/ (root)`.
4. Confirme o domínio `solucoes.instant.com.br`.

Os links dos produtos utilizam os endereços oficiais registrados nas fontes:

- Kwik: `https://landing.kwik.app.br/`
- InstantVoice: `https://landing.instant.com.br/instant-cloud-voice/`
- Kwik Scout: `https://scout.kwik.app.br/`
- Cortex: `https://cortex.instant.com.br`

Esses links abrem em uma nova guia e não dependem de pastas internas no repositório.

Os logotipos da Instant Solutions, Meta Business Partner e das quatro soluções estão incorporados no próprio HTML. As capturas oficiais do Kwik Scout — painel principal, indicadores e resumos, conversas e insights com IA — também estão incorporadas. Portanto, esses materiais continuam visíveis mesmo quando somente o `index.html` é publicado. A pasta `assets` permanece no projeto para facilitar futuras substituições e edições.

As referências visuais desta versão seguem o arquivo `Logos-publicos(7).txt`, o mapeamento da biblioteca de mídia do WordPress e os arquivos oficiais anexados ao projeto.

Os logos do InstantVoice e do Cortex possuem margem interna nos arquivos originais e, por isso, recebem escala visual específica nos cards. O rodapé foi reorganizado em três níveis: apresentação e contato, navegação e redes sociais, e informações legais.

O formulário comercial está incorporado na seção `#contato` por meio do formulário Kwik `019f6bb8-8e50-7905-b627-2e7f5cab6ca3`. O iframe usa uma altura inicial responsiva e redimensionamento automático para evitar rolagem interna. Os CTAs comerciais direcionam para essa seção e os links com o telefone `+55 11 4063-6100` abrem o WhatsApp da Instant com uma mensagem inicial.

## Monitoramento

O aviso de cookies já registra a preferência no navegador. Os códigos de Google Analytics, Google Tag Manager e Microsoft Clarity devem ser incluídos no ponto indicado ao final do `index.html`, carregando somente quando houver autorização para cookies analíticos.
