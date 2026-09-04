# OrganizaDia Web v1.1

Sistema 100% Web, sem Python e sem banco de dados externo.

## Funções
- Tarefas com data, prioridade e observações
- Ações com status: Pendente, Em andamento e Concluída
- Progresso automático (Em andamento conta como 50%)
- Filtros por status, seleção, busca e data
- Exportação para CSV
- Compartilhamento com WhatsApp
- CSV → WhatsApp
- Backup e restauração em JSON
- Resumo em TXT
- Layout responsivo para computador e celular
- PWA instalável em HTTPS

## Dados
Os dados ficam no `localStorage` do navegador. Cada navegador/dispositivo possui sua própria base. Use o backup JSON para transferir os dados entre aparelhos.

## GitHub Pages
Endereço esperado após ativar o Pages:

`https://leonardoperuzzolourenco-dotcom.github.io/organiza-dia/`

## CSV → WhatsApp
Se houver tarefas marcadas, o CSV contém somente elas. Caso contrário, usa as tarefas visíveis pelos filtros.

No celular, navegadores compatíveis abrem o menu de compartilhamento com o CSV anexado. No computador, o arquivo é baixado e o WhatsApp Web é aberto para você anexá-lo.