# front-end-aulaquarta
Protótipo acadêmico de site institucional, inspirado no **Instituto Ayrton Senna** (ONG real, fundada em novembro de 1994).

> Este projeto é um trabalho de faculdade e **não representa o site oficial** do Instituto Ayrton Senna. Não recebe doações, não coleta dados e não envia mensagens de verdade.

## Integrantes

- Caio Santos Alencar - 47052830
- Davi de Souza - 47169826
- Ezequiel Soares da Silva - 47205521
- Gabriel Ferraz Aguiar Tricai - 47142014
- Italo Guilherme Silva Nunes - 47189771

## Objetivo

Divulgar a causa da educação pública e as três frentes de atuação do Instituto Ayrton Senna (pesquisa e inovação, mobilização e advocacy, soluções em larga escala), em um site responsivo e interativo feito só com HTML, CSS e JavaScript básico.

## Ideia visual

O site usa o universo do automobilismo, ligado à história de Ayrton Senna: as cores do capacete (amarelo, verde e azul), a faixa quadriculada de chegada e um circuito cujas curvas representam etapas da educação.

## Páginas

| Arquivo | Conteúdo |
|---|---|
| `index.html` | Causa, motivo da educação, três frentes e botão "Como posso participar?" |
| `sobre.html` | História (linha do tempo), missão, público atendido e objetivos |
| `projetos.html` | Três frentes de atuação, cada uma com imagem e forma de a comunidade contribuir |
| `contato.html` | Formulário com validação, orientações de participação e aviso de envio simulado |


## Duas funcionalidades em JavaScript (`js/participacao.js` e `js/formulario.js`)

1. **Interação adicional:** na página inicial, o botão "Como posso participar?" mostra e esconde um painel. O texto do botão muda a cada clique.
2. **Formulário validado:** na página de contato, o evento `submit` é tratado com `addEventListener()` e `preventDefault()`. Confere nome (3+ caracteres), e-mail válido, assunto preenchido e mensagem (10+ caracteres, depois de `trim()`). Mostra o erro ou a confirmação na própria página. A confirmação é **simulada**: nada é enviado nem guardado.

## Estrutura de arquivos

```
ONG_Educacao_em_Pista/
├── index.html · sobre.html · projetos.html · contato.html
├── css/estilos.css
├── js/participacao.js e js/formulario.js
├── img/ (pista.svg e três ilustrações das frentes)
└── README.md
```

## Como executar

Descompacte o ZIP e abra `index.html` no navegador. Use o menu para navegar entre as páginas. Não precisa instalar nada. A fonte usada é Arial, disponível no computador. Não há dependências para instalar.

## Tecnologias

HTML5 semântico, CSS3 (Flexbox, `box-sizing` e `@media`) e JavaScript básico (funções, `if/else`, eventos e DOM).
