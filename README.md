# Grupo Prioridade — versão estática visualmente idêntica

Esta versão mantém o mesmo visual da landing page publicada, mas foi empacotada como HTML estático.

## Abrir com duplo clique

Abra `index.html` diretamente no navegador. O JavaScript foi gerado como bundle clássico, sem módulos ES, servidor local ou dependências externas. O CSS e a imagem do hero são carregados por caminhos relativos.

## Publicar na Vercel

Envie esta pasta para um repositório e importe na Vercel. Use:

- Framework Preset: `Other`
- Build Command: vazio
- Output Directory: `.`
- Install Command: vazio

## Arquivos

- `index.html`: entrada da página.
- `assets/site.css`: estilos originais da interface.
- `assets/site.js`: bundle JavaScript autocontido da interface React.
- `assets/grupo-prioridade-hero.jpg`: imagem local do hero.

O formulário exibe confirmação visual no frontend. Para receber mensagens reais, conecte-o a um serviço de formulários ou API.
