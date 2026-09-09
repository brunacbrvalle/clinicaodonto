# clinicaodonto
Projeto de Sistema Clinica Odontológica/Estética
# Sistema de Gestão para Clínica Odontológica e Harmonização Facial (HOF)

Este repositório contém o projeto de um sistema web para gestão completa de uma clínica especializada em Odontologia Geral e Harmonização Orofacial. O projeto engloba desde a modelagem de processos (BPMN), arquitetura do sistema e banco de dados, até o desenvolvimento do frontend e backend.

---

## 1. Fluxo de Trabalho e Processos (BPMN)

O fluxo cobri toda a jornada do paciente, desde a captação do lead até o pós-tratamento e
manutenção.

### Estrutura do Fluxograma:
* **Piscina (Pool) - Processo Clinica:**
  * **Raia Recepção:** Agendamento, triagem, envio de pesquisas de satisfação e mensagens de retorno.
  * **Raia Profissional de Saúde:** Anamnese digital, plano de tratamento, orçamento, registro de fotos (antes/depois) e execução das sessões.
  * **Raia Financeiro/Comercial:** Negociação, emissão de contratos/TCLE, registro de vendas e *follow-up*.

<img width="2976" height="2278" alt="Modelo Clinica" src="https://github.com/user-attachments/assets/5d69023f-277d-4b60-a149-b9033b54b4e2" />

##  2. Tecnologias Utilizadas


* **Modelagem de Processos:** Bizagi / BPMN 2.0
* **Modelagem de Banco de Dados:** MySQL Workbench / BR Modelo
* **Arquitetura:** Draw.io
* **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 5.
* **Backend:** PHP / Node.js
* **Banco de Dados:** MySQL

---

## 3. Funcionalidades do Sistema

1. **Gestão de Pacientes:** Cadastramento inicial e agendamentos de avaliação.
2. **Prontuário Eletrônico:**
   * Anamnese geral e ficha específica para procedimentos de HOF (toxina, preenchedores, etc.).
   * Histórico de sessões e galeria de fotos (Antes/Depois).
3. **Módulo Financeiro & Contratos:**
   * Aprovação de orçamentos.
   * Geração de contrato e Termo de Consentimento Livre e Esclarecido (TCLE).
4. **Controle de Acesso (RBAC):** Tela de login e permissões diferenciadas por nível de usuário (Recepção, Profissional de Saúde, Financeiro/Admin).

---
