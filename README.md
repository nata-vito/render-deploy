# Solara • Assistente Repsol (ElevenLabs)

Página estática com o widget Conversational AI da ElevenLabs.

## Como publicar no Render

1. Crie um repositório no GitHub contendo: `index.html` e `render.yaml`.
2. No painel do Render: **New +** → **Static Site**.
3. Conecte ao seu repositório e selecione a branch (ex.: `main`).
4. **Build Command**: deixe em branco.
5. **Publish Directory**: `.` (raiz).
6. Crie o serviço. O Render fará o deploy automático a cada push.

> Opcional: aponte um domínio personalizado em **Settings → Custom Domains**.

## Notas
- O widget é carregado via:
  ```html
  <elevenlabs-convai agent-id="agent_8601k2zk8ndkepnap4gewwbtb9jk"></elevenlabs-convai>
  <script src="https://unpkg.com/@elevenlabs/convai-widget-embed" async type="text/javascript"></script>
