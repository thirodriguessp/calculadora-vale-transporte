# Calculadora de Vale-Transporte

Ferramenta para calcular o custo de vale-transporte de funcionários a partir dos CEPs de origem e destino, usando a API do Google Maps.

🔗 **Acesse:** https://thirodriguessp.github.io/calculadora-vale-transporte/

---

## Como usar

1. Abra a [calculadora](https://thirodriguessp.github.io/calculadora-vale-transporte/)
2. Informe sua chave da API do Google Maps
3. Preencha o CEP da empresa e o CEP do funcionário
4. Informe os horários de chegada e saída, e a quantidade de dias úteis no mês
5. Clique em **Buscar rotas**

---

## Pré-requisito

É necessária uma chave de API do Google Cloud com as seguintes APIs ativadas:

- **Maps JavaScript API**
- **Directions API**

Para criar uma chave, acesse o [Google Cloud Console](https://console.cloud.google.com/).

---

## Funcionalidades

- Busca rotas de transporte público nos dois sentidos (ida e volta)
- Sugere três cenários de rota:
  - 💰 Mais barata
  - ⚡ Mais rápida
  - 🔀 Menos conduções
- Calcula custo diário e mensal com base nos dias úteis informados
- Permite informar tarifas manualmente quando a API não retorna o valor
- Salva tarifas informadas localmente para reutilização
- Suporte a tema claro e escuro (segue o sistema operacional)

---

## Observações

- A API do Google Maps pode não retornar tarifas para todas as rotas — nesse caso, o campo de tarifa fica disponível para preenchimento manual
- A chave de API é usada apenas no navegador do usuário e não é armazenada em nenhum servidor

---

## Status

Versão inicial — em testes. Feedbacks são bem-vindos.
