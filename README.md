# 5W2H_Problema_Social_TransporteEscolar — VansLink

> Objetivo: estruturar o **problema social** do transporte escolar (vans) de forma clara e mensurável,
> servindo como base para o Design Thinking, requisitos e backlog do MVP.

---

## 1) WHAT — O que está acontecendo? (Problema)
A contratação e o acompanhamento do transporte escolar por vans, em muitos contextos, ocorre de forma **informal e fragmentada**, o que gera:

- dificuldade para responsáveis encontrarem e compararem opções confiáveis
- falta de transparência sobre rota, horários, vagas e substituições
- ausência de confirmação padronizada de **embarque (check-in)** e **desembarque (check-out)**
- comunicação falha sobre atrasos e ocorrências
- falta de registros/histórico para reduzir conflitos e melhorar previsibilidade

**Resumo do problema em 1 frase:**
> Responsáveis não conseguem contratar e acompanhar o transporte escolar com segurança e previsibilidade porque não há um sistema padronizado para organizar rotas, vagas, comunicação e registros do serviço.

---

## 2) WHY — Por que isso é um problema? (Impactos)
### Impactos para responsáveis (pais/mães)
- insegurança e ansiedade no dia a dia
- falta de confirmação de embarque/desembarque
- dificuldade para tomar decisão (comparar opções)
- desgaste por mensagens repetidas e falta de respostas

### Impactos para motoristas/monitores
- retrabalho e sobrecarga de comunicação (muitas mensagens)
- maior chance de erros operacionais (lista manual, confusão de pontos/alunos)
- conflitos sem registro/histórico do que ocorreu
- perda de tempo e dificuldade de organizar rota/vagas

### Impactos sociais e comunitários
- desigualdade de acesso (quem não tem indicação fica sem opção)
- falta de padronização e rastreabilidade em ocorrências
- atraso e instabilidade na rotina escolar (pontualidade)

---

## 3) WHERE — Onde ocorre?
- principalmente em contextos onde a contratação é feita por:
  - indicação (bairro, grupos de pais, escola)
  - WhatsApp e conversas individuais
- em bairros/cidades com grande demanda por transporte escolar e pouca estrutura formal de comparação e gestão

> Observação: o problema pode existir tanto em cidades grandes quanto médias, especialmente onde há forte dependência de vans/serviços autônomos.

---

## 4) WHEN — Quando acontece (momentos críticos)?
### Picos de contratação
- início do ano letivo
- mudança de escola / turno
- mudança de endereço
- quando um motorista “para” e famílias precisam de substituto rápido

### Picos de conflito operacional
- dias de chuva/trânsito forte
- manutenção/quebra do veículo
- alterações emergenciais na rota
- faltas do aluno sem aviso
- substituição de motorista/van sem comunicação clara

---

## 5) WHO — Quem é afetado?
### Atores diretamente afetados (primários)
- **Responsáveis (pais/mães)**: contratam, pagam, acompanham
- **Alunos**: dependem do serviço (dados sensíveis)
- **Motoristas/monitores**: executam rota e comunicação

### Atores indiretamente afetados (secundários)
- **Escolas**: recebem reclamações e impactos de atrasos
- **Comunidade**: redes de indicação e confiança locais
- **Órgãos/regulação local**: (fora do escopo do MVP, mas existentes no mundo real)

---

## 6) HOW — Como ocorre hoje? (AS-IS)
### Contratação
1. responsável pede indicação em grupos
2. pega contato do motorista
3. negocia por WhatsApp (horário, bairro, preço, vagas)
4. combina informalmente

**Falhas comuns:**
- informação despadronizada
- falta de histórico confiável
- difícil comparar opções
- dependência de indicações

### Operação diária
- pais perguntam “já passou?”, “vai atrasar?”, “pegou meu filho?”
- motorista responde quando consegue
- check-in/out não é padronizado
- atrasos e ocorrências viram “conversa” e discussão

**Falhas comuns:**
- ansiedade e insegurança
- excesso de mensagens
- sem registro oficial dos acontecimentos

---

## 7) HOW MUCH — Quanto custa / como medir? (Indicadores)
> No PI, você pode medir com entrevistas/simulação e comparar antes/depois do MVP.

### Indicadores do problema (diagnóstico)
- **Tempo médio para encontrar uma van confiável** (dias/semanas)
- **% de atrasos sem aviso** (em uma semana/mês)
- **Nº de mensagens por dia** entre pais e motorista (sobre o mesmo tema)
- **Nº de conflitos/reclamações** por mês
- **Taxa de troca de motorista/van** por insatisfação

### Indicadores de melhoria com o VanLink (sucesso do MVP)
- **% de dias com check-in/out registrados**
- **Tempo para o responsável encontrar rota e solicitar vaga**
- **Redução de mensagens repetidas** (ex.: “já passou?”)
- **Nº de avisos padronizados enviados pelo motorista** (em vez de responder 1 a 1)
- **Registro de ocorrências por rota/dia** com histórico acessível

---

# 8) Declaração final do problema (para usar em apresentação)
> “Atualmente, o transporte escolar por vans é contratado e operado com informações dispersas e comunicação informal, o que causa insegurança e ansiedade em responsáveis, retrabalho para motoristas e falta de rastreabilidade em atrasos e ocorrências. Isso dificulta comparar opções confiáveis, acompanhar embarque/desembarque e reduzir conflitos.”

---

# 9) Conexão com o MVP (o que esse 5W2H exige do sistema)
Prioridades derivadas diretamente do problema:
1. Cadastro padronizado de rotas (escola, bairros, horários, vagas)
2. Solicitação de vaga com status (pendente/aprovado/recusado)
3. Check-in/out do aluno (registro simples)
4. Aviso de atraso/ocorrência padronizado
5. Histórico por dia/rota (rastreabilidade básica)
6. Perfis e permissões (responsável/motorista/admin)
7. Dados mínimos e fictícios (privacidade/LGPD no contexto acadêmico)
