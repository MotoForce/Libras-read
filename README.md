# Libras Ao Vivo 5.6 — vídeos autênticos por reconhecimento de fala

## O que realmente acompanha o pacote
- `index.html`: aplicativo completo e independente de frameworks; layout responsivo, captura de voz via Web Speech API nos navegadores compatíveis, diagnóstico de microfone, legendas, histórico, fila sequencial, reprodução de mídia, catálogo pesquisável e upload de vídeos persistido por IndexedDB.
- O exemplo `cachorro` possui **vídeo de sinalização real**, de Fred Maranhão (2007), servido externamente pelo Wikimedia Commons: https://commons.wikimedia.org/wiki/File:Libras-cachorro.ogv . Licença CC BY-SA 3.0, atribuição necessária. Para distribuir ou modificar, siga a licença. O pacote não contém esse vídeo, apenas a URL; não funciona offline sem cópia devidamente licenciada.
- Demais termos (mais de 100) são ENTRADAS DE CATÁLOGO, não são vídeos nem sinais validados. Sem um vídeo cadastrado, o aplicativo informa ausência de sinal — não inventa um gesto.

## Como testar
1. Publique o `index.html` em hospedagem HTTPS (por exemplo GitHub Pages). Em `file://` o microfone e IndexedDB podem não funcionar adequadamente.
2. Digite `cachorro` e toque em 'Procurar e reproduzir' para testar o vídeo real (requer internet e suporte a OGV do navegador).
3. Clique 'Testar microfone'; autorize a permissão, observe a barra e encerre. Clique 'Iniciar escuta' e fale `cachorro`.
4. Para cadastrar sinais próprios: informe palavra, arquivo MP4/WebM/OGV e licença/autoria. O sistema armazena no IndexedDB (somente no dispositivo atual). A biblioteca local pode ser apagada pelo navegador ou modo privado.

## Limites
- Transcrever fala não é traduzir contexto para Libras. A associação exata entre palavras e vídeos é uma **demonstração de glossário**, não tradução fluente. Para palestras reais, mantenha intérprete de Libras.
- Reconhecimento Web Speech é dependente do navegador e pode exigir conexão a serviço externo; não prometa processamento offline ou privacidade de áudio sem verificar o fornecedor do navegador.
- Não está incluso avatar 3D capaz de executar sinais validados; os sinais disponíveis são apresentados como vídeos reais. Um avatar real requer animação articulada validada, expressões não manuais, gramática e direitos de uso de dados de movimento.
- Vídeo Wikimedia em formato OGV pode não funcionar no Chrome Android. O aplicativo reporta falha de reprodução; substitua o item por MP4/WebM autorizado para compatibilidade.
- Para comercializar: verificar a licença de cada vídeo, direitos de imagem e voz e LGPD, bem como validação linguística, testes Android e acessibilidade.

## Autor
Copyright © 2026 Nailson Rodrigues de Lima (código do projeto). Direitos dos vídeos pertencem aos respectivos titulares.
