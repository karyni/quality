Problema:

Empresa de software que presta o serviço de um sistema integrado de gestão empresarial, banco de dados MSSQL Server e servidor de aplicações Apache Tomcat 8.5, camada de apresentação foi construída com HTML e JQuery. 
Falha no sistema causando insatisfações dos clientes, que rescindem contratos.

Evolução da empresa em 5 anos:
4 funcionários -> 45 funcionários
2 empresas -> 125 empresas

Sugestões de soluções:

Implementação de ERPs em nuvem.

Apesar das empresas utilizarem a ferramenta com o mesmo propósito, cada uma acaba tendo alguma necessidade diferente, que não se encontra no programa disposto a princípio.

Se cada uma das 125 empresas sugerir alguma mudança, por mais leve que seja, outras empresas que estavam satisfeitas com o serviço podem estranhar a mudança. 
Se cada um dos 45 funcionários efetuar uma mudança sem comunicar efetivamente outra equipe, sem realizar os testes necessários para que a interface, o servidor e todos os sistemas que em conjunto estejam em pleno funcionamento, problemas ocorreram em algum lado.

Existem 45 funcionários, podem ser dispostos em 9 equipes com 5 integrantes, cada uma possuindo um líder ou gerente a quem comunicarão suas atividades, lideres que por sua vez estarão em contato uns com os outros para que todos saibam do desenvolvimento dos projetos. 
A utilização do método Scrum é recomendada por possuir reuniões diárias sobre o progresso do projeto, mantendo todos atualizados. 

No método Scrum, as equipes são multidisciplinares, a pessoa com conhecimento de QA deve compartilhar seu conhecimento e monitorar os integrantes para que cada um seja responsável por realizar testes de garantia de qualidade com frequência e reafirmar a boa utilização do software em cada área, mantendo o cliente satisfeito. Ou seja, todos os integrantes devem ser parte do QA.
A realização destes testes de qualidade frequentes durante todo os processos de desenvolvimento é de extrema importância para que o sistema não fique atrasado, caso o QA seja feito em separado, quando os desenvolvedores acreditarem que o produto se encontra pronto, podem encontrar mais problemas e deixar o cliente insatisfeito com demoras em updates.

ERPs em nuvem:
Uma opção para acompanhar e dar suporte constante ao cliente, que por sua vez reduz os gastos já que não precisa contratar uma equipe de TI local. O sistema deve acompanhar as atualizações do mercado e também a evolução da empresa para continuar competitivo.
É imprescindível a participação do cliente na implementação do sistema, já que ele tem o conhecimento da empresa e a equipe da XY tem o conhecimento do sistema.

Softwares sugeridos:

Microsoft SQL Server 2019 (atualização do sistema já utilizado pela XY), sistema já muito utilizado na indústria tecnológica, documentação acessível, garantia em suporte e segurança. Possui ainda o recurso Power BI, que fornecem relatórios voltados a Business Intelligence.
De acordo com o site da empresa Microsoft “o SQL Server 2019 facilita o gerenciamento de um ambiente de big data. Ele oferece elementos-chave de um data lake — HDFS (Hadoop Distributed File System), Spark e ferramentas analíticas — que estão profundamente integrados com o SQL Server e com total suporte da Microsoft.“

Apache Spark (já integrado no SQL Server 2019), para o processamento de dados em larga escala, de acordo com a distribuidora o Spark é 100x mais rápido ao realizar workloads, além disso suporta as linguagens Java, Python, R e os containers de SQL.

A camada de apresentação segue padrões normais, com HTML e JQuery, para formatação dos dados, conversão de códigos e caracteres, ou seja traduzir as informações em um formato entendido pelo protocolo usado. Por questões de segurança é sugerida a aplicação de criptografia nessa camada.








