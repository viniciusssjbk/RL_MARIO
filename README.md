# Super Mario Bros Reinforcement Learning Environment

Este projeto apresenta a configuração de um ambiente do Super Mario Bros utilizando Python, Gym, NES-Py e Gym Super Mario Bros. O objetivo é preparar o ambiente para experimentos e estudos em Aprendizado por Reforço (Reinforcement Learning).

## Objetivo

Configurar e validar um ambiente de execução do Super Mario Bros para servir como base para o desenvolvimento e treinamento de agentes inteligentes.

## Tecnologias

- Python 3
- Gym
- Gym Super Mario Bros
- NES-Py
- Jupyter Notebook

## Instalação

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

Instale as dependências:

```bash
pip install gym
pip install gym-super-mario-bros
pip install nes-py
pip install notebook
```

Ou, caso exista um arquivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

## Execução

Inicie o Jupyter Notebook:

```bash
jupyter notebook
```

Abra o arquivo:

```
Ambiente_MARIO_RL.ipynb
```

Execute todas as células do notebook.

## Funcionalidades

- Criação do ambiente `SuperMarioBros-v1`
- Renderização do jogo em tempo real
- Utilização do conjunto de ações `SIMPLE_MOVEMENT`
- Execução de ações aleatórias para validação do ambiente
- Reinicialização automática quando necessário

## Estrutura do Projeto

```
.
├── Ambiente_MARIO_RL.ipynb
├── README.md
└── requirements.txt
```

## Próximos Passos

Este projeto faz parte de uma sequência de estudos em Aprendizado por Reforço. As próximas etapas incluem:

- Implementação de funções de recompensa
- Treinamento de agentes com Deep Q-Learning (DQN)
- Avaliação do desempenho do agente
- Comparação entre diferentes algoritmos de Reinforcement Learning

## Licença

Este projeto foi desenvolvido para fins de estudo e pesquisa em Inteligência Artificial e Aprendizado por Reforço.
