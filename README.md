# Documento Local

Aplicação estática para converter cotações de custos, notas de débito e ordens de compra em Excel.

- Cotações: leitura de PDFs, revisão dos campos e exportação nos modelos de ferramental e try-out.
- Notas de débito: importação de PDFs ou ZIP, consolidação dos itens e conferência dos totais.
- Ordens de compra: resumo, valores brutos, líquidos e impostos em quatro abas.

## Uso

Abra o site, escolha o tipo de documento, importe os arquivos, confira os valores e baixe o Excel. Os exemplos incluídos são fictícios. Os leitores reconhecem layouts específicos de PDF com texto; documentos digitalizados precisam de OCR antes da importação.

## Privacidade

O processamento dos documentos acontece no navegador. O aplicativo não contém servidor de upload, analytics nem armazenamento remoto. As bibliotecas PDF.js, JSZip e SheetJS são carregadas do cdnjs. A hospedagem e o CDN recebem as requisições normais de acesso.

Os modelos públicos não contêm logotipos, dados reais de exemplo, contatos, autores, caminhos locais ou histórico do arquivo de origem. Preços, taxas comerciais e condições preenchidas originalmente foram removidos; confira valores que não puderem ser extraídos do seu PDF.

Os documentos importados e os arquivos exportados preservam os dados fornecidos pelo usuário: esta aplicação não anonimiza documentos de entrada.

## Hospedagem

Sem build ou backend. No GitHub Pages, publique a raiz da branch `main`.
