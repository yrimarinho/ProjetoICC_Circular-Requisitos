# Especificação dos Requisitos de Software (ERS)

## 1. Introdução
### 1.1 Propósito 
Este documento tem como objetivo descrever os requisitos funcionais e não funcionais da **Aplicação
Mobile de Monitoramento do Ônibus Circular** (AMOC) da UFRPE, que será utilizada para 
acompanhar o trajeto dos circulares, contribuindo para uma melhor organização locomotiva dos 
estudantes.
### 1.2 Escopo da aplicação
O **AMOC** fornecerá aos usuários os horários de chegada do circular, bem como sua a tabela de 
horários, localização do veículo em tempo real e o tempo estimado de chegada ao destino, além de 
um mapa exclusivo da universidade, destacando cada parada do circular.
### 1.3 Definições e Abreviações
-**AMOC**: Aplicativo de Monitoramento do Ônibus Circular  
-**UFRPE**: Universidade Federal Rural de Pernambuco  
-**Circular**: Ônibus circular interno da UFRPE   
### 1.4 Referências
[UFRPE. Circular Universitário – Horários e Informações.](http://www.delogs.ufrpe.br/br/content/circular-ufrpe) Acesso em: 15 nov. 2025.  

## 2 Descrição Geral
### 2.1 Perspectiva do produto
O aplicativo terá o intuito de monitorar e acompanhar os ônibus circulares
informando aos discentes sua localização e próxima parada. Além disso, visa
substituir os grupos de redes sociais para acompanhamento desses transportes.
### 2.2 Funções principais
- Monitorar a localização dos ônibus e informar aos estudantes.  
- Informar a parada seguinte em que o ônibus estará.  
- Previsão de chegada na próxima parada.  
### 2.3 Tipos de usuário
- **Estudantes**: discentes da UFRPE  
- **Condutores**: motoristas dos ônibus  
### 2.4 Restrições
As informações salvas dos alunos cadastrados terão que ser atualizadas a cada semestre.
### 2.5 Suposições e Dependências
- Os alunos da UFRPE precisarão se cadastrar.  
- O aplicativo precisará estar conectado a internet e os condutores precisarão, para além da
conexão com a internet, estarem com seu sistema de localização (GPS) ativado.  

## 3. Requisitos Funcionais
| Código | Descrição | Prioridade |
|:---:|---|:---:|
| RF01 | O sistema deve permitir ao usuário consultar os horários de chegada dos ônibus circulares, <br> exibindo informações atualizadas sobre os próximos horários disponíveis. | **Alta** |
| RF02 | O sistema deve apresentar uma tabela completa com todos os horários do circular ao longo <br> do dia e da semana. | **Alta** |
| RF03 | O sistema deve mostrar em tempo real a localização atual do ônibus circular por meio de um <br> mapa interativo, facilitando o acompanhamento do trajeto. | **Alta** |
| RF04 | O sistema deve conter um mapa exclusivo da universidade com destaque visual para os pontos <br> de parada do circular, facilitando a identificação pelo usuário. | **Média** |
| RF05 | O sistema deve calcular e exibir o tempo estimado de chegada do ônibus circular até cada uma <br> das paradas disponíveis, com base na posição atual do veículo. | **Alta** |
| RF06 | O sistema deve atualizar automaticamente as informações em intervalos regulares, garantindo <br> precisão nos dados fornecidos aos usuários. | **Alta** |
| RF07 | O sistema deve permitir ao usuário selecionar uma parada desejada e visualizar informações <br> específicas, como previsão de chegada do próximo ônibus e lista de horários de atendimento <br> dessa parada. | **Média** |
| RF08 | O sistema deve apresentar funcionalidades e interfaces diferenciadas para usuários e motoristas. <br> Visto que, é necessário uma ambientação específica de cada perfil. | **Alta** |


