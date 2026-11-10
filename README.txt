# Temporizador de Estudo de Piano

A aplicação inclui o plano diário configurado (09:30–12:30), contagem decrescente, alerta sonoro e avanço apenas após confirmação manual.

## Testar rapidamente
Abre `index.html` no navegador. O temporizador funciona, mas a instalação como aplicação e o modo offline completo exigem alojamento HTTPS.

## Instalar como aplicação (PWA)
1. Publica os ficheiros desta pasta num alojamento HTTPS estático (por exemplo, GitHub Pages).
2. Abre o endereço publicado no Chrome ou Edge.
3. Escolhe **Instalar aplicação** na barra de endereço ou no menu do navegador.

Depois da primeira visita, a aplicação pode funcionar offline. O progresso fica guardado nesse navegador/dispositivo.

## Conteúdo
- `index.html`: aplicação e temporizador
- `manifest.json`: identificação da aplicação instalável
- `sw.js`: suporte offline
- `icon.svg`: ícone

## Nota
Mantém a página aberta durante a sessão. O navegador pode suspender temporizadores se o dispositivo entrar em suspensão ou se a página for fechada.
