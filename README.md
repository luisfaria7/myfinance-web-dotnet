🧮 MyFinance-Web-DotNet

📌 MyFinance é um projeto do Curso de Pós-Graduação em Engenharia de Software da PUC-MG.

📖 Sobre o Projeto
O "MyFinance Web" é um sistema para controle de finanças pessoais, desenvolvido como uma aplicação web baseada no padrão MVC (Model-View-Controller) com ASP.NET Core na versão .NET 6.0.. O banco de dados utilizado será o SQL Server e o repositório do projeto será gerenciado via GitHub, permitindo o controle de versões e acompanhamento das alterações realizadas.

Durante o desenvolvimento, abordaremos aspectos como questões arquiteturais, técnicas de manutenção e refatoração de código, além de práticas de testes e implantação. Mais detalhes sobre a disciplina serão fornecidos no módulo inicial do curso.

🚀 Tecnologias Utilizadas
✔ C# ✔ .NET Core ✔ ASP.NET MVC ✔ Entity Framework Core ✔ SQL Server ✔ Bootstrap (Para Interfaces)

📂 Estrutura do Projeto
A estrutura básica do projeto segue o padrão MVC:

MyFinance-Web-DotNet/
├── myfinance-web-dotnet/           # Aplicação Web principal (MVC)
├── myfinance-web-dotnet-service/   # Camada de serviços
├── myfinance-web-dotnet-domain/    # Camada de domínio
├── myfinance-web-dotnet-infra/     # Infraestrutura e acesso a dados

🚀 Como Construir e Executar
Requisitos
🔹.NET SDK instalado 🔹Editor de código, como Visual Studio

Clonar o repositório
git clone https://github.com/seu-usuario/MyFinance-Web-DotNet.git
cd myfinance-web-dotnet/

Construção do Projeto
dotnet build

Se a construção for bem-sucedida, o executável será gerado:
bin/Debug/net9.0/myfinance-web-dotnet.dll.

Executando a Aplicação
Comando que deve ser utilizado:

dotnet run
A aplicação estará diponível:

Now listening on: http://localhost:5240
E para encerrar sua execução, pressione Ctrl+C.

🔍 Descrição & Proposta
Vamos criar uma aplicação web para que famílias possam registrar suas receitas e despesas para análise de seus gastos e consequentemente um melhor planjeamento financeiro. Esta aplicação deve permitir que o usuário monte uma espécie de Plano de Contas para categorizar todas as Transações realizadas. É importante que se tenha também relatórios de despesas por período, permitindo uma análise detalhada das finanças.

####🔹Requisitos Funcionais e Não Funcionais

RF001 - Plano de Contas: O sistema deve permitir o cadastro de Plano de Contas para categorização das Receitas e Despesas previamente estabelecidas. Exemplo:

![image](https://github.com/user-attachments/assets/300820e5-9863-4ad9-8a95-bf86895407a2)



RF002 - Registro de Transações: O sistema deve permitir o registro de Transações Financeiras de Receitas e Despesas indicando um item do Plano de Contas. Exemplo:
![image](https://github.com/user-attachments/assets/a32d778f-a289-4552-a9fe-6239f907be97)


RF003 - Relatório de Transações por Período: O usuário precisa de um relatório em HTML, representando um demonstrativo das transações por tipo (Receita ou Despesa) e por período de datas.

RF004 - Gráfico de Receitas vs Despesas por Período: O usuário precisa de um relatório do tipo gráfico no fomato pizza e que demonstre o total de receitas e despesas por período de datas.

RNF005 - Suporte a Plataformas: O sistema deve ser desenvolvido para plataformas web com design responsivo para renderização em telas de Smartphones e Tablets.

RNF006 - Linguagens de Implementação: O sistema deve ser desenvolvido utilizando o Microsoft ASP.NET MVC com Banco de Dados SQL-SERVER

🏛️ Modelagem Arquitetural
![image](https://github.com/user-attachments/assets/21368300-df81-4025-86dd-bba4f13f1f08)

![image](https://github.com/user-attachments/assets/78a9e1e6-9a37-44c7-b173-7eb1a0456e6e)



📝 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
