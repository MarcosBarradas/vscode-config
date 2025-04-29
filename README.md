# ⚙️ VSCode Settings Personalizados

Este documento lista e explica as configurações personalizadas do `settings.json` usadas no VSCode, otimizadas para desenvolvimento com HTML, JavaScript e React.

---

## 🎨 Aparência e Fonte do Editor

### `"editor.fontFamily": "IBM Plex Mono"`
→ Define a fonte usada no editor como IBM Plex Mono.

### `"editor.fontWeight": "500"`
→ Deixa o texto com peso de fonte 500 (seminegrito).

### `"editor.fontSize": 16`
→ Tamanho da fonte no editor: 16px.

### `"editor.lineHeight": 28`
→ Altura de linha: espaço entre linhas é 28px (deixa o texto mais espaçado).

---

## 🛠️ Edição de Código

### `"editor.tabSize": 2`
→ Cada tabulação (TAB) vai ter 2 espaços.

### `"editor.tabCompletion": "on"`
→ Autocompleta automaticamente palavras ou trechos com a tecla TAB.

### `"editor.wordWrap": "on"`
→ Se o código passar da largura da tela, ele quebra a linha.

### `"editor.formatOnSave": true`
→ Formata o código automaticamente toda vez que você salvar o arquivo.

### `"editor.autoClosingBrackets": "always"`
→ Fecha automaticamente parênteses, colchetes e chaves.

### `"editor.autoClosingQuotes": "always"`
→ Fecha automaticamente aspas simples e duplas.

### `"editor.colorDecorators": false`
→ Desativa pré-visualização de cores (por exemplo, mostrar uma bolinha de cor no CSS).

### `"editor.minimap.renderCharacters": false`
→ Minimapa no lado direito mostra sombras, não texto pequeno.

### `"editor.renderWhitespace": "selection"`
→ Só mostra espaços e tabs quando você seleciona o texto.

### `"editor.bracketPairColorization.enabled": false`
→ Desativa a coloração automática de pares de chaves/colchetes.

---

## 🔥 Live Server

### `"liveServer.settings.donotShowInfoMsg": true`
→ Não mostra mensagens informativas ao iniciar o Live Server.

### `"liveServer.settings.donotVerifyTags": true`
→ Não checa se as tags HTML estão corretas no Live Server.

---

## 📂 Explorer e Interface

### `"explorer.confirmDragAndDrop": false`
→ Não pede confirmação ao arrastar e soltar arquivos no Explorer.

### `"explorer.sortOrder": "default"`
→ Ordem padrão de listagem de arquivos (não é por tipo ou modificação).

### `"breadcrumbs.enabled": false`
→ Esconde a navegação de pastas/arquivos no topo do editor.

### `"workbench.statusBar.visible": true`
→ Mostra a barra de status no rodapé.

### `"window.title": "${activeEditorMedium}${separator}${rootName}"`
→ Personaliza o título da janela mostrando o arquivo aberto + nome do projeto.

### `"window.newWindowDimensions": "inherit"`
→ Novas janelas herdam o tamanho da atual.

---

## 🎨 Tema e Ícones

### `"workbench.colorTheme": "Origamid Next"`
→ Usa o tema de cores Origamid Next.

### `"workbench.iconTheme": "origamid-next-icons"`
→ Usa o pacote de ícones Origamid Next no VSCode.

---

## 🧹 Formatação de Código (Prettier + HTML)

### `"prettier.singleQuote": true`
→ Prettier usa aspas simples no lugar de duplas.

### `"prettier.trailingComma": "all"`
→ Prettier adiciona vírgula no final de objetos e arrays.

### `"[javascriptreact]"` e `"[json]"`
→ Para arquivos .jsx e .json, usa o Prettier como formatador padrão.

### `"[html]"`
→ Para arquivos .html, usa o formatador padrão do VSCode para HTML.

### `"html.autoClosingTags": false`
→ Desativa o fechamento automático de tags no HTML.

### `"html.format.wrapAttributes": "auto"`
→ Organiza atributos HTML automaticamente em várias linhas se necessário.

### `"html.format.wrapLineLength": 0`
→ Não limita o tamanho da linha ao formatar HTML.

---

## 🛡️ Privacidade e Telemetria

### `"telemetry.telemetryLevel": "off"`
→ Desliga o envio de dados e métricas para a Microsoft.

---

## 📁 Arquivos

### `"files.associations": { "*.js": "javascriptreact" }`
→ Trata todos os arquivos .js como JavaScript React (.jsx) no editor.

### `"files.autoSave": "afterDelay"`
→ Salva automaticamente os arquivos depois de um pequeno atraso.

---

## 🎨 Extensão Extra

### `"color-highlight.markerType": "dot-before"`
→ No plugin Color Highlight, a cor aparece como uma bolinha antes do código.

---

## 📄 Licença

Este repositório pode ser usado livremente, com ou sem alterações.  
Caso redistribua, mantenha os créditos à Origamid

---


