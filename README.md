# ALPA NeuroReading AI v8.0 - Ultimate Edition

Site estático em arquivo único para treino de leitura, visão periférica, chunking, pacer rítmico, gamificação e módulo Mindset & Flow.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub, por exemplo: `alpa-neuroreading-ai`.
2. Faça upload destes arquivos para a raiz do repositório:
   - `index.html`
   - `.nojekyll`
   - `README.md`
3. Vá em **Settings > Pages**.
4. Em **Build and deployment**, escolha:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/** root
5. Salve. O link será parecido com:
   `https://SEU-USUARIO.github.io/alpa-neuroreading-ai/`

## Configuração do EmailJS

No `index.html`, procure por `EMAILJS_CONFIG` e preencha:

```js
const EMAILJS_CONFIG = {
  publicKey: "SUA_PUBLIC_KEY",
  serviceId: "SEU_SERVICE_ID",
  templateId: "SEU_TEMPLATE_ID",
  appName: "ALPA NeuroReading AI v8.0"
};
```

Atenção: OTP apenas no front-end serve para protótipo e uso pessoal. Para segurança real, use um backend para gerar e validar o código.
