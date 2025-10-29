# Primeira-Stack-com-AWS-CloudFormation

## Descrição:
- Primeira Stack com AWS para simular um pedido numa livraria.

Explicação do fluxo:
- S3 Bucket → armazena os arquivos da loja 
- Lambda → processa o pedido quando alguém faz a compra
- API Gateway → recebe requisições HTTP (POST /pedido) e envia para o Lambda.
- Permissões IAM → permitem que o Lambda acesse logs e arquivos no S3, e que o API Gateway invoque o Lambda.

- <img width="1172" height="480" alt="Image" src="https://github.com/user-attachments/assets/ceafb6c1-901e-4aeb-b467-edbd86918e09" />

  
