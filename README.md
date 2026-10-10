# Libras Ao Vivo 5.3

## Início rápido
1. Publique `index.html` em hospedagem HTTPS (por exemplo GitHub Pages). Não use `file://` para testar microfone.
2. Use **Testar microfone**: fale e confira se o nível se movimenta. Encerre o teste antes de começar a transcrição.
3. Toque **Iniciar microfone**, permita acesso e fale claramente. O aplicativo usa o serviço de reconhecimento integrado ao navegador, quando disponível.
4. Caso o reconhecimento falhe, tente desligar o modo contínuo (por padrão ele já fica desligado), atualize o navegador, confira conexão e permissões.
5. Sem reconhecimento, use o campo de digitação e cadastre vídeos de Libras licenciados e linguisticamente validados.

## Limites
- Medidor de áudio comprova apenas entrada de som, NÃO reconhecimento de palavras.
- SpeechRecognition não funciona em todos os navegadores; pode depender de processamento externo e internet.
- Reprodução de vídeos é por correspondência exata de frases cadastradas, não tradução contextual automática para Libras.
- Sinais não são incluídos, por exigir direitos e validação linguística.
- Vídeos ficam no IndexedDB quando disponível. Dados podem ser apagados pelo navegador.
- Testar com pessoas surdas fluentes em Libras e profissionais antes de uso público ou comercial.

Copyright © 2026 Nailson Rodrigues de Lima.
