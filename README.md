# Ophir B7

App de gestão de negócios para corretores de imóveis — desenvolvido para Lucas.

## Funcionalidades

- **Painel** — visão geral do mês: entradas, saídas, pipeline e versículo do dia
- **Finança** — registro de comissões e despesas com categorias
- **Agenda** — compromissos com exportação para Apple Calendário e Google Agenda
- **Funil** — pipeline de vendas (Lead → Visita → Proposta → Fechado / Perdido)
- **Metas** — acompanhamento de metas com barra de progresso
- **Planos** — projetos com lista de etapas e checkboxes

## Tecnologia

- HTML/CSS/JavaScript puro — sem dependências externas
- **Armazenamento local** via `localStorage` (dados ficam no dispositivo/navegador)
- **PWA** — instalável como app no celular ou desktop
- **Offline** — funciona sem internet após o primeiro acesso

## Instalação como app (PWA)

### iPhone / iPad
1. Abra o site no Safari
2. Toque em **Compartilhar** → **Adicionar à Tela de Início**

### Android
1. Abra no Chrome
2. Menu (⋮) → **Adicionar à tela inicial**

### Desktop (Chrome / Edge)
1. Clique no ícone de instalação na barra de endereço

## Backup dos dados

Os dados são salvos **localmente no navegador**. Para não perder nada:

1. Toque em **↓ Exportar** no topo do app — baixa um arquivo `.json`
2. Guarde o arquivo no Google Drive, iCloud ou qualquer lugar seguro
3. Para restaurar: **↑ Importar** e selecione o arquivo

## Deploy no GitHub Pages

1. Crie o repositório no GitHub (ex: `ophir-b7`)
2. Faça push dos arquivos:
   ```bash
   git remote add origin https://github.com/SEU_USUARIO/ophir-b7.git
   git push -u origin main
   ```
3. Vá em **Settings → Pages → Branch: main → Save**
4. O app estará em `https://SEU_USUARIO.github.io/ophir-b7`

## Ícones (opcional)

Adicione `icon-192.png` e `icon-512.png` na raiz do projeto para o ícone aparecer ao instalar o PWA. Use fundo escuro (`#060912`) com o texto "B7" em dourado.
