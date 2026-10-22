# Caderno de Python

Curso interativo de Python do zero, em português: 10 módulos com lições, exercícios corrigidos na hora, desafios, revisões e projetos. O Python roda direto no navegador, sem instalar nada, e o app funciona offline depois de aberto uma vez.

## Como publicar no GitHub Pages (grátis)

1. Crie uma conta em [github.com](https://github.com) (se ainda não tiver).
2. Clique em **+** (canto superior direito) → **New repository**.
   - Nome: `caderno-python`
   - Marque **Public**
   - Clique em **Create repository**.
3. Na página do repositório, clique em **uploading an existing file**.
4. Abra a pasta descompactada `caderno-python` no seu computador, selecione **tudo o que está dentro dela** (inclusive as pastas `icons` e `vendor`) e arraste para a página.
5. Clique em **Commit changes**.
6. Vá em **Settings** → **Pages** (menu da esquerda).
   - Em **Source**, escolha **Deploy from a branch**.
   - Em **Branch**, escolha **main** e a pasta **/ (root)** → **Save**.
7. Espere 1 ou 2 minutos e recarregue a página de Settings → Pages. O endereço aparece no topo:
   `https://SEU-USUARIO.github.io/caderno-python/`

## Como instalar no celular

- **Android (Chrome):** abra o endereço → menu ⋮ → **Instalar app** (ou "Adicionar à tela inicial").
- **iPhone (Safari):** abra o endereço → botão **Compartilhar** → **Adicionar à Tela de Início**.

O ícone aparece junto com os outros apps e abre em tela cheia, sem a barra do navegador.

## Como atualizar depois

1. No repositório, clique em **Add file** → **Upload files** e envie os arquivos novos (eles substituem os antigos).
2. Abra o arquivo `sw.js` no GitHub, clique no lápis ✏️ e mude `caderno-v1` para `caderno-v2` (depois `v3`, e assim por diante). Isso avisa os celulares que há uma versão nova.
3. **Commit changes**. Na próxima vez que o app for aberto com internet, ele se atualiza.

## O que tem em cada arquivo

| Arquivo | Para que serve |
|---|---|
| `index.html` | O app inteiro: lições, editor e correção |
| `manifest.webmanifest` | Nome, cores e ícones do app instalado |
| `sw.js` | Guarda o app no aparelho para funcionar offline |
| `icons/` | Ícones do app |
| `vendor/` | O Python que roda no navegador ([Skulpt](https://skulpt.org), licença MIT) |

## Observações

- O progresso fica salvo em cada aparelho. O que for feito no computador não aparece automaticamente no celular.
- Abrir o `index.html` direto do computador (com dois cliques) funciona, mas o modo offline e a instalação só funcionam depois de publicado.
