# ignite-desafio07-construindo-com-serverless
Desafio 01 - Construindo com serverless


## Instação de dependências e executação do Projeto

```yarn add serverless-offline -D```

```yarn add aws-sdk```




Configuração AWS:
https://aws.amazon.com/pt/

Criar o S3
1 - criar um novo usuario

aws001

Usuário
aws002

Adicionar Usuário:
aws003

Colocar o nome:
aws004

Procura o s3, para polica de permições:
aws005

Na tela que se abre e so dar um proximo.
aws006

Criar usuário
aws007

Agora copiar a chave de acesso:
E o exibir ao lado
aws008

Retorna a busca e digita S3
aws009

Criar um Buckets
aws010

aws011

aws012

aws013

Configura as variaveis de hambiente
Digita no google:
aws sdk environment
aws014

2 
Saber se ja tem essa credecial:
```cd ~/.aws```

```ls```
Se ja existi e so utilisa  aflag -o
```yarn serverless config credentials --provider aws --key=AKIAYORDYZYHLBI4XWAD --secret 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 -o```


Caso seja a primeira vez:
```yarn serverless config credentials --provider aws --key=AKIAYORDYZYHLBI4XWAD --secret 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```

```yarn deploy```

Para limpa:

```yarn serverless remove```



https://www.notion.so/Desafio-01-Construindo-com-serverless-1fdde2c717a94f7aa077e746cb077bec#43710864611c4079ad6428f2d9aa2213