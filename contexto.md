# Contexto das Alterações

## Problema
A imagem do card de prato estava "quebrada" (distorcida ou fora do layout) devido à configuração inadequada do tamanho e do flexbox no CSS.

## O que foi feito
- Ajustei o container da imagem (.dish-image-container) para ter largura fixa de 120px e altura fixa de 68px, mantendo a proporção 16:9.
- Removi o uso de aspect-ratio e height: auto, que causavam inconsistências.
- Ajustei o flex do container do conteúdo do card (.card-dishes-content) para alinhar corretamente o texto e a imagem, adicionando espaçamento (gap) e alinhamento vertical.
- Garanti que a imagem preencha todo o espaço do container usando object-fit: cover, evitando distorções.

## Resultado
O card agora exibe a imagem corretamente, alinhada ao lado das informações do prato, sem distorções ou quebras de layout, proporcionando uma visualização mais agradável e profissional.