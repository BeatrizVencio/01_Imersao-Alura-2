# Desafios da Aula 1
## Desafio 1
**OBJETIVO:** Utilizar o Gemini para ajudar em alguma tarefa na área de trabalho (faculdade).

Solicitei a enumeração e a descrição de uma imagem enviada a mim no curso Ciência de Dados. Segue a imagem: 

![imagem data lake](https://github.com/BeatrizVencio/Imersao-Alura-2/blob/main/Aula_1/imgs/data_lake.png)

Análise do `Gemini`:  

![analise data lake](https://github.com/BeatrizVencio/Imersao-Alura-2/blob/main/Aula_1/imgs/analise_data_lake.png)

Com isso, o Gemini trouxe as seguintes informações:

1. **Armazenamento de Dados:**
   * Amazon S3: Serviço de armazenamento de objetos escalável e de alta disponibilidade oferecido pela Amazon Web Services. É frequentemente usado para armazenar grandes conjuntos de dados não estruturados.
   * Amazon RDS: Serviço de banco de dados relacional gerenciado que facilita a configuração, operação e dimensionamento de bancos de dados relacionais na nuvem.
   * Hadoop Distributed File System (HDFS): Sistema de arquivos distribuído projetado para armazenar grandes volumes de dados em clusters de computadores.
   * Apache HBase: Banco de dados NoSQL de código aberto que é executado em cima do HDFS, oferecendo acesso de baixa latência a grandes conjuntos de dados.
   * Amazon Redshift: Armazém de dados na nuvem, totalmente gerenciado, que permite analisar grandes conjuntos de dados usando consultas SQL.
   * Apache Cassandra: Banco de dados NoSQL de código aberto que oferece alta disponibilidade e escalabilidade.
   * Redis: Armazenamento de estrutura de dados em memória de código aberto que pode ser usado como banco de dados, cache e broker de mensagens.
   * Amazon DynamoDB: Banco de dados NoSQL de baixa latência e alta performance, oferecido pela Amazon Web Services.

2. **Processamento de Dados:**
   * Apache Hadoop: Framework de código aberto para processamento distribuído de grandes conjuntos de dados em clusters de computadores.
   * Apache Spark: Motor de processamento de dados de código aberto que oferece processamento em memória para análise de dados em tempo real.
   * Apache Flink: Framework de código aberto para processamento de fluxo de dados em tempo real e em lote.
   * Apache Tez: Framework de código aberto para a construção de aplicações de processamento de dados de alto desempenho em cima do Hadoop.
   * Apache Pig: Linguagem de alto nível para análise de grandes conjuntos de dados que é executada em cima do Hadoop.
   * Apache Hive: Armazém de dados que permite consultas SQL em dados armazenados no Hadoop.
   * Presto: Motor de consulta SQL distribuído de código aberto projetado para executar consultas analíticas interativas em grandes conjuntos de dados.

3. **Gerenciamento de Clusters e Recursos:**
   * Apache Mesos: Gerenciador de clusters de código aberto que abstrai recursos de CPU, memória, armazenamento e outros recursos de máquinas físicas ou virtuais.
   * Kubernetes: Plataforma de código aberto para automatizar a implantação, o dimensionamento e o gerenciamento de aplicativos em contêineres.
   * Apache ZooKeeper: Serviço de código aberto para coordenação distribuída, usado para manter informações de configuração, nomeação, fornecer sincronização distribuída e fornecer serviços de grupo.

4. **Análise de Dados e Machine Learning:**
   * Apache Mahout: Biblioteca de aprendizado de máquina escalável que implementa algoritmos de aprendizado de máquina em cima do Hadoop.
   * TensorFlow: Biblioteca de código aberto para aprendizado de máquina e inteligência artificial, desenvolvida pelo Google.
   * MXNet: Biblioteca de aprendizado profundo de código aberto que permite construir e treinar modelos de aprendizado profundo.
   * R: Linguagem de programação e ambiente de software para computação estatística e gráficos.

5. **Orquestração e Gerenciamento de Workflow:**
   * Apache Airflow: Plataforma para criação, agendamento e monitoramento programaticamente de workflows de dados.
   * Apache Oozie: Sistema de gerenciamento de workflow para gerenciar trabalhos Hadoop.
   * Livy: Interface REST para interagir com clusters Apache Spark.

6. **Outras Tecnologias:**
   * Amazon Kinesis: Plataforma para coletar, processar e analisar dados de streaming em tempo real.
   * Apache Kafka: Plataforma de streaming de código aberto para publicação, subscrição e processamento de fluxos de dados em tempo real.
   * Docker: Plataforma de código aberto para desenvolver, enviar e executar aplicativos em contêineres.
   * Apache Shiro: Framework de segurança para aplicações Java.
   * MySQL Workbench: Ferramenta visual de código aberto para administração de banco de dados MySQL.
   * Hue: Interface web de código aberto para gerenciar e interagir com o ecossistema Hadoop.


#

## Desafio 2
**OBJETIVO:** Utilizar o Gemini para analisar o histórico de navegação do Google.

Utilizando a extensão [Quick Chrome History Export](https://chromewebstore.google.com/detail/quick-chrome-history-expo/hdfpifhfphhgjipcnfnolgalplokmmge), o histórico de navegação do Google Chrome foi extraído e salvo como `.csv`.

<img alt="Google Extensao" src="https://github.com/BeatrizVencio/Imersao-Alura-2/blob/main/Aula_1/imgs/google_extensao.png" width="400" height="250"/>

Depois importei o arquivo `.csv` para o [AI Studio](https://aistudio.google.com/app/prompts/new_chat?utm_source=website&utm_medium=referral&utm_campaign=Alura&utm_content=).

#

**ANÁLISE DO HISTÓRICO DE NAVEGAÇÃO**

Através do AI Studio, o histórico coletado pela extensão foi submetido ao Gemini para análise. 

![analise do historico](https://github.com/BeatrizVencio/Imersao-Alura-2/blob/main/Aula_1/imgs/analise_historico.png)

Com isso, o Gemini forneceu 4 tipos de informações: 

1. **Principais Atividades:**
   * Estudante Universitário: As atividades do usuário sugerem que ele é um estudante universitário, possivelmente cursando disciplinas relacionadas a Ciência de Dados. O histórico mostra acessos frequentes a uma plataforma de ensino online e a um espaço do aluno, com foco em cursos como "Introdução a R para Ciência de Dados", "Fundamentos de Big Data" e "Aprendizagem Profunda (Deep Learning)".
   * Imersão em IA: Há evidências de participação ou interesse em um programa de imersão sobre Inteligência Artificial, possivelmente em parceria com o Google. O usuário acessou repositórios do GitHub relacionados ao programa e editou arquivos README.
   * Busca por Dados Abertos: O histórico demonstra uma busca ativa por dados abertos, especificamente relacionados à dengue. O usuário explorou portais governamentais e sites de ciência de dados em busca de conjuntos de dados e projetos de aprendizado de máquina sobre o tema.
   * Uso de Ferramentas de Ciência de Dados: O usuário utiliza ferramentas como Google Colab para análise de dados e Kaggle para explorar conjuntos de dados e projetos de aprendizado de máquina.
  
2. **Outras Observações:**
   * Plataforma de Desenvolvimento Colaborativo: O histórico indica familiaridade com uma plataforma de desenvolvimento colaborativo como o GitHub, incluindo a criação de repositórios, edição de arquivos README e exploração de recursos de automação.
   * Criação de Imagens: O usuário demonstrou interesse em criar imagens utilizando uma plataforma online específica, buscando tutoriais e experimentando diferentes ferramentas de criação.
   * Rede Profissional: Há indícios de que o usuário está ativo em uma rede profissional online, sugerindo preocupação com o desenvolvimento de sua carreira.

3. **Possíveis Interesses e Objetivos:**
   * Carreira em Ciência de Dados: Com base nos cursos e ferramentas utilizadas, o usuário provavelmente tem interesse em seguir uma carreira em Ciência de Dados.
   * Projeto Relacionado à Dengue: A busca por dados abertos e projetos de aprendizado de máquina sugere que o usuário pode estar trabalhando em um projeto relacionado à dengue, possivelmente como parte de seus estudos ou como iniciativa pessoal.
   * Criatividade e Design: O uso da plataforma de criação de imagens indica um interesse em expressar sua criatividade e explorar ferramentas de design.

4. **Considerações:**
   * Esta análise é baseada em um trecho específico do histórico de navegação e pode não representar completamente os interesses e objetivos do usuário.
   * É importante lembrar que o histórico de navegação é apenas um indicador de atividade e não necessariamente reflete as intenções ou pensamentos do usuário.



























