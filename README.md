# 🚗 Car Shop API

API RESTful para gerenciamento de uma concessionária de veículos, desenvolvida com princípios de Programação Orientada a Objetos e utilizando MongoDB via Mongoose durante o curso da Trybe.

## 📌 Funcionalidades
- C.R.U.D
- Cadastro, listagem, atualização e exclusão de carros e motos.
- Separação por camadas (Controller, Service, Model, etc.).
- Aplicação de boas práticas com interfaces, classes de domínio e abstrações.
- Testes unitários com cobertura de código.

## 🛠 Tecnologias

- Node.js
- TypeScript
- Express
- MongoDB + Mongoose
- Docker
- Mocha, Chai e Sinon (testes)

## 🚀 Como rodar localmente

### Com Docker

```bash
docker-compose up -d
docker exec -it car_shop bash
npm install
npm run dev
```

### Sem Docker

```bash
npm install
npm run dev
```

## 🧪 Executar testes
```bash
npm test
```
