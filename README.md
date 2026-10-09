# Natal de Oportunidades — Senac Piauí

Landing page da campanha especial **Natal de Oportunidades** do Senac Piauí.

## 📁 Estrutura de Arquivos

- `index.html`: Página principal da campanha (configurada para servir na raiz do domínio no Render).
- `natal_de_oportunidades.html`: Cópia direta do arquivo original para acesso direto via `/natal_de_oportunidades.html`.
- `render.yaml`: Configuração opcional de Blueprint para deploy automático no Render.

---

## 🚀 Como fazer o deploy no Render

1. Acesse o painel do [Render](https://dashboard.render.com/).
2. Clique em **New +** e selecione **Static Site**.
3. Conecte este repositório (`insidekeyco/natalsenac`).
4. Configure os seguintes campos:
   - **Name**: `natalsenac` (ou o nome que desejar)
   - **Branch**: `main`
   - **Build Command**: *(deixe em branco)*
   - **Publish Directory**: `./` (ou deixe em branco/padrão)
5. Clique em **Create Static Site**.
6. Em instantes o site estará no ar com HTTPS gratuito!
