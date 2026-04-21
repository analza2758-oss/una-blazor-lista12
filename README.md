# EcoMonitor - Blazor
## 👩‍💻 Identificação
**Nome:** Ana Luiza Martins Pereira  
**Curso:** Ciências da Computação  

## 💡 Descrição do Projeto
O projeto consiste no desenvolvimento de um componente reutilizável em Blazor chamado **EcoStatus**, utilizado para monitorar ações sustentáveis como reciclagem de plástico, plantio de árvores e descarte de eletrônicos. Cada ação possui um contador interativo, um peso específico para incremento, uma meta definida e uma barra de progresso que representa visualmente o avanço até o objetivo. Ao atingir a meta, o sistema exibe uma mensagem de reconhecimento ao usuário.

## 🎯 Heurísticas de Nielsen Aplicadas
**1. Visibilidade do status do sistema** – O sistema mantém o usuário informado continuamente ao exibir o valor atualizado do contador e a barra de progresso em tempo real a cada interação com o botão.  
**2. Feedback do sistema** – Ao atingir a meta definida, o sistema apresenta uma mensagem clara (“Meta batida! Você é um herói do planeta!”), fornecendo retorno imediato ao usuário.

## 🚀 Guia de Execução
### ▶️ Executando o projeto via terminal
1. Abra o terminal (CMD ou VS Code)  
2. Navegue até a pasta do projeto:  
cd EcoMonitor  
3. Execute o projeto utilizando HTTPS:  
dotnet run --launch-profile https  
4. Acesse no navegador:  
https://localhost:5067  

## ⚙️ Explicação Técnica
O componente **EcoStatus** foi desenvolvido com foco em reutilização por meio da utilização de parâmetros. Os principais parâmetros utilizados foram: `Titulo`, responsável por definir o nome da ação exibida; `Peso`, que determina o valor incrementado no contador a cada clique; e `Meta`, que define o valor objetivo a ser atingido. Essa abordagem permite reutilizar o componente em diferentes contextos sem duplicação de código. Além disso, foi implementada uma propriedade calculada chamada `Progresso`, responsável por calcular dinamicamente a porcentagem da barra de progresso com base no valor atual e na meta, garantindo atualização automática da interface.

## 📱 Funcionalidades
- Contador interativo  
- Incremento baseado em peso  
- Barra de progresso dinâmica  
- Exibição de mensagem ao atingir a meta  
- Interface organizada em formato de cards  
