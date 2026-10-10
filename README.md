# Libras Ao Vivo 5.5

## O que está incluído
- Um `index.html` independente, sem CDN ou bibliotecas JavaScript externas.
- 30 termos com **animações ilustrativas genéricas** de avatar (não representam sinais corretos de Libras).
- Reprodução automática de vídeos MP4/WebM de sinais que o usuário tenha obtido legalmente e validado.
- Legendas por reconhecimento de fala do navegador, quando disponível, ou entrada manual.
- Fila automática de termos, controle de reprodução, histórico e exportação TXT.
- Teste de microfone com medidor de intensidade e mensagens de diagnóstico.

## Atenção
**O projeto NÃO contém 30 sinais validados em Libras nem traduz frases de maneira linguisticamente correta.** As animações demonstram apenas o fluxo visual e são rotuladas como ilustrações. Somente os vídeos cadastrados pelo responsável podem conter Libras real, desde que validados por usuários fluentes e intérpretes. A correspondência textual exata e reprodução palavra a palavra não constituem interpretação profissional.

## Como testar
Hospede `index.html` por HTTPS (p.ex. GitHub Pages). No celular, abra no navegador compatível, teste microfone, encerre o teste e inicie a escuta. O Web Speech API pode depender do serviço de reconhecimento do navegador, da conexão e de permissões. Para testar sem captura, digite uma frase e toque em **Interpretar biblioteca**.

## Colocar vídeos autênticos no pacote
O botão de cadastro aceita um vídeo MP4/WebM por termo, armazenado na sessão como URL local de objeto; ao fechar a página, o cadastro desaparece. Para distribuição offline permanente, os arquivos de vídeos licenciados deverão ser disponibilizados com o pacote, e o carregamento por caminhos relativos deverá ser desenvolvido. Evite afirmar cobertura de Libras sem revisão humana.

## Testes recomendados
Android Chrome via HTTPS, permissões, interrupções de sessão, ausência de rede, feedback de usuários surdos, qualidade linguística dos vídeos, sincronização, desempenho e acessibilidade.

Copyright © 2026 Nailson Rodrigues de Lima.
