# Deploy de App com Docker e Agente de IA Para Provisionamento de Infraestrutura com IaC

## Estrutura:

```
.
├── app
│   ├── app.py
│   └── requirements.txt
├── .env
├── docker-compose.yml
└── Dockerfile
```

## Passo 1: Arquivos e Diretórios

- Crie a estrutura de diretórios e os arquivos acima.

## Passo 2: Configure sua Chave de API da OpenAI

## Passo 3: Construa e Execute o Contêiner Docker

docker-compose -p agent_app_terraforma up --build

## Passo 4: Interaja com o Agente

- Após a conclusão do comando, abra seu navegador e acesse:

http://localhost:8501

- Teste a app, por exemplo, com esse texto: Crie o código IaC com Terraform para criar um bucket S3 na AWS com o nome 'bucket-super-seguro-12345', com versionamento e criptografia SSE-S3 habilitados.
