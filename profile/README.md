# 🚗 Carona Amiga Universitária

## 📚 Descrição do Projeto
O sistema **Carona Amiga Universitária** tem como objetivo facilitar a divisão de custos de deslocamento entre estudantes universitários, permitindo que alunos ofereçam e reservem vagas em caronas de forma simples e organizada.

O projeto trabalha com dois perfis principais:

- **Motorista** → responsável por oferecer caronas.
- **Passageiro** → responsável por buscar e reservar vagas.

---

# 👨‍💻 Integrantes
- Arthur Rodrigues
- Luis Fernando

---

# 🎯 Objetivo
Desenvolver uma aplicação capaz de:

- Cadastrar caronas disponíveis;
- Permitir busca de caronas por destino;
- Controlar vagas disponíveis em cada veículo;
- Registrar histórico de utilização dos usuários.

---

# 🧩 Funcionalidades

## ✅ Oferta de Carona
O motorista poderá cadastrar uma nova carona informando:

- Origem;
- Destino;
- Horário;
- Quantidade de vagas disponíveis.

---

## 🔍 Busca de Caronas
Os passageiros poderão buscar caronas disponíveis utilizando o destino como filtro.

---

## 🎫 Reserva de Vaga
O passageiro poderá reservar uma vaga em uma carona disponível.

### Regras:
- A quantidade de vagas será decrementada automaticamente;
- Não será possível reservar vagas quando o limite for atingido.

---

## 📜 Histórico de Caronas
Cada usuário poderá visualizar:

- Caronas oferecidas;
- Caronas reservadas;
- Histórico completo de deslocamentos.

---

# 🧠 Lógica Central do Sistema

Uma **Carona** possui:

- Motorista responsável;
- Lista de passageiros;
- Número máximo de passageiros definido pela capacidade do veículo.

### Regra Principal
O sistema deve impedir reservas acima da capacidade do veículo.

---
