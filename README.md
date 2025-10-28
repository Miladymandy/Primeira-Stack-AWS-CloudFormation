# Primeira-Stack-com-AWS-CloudFormation

## Descrição:
- Primeira Stack com AWS para simular um pedido numa livraria.

Explicação do fluxo:
- S3 Bucket → armazena os arquivos da loja 
- Lambda → processa o pedido quando alguém 
- API Gateway → recebe requisições HTTP (POST /pedido) e envia para o Lambda.
- Permissões IAM → permitem que o Lambda acesse logs e arquivos no S3, e que o API Gateway invoque o Lambda.

  
