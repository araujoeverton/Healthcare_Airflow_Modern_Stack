<img align="right" src="https://raw.githubusercontent.com/araujoeverton/Healthcare_Airflow_Modern_Stack/dev-dbt/assets/healthcare-airflow-modern-stack-banner.jpg" width="1080"/> ...



<img align="right" src="https://raw.githubusercontent.com/araujoeverton/Healthcare_Airflow_Modern_Stack/7870e8086b52deae4ca9562f0c17fb707ab8d7ad/assets/dbt-signature_tm.svg" width="200"/>

# Autorização de Uso

### 1. Salve uma cópia e utilize o material deste repositório para estudo!
<a href="https://github.com//araujoeverton/Healthcare_Airflow_Modern_Stack/fork">
    <img alt="Folk" title="Fork Button" src="https://shields.io/badge/-DAR%20FORK-red.svg?&style=for-the-badge&logo=github&logoColor=white"/></a>


## Introdução

Segundo o Centro de Controle e Prevenção de Doenças (CDC), problemas cardíacos representam uma das principais causas de óbito entre várias etnias nos Estados Unidos, incluindo afro-americanos, índios americanos, nativos do Alasca e caucasianos. Quase metade da população americana (47%) apresenta pelo menos um dos três fatores de risco significativos para o desenvolvimento de doenças cardíacas, que são hipertensão arterial, alto nível de colesterol e hábito de fumar. Adicionalmente, diabetes, obesidade (indicada por um Índice de Massa Corporal elevado), insuficiência de exercício físico, ou o consumo abusivo de álcool são também considerados fatores cruciais.

### Objetivo

Através de uma Stack Moderna de Engenharia de Dados, fornecer dados que permitem a aplicação de métodos de aprendizagem de máquina para detectar “padrões” nos dados que podem prever a condição de um paciente.

### Ferramentas Utilizadas

Neste projeto serão utilizados o Mongodb, Airbyte, Apache Airflow, Dbt e Snowflake.<br><br>
<b>Mongodb:</b> Por ser baseado em documentos e sua capacidade de indexação eficiente, o que pode ser especialmente útil para aplicações que lidam com grandes volumes de dados.
<br><br>
<b>Airbyte:</b> O Airbyte possui um scheduler integrado e utiliza o [Temporal](https://airbyte.com/blog/scale-workflow-orchestration-with-temporal) para orquestrar tarefas e garantir confiabilidade em escala. O Airbyte aproveita o [dbt](https://www.youtube.com/watch?v=saXwh6SpeHA) para normalizar dados extraídos e pode acionar transformações personalizadas em SQL e dbt. Você também pode orquestrar sincronizações do Airbyte com o [Airflow](https://docs.airbyte.com/operator-guides/using-the-airflow-airbyte-operator).
<br><br>
<b>Apache Airflow:</b> São diversas as vantagens de se usar o Airflow, dentre elas está sua UI que nos possibilita monitoramento e logs para identificar eventuais problemas, flexibilidade ao poder ser utilizado em diversos serviços, facilidade de criar e alterar fluxos simples e complexos de dados ( Dags ), entre outros.
<br><br>
<b>Dbt:</b> Simplifica consideravelmente a modelagem de dados ao empregar o SQL como sua linguagem principal, além de ter uma fácil implementação e controle de versionamento.
<br><br>
<b>Snowflake:</b> Utiliza instâncias virtuais para as necessidades de computação e um serviço para armazenamento persistente de dados. Possui uma alta escalabilidade e a execução das consultas é realizada na camada de processamento. O Snowflake processa as consultas utilizando «warehouses virtuais». Cada warehouse virtual é um cluster de computação MPP composto de múltiplos nós de computação alocados pelo Snowflake a partir de um provedor de nuvem.

Link da base de dados: [Personal-Key-Indicators-Of-Heart-Disease](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease)







### Repositório destinado à estudos e documentação do projeto de formação.


<div align="left">
  <p>
      <img src="https://img.shields.io/github/languages/count/alexklenio/DIO-dotnet-developer"/>
      <img src="https://img.shields.io/github/repo-size/alexklenio/DIO-dotnet-developer"/>
      <img src="https://img.shields.io/github/last-commit/alexklenio/DIO-dotnet-developer"/>
      <img src="https://img.shields.io/github/issues/alexklenio/DIO-dotnet-developer"/>
  </p> 
</div>


