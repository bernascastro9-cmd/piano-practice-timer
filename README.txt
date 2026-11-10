# Temporizador de Estudo de Piano

## O que inclui
- Plano diário inicial das 09:30 às 12:30.
- Contagem decrescente, alerta sonoro e avanço apenas após confirmação manual.
- Edição dos nomes e durações dos exercícios diretamente na aplicação.
- Possibilidade de adicionar e eliminar exercícios.
- Guardar o plano personalizado neste navegador.
- Repor o plano original.
- Suporte PWA e cache offline após publicação HTTPS.

## Testar
Abre `index.html` num navegador. Para instalar como aplicação e usar o modo offline, publica os ficheiros num alojamento HTTPS, por exemplo GitHub Pages.

## Atualizar uma versão já publicada no GitHub
1. Extrai este ZIP.
2. Abre o repositório GitHub.
3. Escolhe Add file > Upload files.
4. Carrega os ficheiros novos, substituindo os antigos.
5. Faz Commit changes.
6. Atualiza a página publicada. Se a versão antiga continuar visível, fecha e volta a abrir a aplicação ou limpa a cache do site.

## Ficheiros
- `index.html`: aplicação, temporizador e editor do plano
- `manifest.json`: instalação como aplicação
- `sw.js`: suporte offline
- `icon.svg`: ícone
- `README.txt`: instruções
