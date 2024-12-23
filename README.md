### DashBoard Microsoft AdventureWorks - Power BI | Análise de dados (Em desenvolvimento)

Link de acesso ao pbix publicado:

https://app.powerbi.com/view?r=eyJrIjoiMmE1YzIzMWMtMzFkMS00OWQ2LWJhZGEtNzAxZDYwY2E3NjJjIiwidCI6ImI1NTBlNzA3LTEwY2MtNDc2ZC05NDExLWJkOGM5ZGU3ZWNjNCJ9

### Objetivo 

A Microsoft disponibiliza para seus usuários uma vasta gama de bancos de dados, com grandes volumes de informações e cobrindo uma variedade de segmentos.
Com o intuito de explorar novas funcionalidades do Power BI, este relatório foi desenvolvido a fim de apresentar métricas do banco de dados AdventureWorks, referente a vendas, faturamento e clientes.
Essas informações são de uma empresa no setor de varejo que atua em todos os continentes do planeta. 

### Detalhes das métricas utilizadas e resumo dos resultados

Dentro do projeto, implementei um novo tipo de campo no visual nativo de "card", visando aprimorar a experiência de análise de dados, graças há uma atualização do Power BI.

![image](https://github.com/user-attachments/assets/36af5e70-e90f-46d4-be07-2f606ca9fa17)

Esse visual é riquíssimo em detalhes e não precisa de um usuário expertise na ferramenta. 
O indicador corresponde é a Receita total, que apresentou uma crescente em relação ao último ano.

Além disso, métricas temporais foram desenvolvidas. 
Ao longo dos meses é possível comparar a receita com o percentual do lucro, que se manteve estável ao longo de ano selecionado.

![image](https://github.com/user-attachments/assets/f1573ebe-c97a-4cba-b91a-7c1a6a5870d6)

Análises sobre a quantidade vendida também é de suma importância no segmento de varejo.

![image](https://github.com/user-attachments/assets/860b48ed-a1d3-4348-bb0a-78dd27e7db70)

Como se trata de uma empresa multinacional, que atua em todo o mundo, é importante ter a visão analítica dos dados nesses locais. 
O que é facilitado implementando um parâmetro. 

![image](https://github.com/user-attachments/assets/08b8885d-5b7b-4605-8b90-3336d12c00d7)

### Ferramentas e Metodologia

 - Ferramentas Utilizadas: Power BI e SQL.

 - Conexão de Dados: SQL SERVER.

 - Processo ETL: Criado todo no SQL, por meio de uma View.

### Características do Painel

O projeto inclui um painel interativo a critério do usuário, com os seguintes recursos:

 - Botões de Navegação: Guias intuitivas, como "Aba Clientes" e "Limpar Filtros", para facilitar a usabilidade.

 - Segmentações de Data: Permite filtrar os dados por períodos específicos (anos), garantindo flexibilidade nas análises.

 - Indicadores Dinâmicos:  Parâmetro implementado. 

### Como Reproduzir o Projeto

 - O link no início do README contém a publicação do BI de forma pública.

 - Baixar o arquivo .pbix, dessa forma, tem acesso a todo o projeto, como: bases, cálculos, imagens, modelagem e ícones. (É necessário ter o Power BI Desktop instalado)

 -  Baixar a View .sql
   
 -  Necessário baixar o banco de dados fornecido pela Microsoft para editar e criar novas consultas: https://learn.microsoft.com/pt-br/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms











