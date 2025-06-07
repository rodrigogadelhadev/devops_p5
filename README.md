# Projeto DevOps - Aplicação Full Stack

## 📋 Descrição
Este é um projeto full stack que demonstra a integração entre um frontend React com TypeScript e um backend Node.js, utilizando práticas modernas de DevOps para desenvolvimento e implantação.

## 🚀 Tecnologias Utilizadas

### Frontend
- React.js com TypeScript
- CSS para estilização
- Testes unitários com Jest

### Backend
- Node.js com TypeScript
- TypeORM para gerenciamento de banco de dados
- Decorators para metadados

### DevOps
- Docker e Docker Compose para containerização
- Ambiente de desenvolvimento isolado
- Configuração padronizada entre ambientes

## 🛠️ Estrutura do Projeto

```
├── frontend/           # Aplicação React
│   ├── src/            # Código fonte do frontend
│   ├── public/         # Arquivos públicos
│   └── Dockerfile      # Configuração do container
│
├── backend/            # Servidor Node.js
│   ├── src/            # Código fonte do backend
│   ├── entities/       # Entidades do TypeORM
│   └── Dockerfile      # Configuração do container
│
└── docker-compose.yml  # Orquestração dos containers
```

## 🚦 Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/rodrigogadelhadev/devops_p5.git
cd devops_p5
```

2. Inicie os containers:
```bash
docker-compose up -d
```

3. Acesse a aplicação:
- Frontend: http://localhost:3000
- Backend: http://localhost:3001

## 📝 Configuração

As configurações do ambiente estão no arquivo `.env`. Certifique-se de configurá-lo corretamente antes de executar a aplicação.

## 🤝 Contribuição

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/NovaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/NovaFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Desenvolvido com ❤️ por [Rodrigo Gadelha](https://github.com/rodrigogadelhadev)