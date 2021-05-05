## Softwares utilizados:
 
- NetBeans v12.0
- Java 8
- Payara Server 5.191

Configurações necessárias no NetBeans:

## Primefaces:

- Adicionar o arquivo .jar do primeFaces-sources em tools -> libraries -> primefaces -> sources
- Adicionar o código abaixo no arquivo pom.xml

`` 
    <dependency>
        <groupId>org.primefaces</groupId>
        <artifactId>primefaces</artifactId>
        <version>5.0</version>
    </dependency>
``

## Unidade de persistência

- Foi necessário realizar a utilização do arquivo persistence.xml para se conectar ao banco de dados (feito manualmente)

Obs: como a professora conteudista utilizou outra versão do Netbeans acredito que essa configuração foi feita automaticamente quando ela gerou a entidade, sendo necessário realizar essa configuração manualmente na versão 12.0
