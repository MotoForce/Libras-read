# Libras Ao Vivo 5.4 — sinais conforme a fala

Abra `index.html` em hospedagem HTTPS (GitHub Pages, Cloudflare Pages etc.) usando navegador que suporte `SpeechRecognition`.

## Novidade
A fala final reconhecida aciona automaticamente uma fila de vídeos previamente cadastrados. O sistema procura correspondências do maior grupo de palavras (até oito) para termos simples, em ordem. Um vídeo termina e o próximo começa. A tela mostra palavras sem vídeo, número de vídeos pendentes e oferece pausa, avanço e limpeza da fila. Use a entrada manual e o botão de demonstração para testar sem microfone.

## Limitações críticas
- **Não traduz português para a gramática da Libras**: a mera sequência de sinais associados a palavras portuguesas não constitui interpretação adequada, podendo alterar o sentido.
- **O pacote não inclui vídeos de sinais**. Para ver sinais reais, cadastre antes vídeos MP4/WebM com permissão de uso e revisão de pessoa fluente em Libras. Somente então o sinal será exibido após reconhecer a fala.
- Dependência de conexão e suporte de `SpeechRecognition`, latência variável no resultado final; não é instantâneo garantido.
- Não substitui intérprete humano e não deve ser a única ferramenta de acesso em situações críticas.
- Vídeos locais IndexedDB podem ser excluídos pelo navegador. Áudio pode ser processado fora do aparelho pelo navegador.

## Teste sugerido
1. Publique em HTTPS e autorize o microfone.
2. Cadastre dois vídeos autorizados com os termos `carro` e `escola`.
3. Diga "O carro chegou na escola" e verifique a reprodução em sequência, e o aviso para palavras sem vídeos.
4. Refaça com digitação manual; confira pausa, pular vídeo e histórico.

Copyright © 2026 Nailson Rodrigues de Lima. Atenção: verifique titularidade de todos os componentes antes de licenciar comercialmente.
