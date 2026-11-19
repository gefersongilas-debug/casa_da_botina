CASA DA BOTINA - V30 | OTIMIZADA PARA PAGESPEED INSIGHTS

Conteúdo: index.html + assets/ + MAPA-FOTOS-V24.txt.
Base: V29. Cards, copy, responsividade, GTM e WhatsApp preservados.

Melhorias técnicas:
- preload de banner LCP apropriado a cada tela (mobile/desktop)
- largura e altura intrínsecas das imagens (evita deslocamento de layout)
- imagens secundárias com carregamento adiado e decodificação assíncrona
- WebP/JPEG ajustados à resolução realmente exibida e recomprimidos
- carrossel mantém autoplay e arraste enquanto visível e economiza CPU fora da tela
- metadados SEO/social e link canônico do domínio final
- acessibilidade dos botões de favorito

IMPORTANTE PARA PUBLICAR:
- Suba index.html + pasta assets sem alterar os caminhos.
- Troque o conteúdo completo da versão anterior (não usar index solto de prévia).
- O domínio canônico usado no HTML é https://lp.casadabotinasapezal.com.br/.
- Confirme o número do WhatsApp antes da campanha.
- Teste GTM-PZRW6ZDV, GA4/Google Ads e UTMs pelo Tag Assistant.
- Verifique o PageSpeed Insights no URL FINAL após publicação.
- Não há pontuação PageSpeed prometida: métricas dependem de rede, hospedagem, GTM e tráfego real.

CACHE DA VERCEL:
- vercel.json define cache longo para assets com HASH no nome.
- Ao atualizar imagens no futuro, gere um novo arquivo com hash diferente e atualize o HTML.
- HTML sempre revalida para mostrar as novas versões.
- Suba também vercel.json na raiz do projeto caso publique na Vercel.
- Se usar outra hospedagem, configure cache equivalente no servidor.
