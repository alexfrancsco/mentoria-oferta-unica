# Apresentação comercial — Mentoria Oferta Única

Esta pasta é independente da página inicial do repositório.

- `revisar.html`: versão de revisão, com painel para mostrar/ocultar as ofertas e regular o desbloqueio.
- `index.html`: versão destinada aos leads, sem painel administrativo.
- `capa-provisoria.svg`: capa provisória para a prévia no GitHub.

## Pendências para publicar a versão final
1. Hospedar o vídeo `mentoriaofertaunicafinal.mp4` (aproximadamente 215 MB) em um serviço que forneça um endereço HTTPS direto com suporte a reprodução por streaming.
2. Atualizar `VIDEO_URL` nos dois HTMLs com esse endereço.
3. Enviar a capa aprovada `capa_apresentacao_mentoria.png` e trocar o atributo `poster` nos dois HTMLs. A imagem atual é apenas temporária, não a capa com a foto aprovada.
4. Configurar `WHATSAPP_NUMBER` no HTML.
5. Verificar GitHub Pages em Settings > Pages, fonte: main / (root).

O GitHub não aceita esse MP4 de ~215 MB como arquivo Git comum (limite de 100 MB).
A liberação dos valores ocorre quando o vídeo alcança 90% do tempo reproduzido.
O bloqueio do player é um recurso de interface, não DRM ou proteção absoluta.

## URLs esperadas se GitHub Pages estiver ativado
- Versão de revisão: https://alexfrancsco.github.io/mentoria-oferta-unica/apresentacao-comercial/revisar.html
- Versão pública: https://alexfrancsco.github.io/mentoria-oferta-unica/apresentacao-comercial/
