# bd_frontend

**Português (Brasil)** | [English](README.md)

Um projeto de estudo de front-end React, pelo nome o front-end do app Baby Daily.

**Código:** repositório público. Documentação revisada em 01/10/2026.

## Status

Projeto de estudo do período do curso Full Stack da Code Institute (últimos commits em 2023). O README anterior era o texto inalterado do template Codeanywhere da Code Institute; foi substituído por este documento em 01/10/2026. O projeto não está atualmente publicado em uma URL pública conhecida.

## Objetivo

O nome do repositório e do pacote (`bd_frontend`) o identificam como front-end do [Baby Daily](https://github.com/iurjoh/Baby-Daily), uma plataforma privada para pais compartilharem marcos do bebê com um círculo de confiança. Note que o repositório Baby Daily também carrega seu próprio diretório `frontend/`; se este repo é uma cópia standalone anterior ou a fonte que depois foi mesclada não foi confirmado nesta revisão e não é afirmado como fato. O código é construído sobre a stack do walkthrough "Moments" do curso (Create React App, React Bootstrap, Axios, autenticação JWT); o backend correspondente é uma API Django REST Framework.

## Stack técnica

Do `package.json`:

- React 18 com `react-scripts` (Create React App) e React Router
- React Bootstrap e Bootstrap
- Axios para chamadas de API, `jwt-decode` para tratamento de tokens
- `react-infinite-scroll-component`
- Testing Library (jest-dom, react, user-event)

## Rodar localmente

```bash
npm install
npm start
```

Abre em `http://localhost:3000`. Uma API de backend rodando é necessária para dados reais. Outros scripts: `npm test`, `npm run build`. Um script `heroku-prebuild` restou da configuração original de deploy no Heroku; nenhum deploy atual foi verificado.

## Registro de desenvolvimento

O conjunto exato de funcionalidades e as notas originais de planejamento não foram reconstruídos nesta atualização de documentação, e nenhum histórico de processo é inventado aqui. A documentação completa do produto vive no repositório [Baby Daily](https://github.com/iurjoh/Baby-Daily). O histórico do git é a fonte para detalhes de implementação.

## Testes

As dependências do Testing Library estão presentes, mas a suíte de testes não foi executada nesta atualização. Antes de qualquer reuso, rode `npm install` e `npm test` e verifique o app contra um backend ativo.

## Créditos e status de licença

Iniciado com Create React App e baseado no template do walkthrough "Moments" da Code Institute. Nenhum arquivo `LICENSE` foi encontrado na raiz do repositório nesta revisão; código de template de terceiros mantém seus termos originais, e esta atualização não aplica uma nova licença sobre eles.
