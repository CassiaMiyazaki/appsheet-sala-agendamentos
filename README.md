# AppSheet + Google Apps Script: Agendamento de Salas

Este projeto permite o agendamento de salas utilizando o AppSheet integrado ao Google Apps Script.
Ao preencher um formulário no AppSheet (vinculado ao Google Sheets), o script verifica conflitos de horário e registra automaticamente os blocos de agendamento.

## 📌 Funcionalidades

- Registro de agendamentos em blocos de 30 minutos
- Verificação de conflitos de horário
- Mensagens de alerta para campos obrigatórios
- Interface simples via AppSheet
- Integração com Google Planilhas

## 🧠 Tecnologias Utilizadas

- **Google Apps Script**
- **Google Sheets**

## 📝 Scripts

Os scripts estão na pasta `/scripts`. O principal é `agendamento`, responsável por:

- Validar os campos do formulário
- Converter horários em blocos
- Verificar conflitos
- Registrar os dados



