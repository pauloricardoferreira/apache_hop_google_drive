## Bem-vindo

Se você está tentando acessar o Google Driver com as versões mais recentes do Apache Hop, já deve ter percebido que ocorre um erro causado por uma diferença de versão.

Em testes realizados, utilizei os driver da versão 0.70 do Apache Hop na versão 2.3.

## Procedimentos

vá até a pasta de de instalação Apache Hop ../plugins/tech, remoeie a pasta google para google_old e adicione o conteúdo desse repositório no lugar.

Após adicionar os arquivos, renomeie o arquivo hop-plugins-tech-google-0.70-SNAPSHOT.jar para  hop-plugins-tech-google-{versao_do_apache_hop}.jar, ou o mesmo nome do plugins original.

### Não se esqueça de fazer os procedimentos para obter o arquivo de credênciais obtivos na console do google, e realizar os procedimentos na documentação do Apache Hop.

Após esses passos deve ser possivel utilizar o Google Drive.

Não testes se interefere em algo do BigQuery, favor testarem e caso queiram postar algo neste repositório abra uma issue