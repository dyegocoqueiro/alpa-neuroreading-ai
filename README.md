# MindForge Reading — Ultimate Edition

Site estático em arquivo único para treino de leitura, foco, visão periférica, chunking, pacer rítmico, gamificação e módulo Mindset & Flow.

**Forje sua mente leitora.** MindForge Reading é um treino neural para leitores de elite: transforma foco em velocidade, velocidade em compreensão e sessões curtas em evolução mensurável.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub, por exemplo: `mindforge-reading`.
2. Faça upload destes arquivos para a raiz do repositório:
   - `index.html`
   - `.nojekyll`
   - `README.md`
   - `INSTRUCOES_RAPIDAS_GITHUB.txt`
3. Vá em **Settings > Pages**.
4. Em **Build and deployment**, escolha:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/** root
5. Salve. O link será parecido com:
   `https://SEU-USUARIO.github.io/mindforge-reading/`

## Configuração do EmailJS

No `index.html`, procure por `EMAILJS_CONFIG` e preencha:

```js
const EMAILJS_CONFIG = {
  publicKey: "COLE_AQUI_SUA_PUBLIC_KEY",
  serviceId: "COLE_AQUI_SEU_SERVICE_ID",
  templateId: "COLE_AQUI_SEU_TEMPLATE_ID",
  appName: "MindForge Reading"
};
```

Atenção: OTP apenas no front-end serve para protótipo e uso pessoal. Para segurança real, use um backend para gerar e validar o código.
