# t_mentais_datasus

> Repositório contendo *datasets* com dados públicos do Brasil sobre Transtornos Mentais no Trabalho 

---

[Dicionário de dados (SINAN - AGRAVO: DRT Transtorno Mental)](https://app.wiki.saude.es.gov.br/vigilancia/microdados/dic_dados_drt_transtornosmentais_v5.pdf)
  
  ╰ Se refere aos arquivos com o padrão: "MENTBRyy.csv"

---

### Como os arquivos originais do SINAN foram obtidos (DATASUS):

1) Baixar o software FileZilla (https://download.filezilla-project.org/client/FileZilla_3.62.0_win64_sponsored2-setup.exe)

2) Abrir o Filezilla e na parte superior do software onde tem uma caixa de texto "Host:", digitar: ftp.datasus.gov.br

3) O Filezilla apresenta a tela dividida em 2 partes!

   - Na esquerda você seleciona em qual pasta irá baixar um arquivo

   - Na direita, você navega pelas pastas disponíveis no servidor do DataSus [para volta para uma pasta anterior.. você deverá clicar na 1a pasta que aparecer (..) ]

4) Os dados do SINAN estão na pasta: dissemin / publicos / SINAN / DADOS / FINAIS 

5) Os arquivos que iniciam com “MENTBRyy” contém os dados anuais sobre Transtornos Mentais no trabalho, entretanto estão em um formato especial (.DBC) que demanda o uso de outro software.
    Exemplo: MENTBR19 -> Transtornos Mentais no Trabalho no ano de 2019.

7) Para baixar, bastaria selecionar os arquivos que estão na tela da direita e clicar com o botão direito do mouse e selecionar 'Download'.

8) Para visualizar o arquivo .DBC deverá baixar antes o programa TabWin.. disponível pelo mesmo acesso descrito anterior, mas na pasta: /dissemin/publicos/TABWIN/Programa e então baixar o arquivo "Instalador-TABWIN415.zip".
que você deseja conferir.
