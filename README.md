# Gerador de QR Code

Ferramenta web simples para gerar QR Codes a partir de links.

**Acesse em produção:** [https://qrcode.gustavomotta.dev.br](https://qrcode.gustavomotta.dev.br)

---

## Sobre

Uma ferramenta web gratuita para gerar QR Codes de forma rápida e sem complicação.  

Diferente de várias soluções SaaS, aqui não há cadastro, limites artificiais ou planos pagos. A interface é direta e pensada para ser fácil de usar: escolha o tipo de link, preencha os dados e baixe o QR Code em PNG.

---

## Funcionalidades

- **Aba Livre** — gera QR Code a partir de qualquer URL
- **Aba WhatsApp** — gera QR Code com link `wa.me` e mensagem opcional pré-preenchida
- **Aba Como usar** — instruções claras de uso da ferramenta
- Preview do link gerado em tempo real (estilo terminal)
- Botões **Copiar** e **Testar** o link
- Controle de tamanho do QR Code via slider (200 a 1000 px)
- Download do QR Code em formato PNG
- Design responsivo (funciona bem em celular e desktop)

---

## Como usar

1. Acesse a ferramenta (localmente ou pelo site em produção).
2. Escolha a aba desejada:
   - **Livre** → cole a URL completa (sempre com `https://`)
   - **WhatsApp** → digite o número com DDI + DDD (ex: `5547999999999`) e, se quiser, uma mensagem
3. Ajuste o tamanho do QR Code pelo slider, se necessário.
4. Clique em **Gerar QR Code**.
5. Use os botões **Copiar** ou **Testar** para verificar o link.
6. Clique em **Baixar PNG** para salvar a imagem.

---

## Como rodar localmente

1. Clone o repositório ou baixe os arquivos:
   ```bash
   git clone https://github.com/MottaGustavo/gerador-qrcode.git