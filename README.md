# Sistema de Gestão de Fazendas e Colheitas

## Visão Geral
Este projeto implementa um sistema de gestão de fazendas e colheitas utilizando o padrão de arquitetura MVC (Model-View-Controller) em Java. O sistema permite cadastrar fazendas, registrar colheitas, gerenciar inventário e calcular o valor dos produtos, tudo através de uma interface gráfica baseada em JOptionPane.

## Estrutura do Projeto

### Model (Modelo)
- **Farm**: Representa uma fazenda com nome, endereço, tipo de plantio e área de cultivo.
- **Harvest**: Representa uma colheita com capacidade, tipo de plantio, condições climáticas, quantidade produzida, data da colheita, preço por unidade e quantidade restante.

### View (Visão)
- **FarmView**: Responsável por coletar e exibir informações sobre fazendas utilizando JOptionPane.
- **HarvestView**: Responsável por coletar e exibir informações sobre colheitas utilizando JOptionPane.
- **InventoryView**: Responsável por gerenciar a exibição e manipulação do inventário utilizando JOptionPane.
- **MainView**: O ponto de entrada do programa, contendo o menu principal e coordenando a interação com o usuário.

### Controller (Controlador)
- **FarmController**: Gerencia as operações relacionadas às fazendas, incluindo adicionar, remover e listar fazendas.
- **HarvestController**: Gerencia as operações relacionadas às colheitas, incluindo adicionar, listar e atualizar a quantidade de colheitas.
- **InventoryController**: Gerencia o inventário dos produtos colhidos, incluindo adicionar, remover e calcular o valor total dos produtos no inventário.

## Funcionalidades Implementadas

### Cadastrar Fazenda
- Coleta informações sobre a fazenda (nome, endereço, tipo de plantio, área de cultivo) e adiciona ao sistema.

### Cadastrar Colheita
- Coleta informações sobre a colheita (capacidade, tipo de plantio, condições climáticas, quantidade produzida, data da colheita, preço por unidade) e adiciona ao sistema.

### Visualizar Fazendas Cadastradas
- Exibe uma lista de todas as fazendas cadastradas no sistema.

### Visualizar Colheitas Cadastradas
- Exibe uma lista de todas as colheitas cadastradas no sistema.

### Gestão de Inventário
- Permite adicionar produtos ao inventário com base nas colheitas cadastradas, remover produtos do inventário e visualizar o inventário atual, incluindo a quantidade e o valor dos produtos restantes.

### Excluir Fazenda
- Permite excluir uma fazenda do sistema pelo nome.

## Pontos Importantes para Apresentação

### Explicação da Arquitetura MVC
- **Model**: Classes que representam os dados do sistema (Farm e Harvest).
- **View**: Classes que gerenciam a interface com o usuário (FarmView, HarvestView, InventoryView).
- **Controller**: Classes que coordenam as interações entre a View e o Model (FarmController, HarvestController, InventoryController).

### Funcionalidades Principais
- Cadastrar fazendas e colheitas com todos os detalhes relevantes.
- Visualizar listas formatadas de fazendas e colheitas cadastradas.
- Gerenciar o inventário de produtos, incluindo a adição, remoção e cálculo do valor total dos produtos.

### Interface Gráfica
- Utilização do JOptionPane para entrada e saída de dados, proporcionando uma interface gráfica simples e interativa.

### Tratamento de Erros
- Conversão de vírgulas para pontos decimais para evitar `NumberFormatException`.
- Mensagens de erro informativas para entradas inválidas ou operações inválidas.

### Extensibilidade e Manutenibilidade
- Separação clara das responsabilidades através do padrão MVC facilita a manutenção e a adição de novas funcionalidades.

Com esta abordagem, o sistema não só atende aos requisitos especificados, mas também proporciona uma base sólida para futuras expansões e melhorias.


### UC Programação de soluções computacionais

### Membros

- Felipe Reis Nascimento – RA: 323210811
- Weslley Bruno Almeida Santos – RA: 32328864
- Charles Miller De Souza Nascimento – RA: 32326802

## Professores
- Adalto Sparremberger
- Adalberto Gessenferth
