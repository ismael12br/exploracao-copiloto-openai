# 📄 Testes com ChatGPT-4o

Este documento reúne os experimentos realizados utilizando o **ChatGPT-4o** através da plataforma web da OpenAI, conforme proposto no laboratório do bootcamp.

---

## Configuração

A partir do Azure Ai Foundry foi criada uma implantação do ChatGPT-4o com o intuito de explorar suas capacidades de resposta utilizando alguns prompts elencados abaixo.

![Criação do projeto no Azure Ai Foundry](....images/explorando-chatgpt-4o/criacao.png)



### Prompt 1: Estou planejando viajar para Pernambuco em maio. Você consegue me ajudar?

Foi observado que a IA não gerou informações gerais sobre o destino, mas buscou entender melhor qual a dúvida sobre o destino da viagem para desenvolver uma resposta mais precisa.

### Prompt 2: Quais são os melhores locais para ficar em Pernambuco?

Dado o contexto que Pernambuco é um Estado, a IA buscou destinos diversos com pontos turísticos relevantes naquele Estado, incluindo o perfil de quem busca estes destinos.

### Prompt 3: Baseado no link acima, me informe quais são os eventos mais importantes na história de Pernambuco.

A IA não obteve êxito neste teste, pois não conseguiu ler, mas elencou uma lista com evento históricos a partir de suas bases de dados para não deixar o operador sem resposta.

### Prompt 4: Liste 3 lugares que você recomenda para eu me hospedar em Pernambuco e que fique a uma curta distância de atrações históricas. Justifique sua resposta.

Foi possível perceber a que IA tentou buscar locais próximos daqueles que possuem maior concentração de atrações históricas, incluindo a jsutificativa da escolha como solicitado no prompt.

### Prompt 4: Quais são os 10 principais pontos turísticos de Pernambuco? Responda com uma lista numerada em ordem de popularidade.

A IA não obteve dificuldades em gerar a reposta, construindo uma lista e justificando o motivo da seleção do ponto turístico na lista.

---

Os prompts testados tinham a intenção de testar determinados tipos de respostas geradas, como:
- Resposta específica;
- Resposta com escopo específico de informações;
- Resposta com relevância maximizada por contexto;
- Resposta com expectativa definida.
