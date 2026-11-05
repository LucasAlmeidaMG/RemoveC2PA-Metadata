# C2PA Remover

Ferramenta web estática para gerar cópias limpas de imagens, removendo metadados incorporados por reexportação no navegador.

## Recursos

- Processamento 100% local com Canvas API.
- Suporte a JPG, JPEG, PNG e WebP.
- Até 4 imagens por seleção ou arrastar e soltar.
- Processamento sequencial para reduzir o consumo de memória.
- Preservação das dimensões originais e da transparência quando possível.
- Download individual de cada imagem processada.
- Nenhum upload, analytics, rastreador ou armazenamento local.

## Uso

Abra o arquivo `index.html` em um navegador moderno ou publique o projeto em GitHub Pages, Netlify ou Vercel.

Selecione ou arraste até quatro imagens. Cada arquivo será processado individualmente e poderá ser baixado pelo respectivo botão.

## Limitações

A imagem é recodificada a partir dos pixels. Podem ocorrer diferenças de compressão, cores ou tamanho. A ferramenta não remove marcas d'água que estejam presentes nos pixels e não implementa detector de C2PA.

## Privacidade

O processamento acontece exclusivamente no navegador. Nenhuma imagem é enviada para servidores.
