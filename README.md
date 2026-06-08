# Portal de Chamados TI — Appa Empregos

Sistema de abertura e acompanhamento de chamados de suporte de TI, feito em HTML/CSS/JS puro, sem framework nem backend.

## Estrutura do Projeto

```
portal-chamados-ti/
|-- index.html          # Pagina principal (HTML)
|-- css/
|   +-- styles.css      # Todos os estilos (CSS3)
|-- js/
|   +-- app.js          # Toda a logica (JavaScript ES6+)
|-- assets/             # Imagens e recursos estaticos
+-- README.md
```

## Configuracao — EmailJS

Edite as constantes no inicio de `js/app.js`:

```js
const EMAILJS_PUBLIC_KEY  = 'EhgqiZfeWNd9BGQMD';  // OK
const EMAILJS_SERVICE_ID  = 'service_tw3u2p6';      // OK
const EMAILJS_TEMPLATE_ID = 'template_pcr0o87';     // OK
const SUPORTE_EMAIL       = 'davi.linares@appaempregos.com.br';
```

## Como usar

Abra `index.html` no navegador, ou hospede em qualquer servidor web.

## Tecnologias

- HTML5
- CSS3 (Flexbox, Grid, animacoes, variaveis CSS)
- JavaScript ES6+ (async/await, fetch, template literals)
- EmailJS (envio de e-mail direto do browser, sem backend)
- Tabler Icons (CDN)

## Funcionalidades

- Login Microsoft 365 ou e-mail/senha
- Abertura de chamados com campo de anexos (drag & drop)
- Painel Kanban: Abertos / Em Andamento / Resolvidos
- Lista completa com ordenacao por coluna e filtros
- Timeline de historico de movimentacoes por chamado
- Notificacao por e-mail ao solicitante a cada atualizacao de status
- Estatisticas clicaveis no topo como filtro rapido
