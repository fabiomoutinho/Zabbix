

##                                      Template SNMP em LLD Zabbix Para Impressora!

##### A ideia desse template e facilitar a vida em poder utilizar um template unico para as impressoras do ambiente ganhando tempo valioso ao invés de ter um template para cada host.

##### Este template foi criado sobre a versao do Zabbix Server 3.4.2rc2

### O template da suporte para as seguintes impressoras:

##### Fabricante Samsung:
##### Modelos: Samsung K-7400LX, Samsung CLX-8640, Samsung X-4220RX, Samsung M-5370LX, Samsung CLX-6260, Samsung M4510.

##### Fabricante HP:
##### Modelos: HP LaserJet 1212nf, HP LaserJet P2055dn, HP LaserJet HP3525dn, HP Officejet Pro 8610.

##### Fabricante Canon:
##### Modelos: Canon IR C1335.

##### Fabricante Kyocera:
##### Modelos: Ecosys M2035DN.

##### Fabricante Sharp:
##### Modelos: MX-2010U.

##### Fabricante Xerox:
##### Modelos: Xerox WorkCentre Pro 123, Xerox WorkCentre 5335, Xerox - Phaser 7500.

##### Fabricante Bizhub:
##### Modelos: KONICA MINOLTA - Model Name:bizhub 283, KONICA MINOLTA - Model Name:bizhub 363, KONICA MINOLTA - Name:bizhub 367, KONICA MINOLTA 215.

##### Fabricante Brother:
##### Modelos: Brother - MFC 9980DW.

##### Fabricante Ricoh:
##### Modelos: RICOH - SP 4510SF, RICOH - Aficio SP 3510DN, RICOH - Aficio MP C3002.

##### O que acompanha o template!

##
##### 1) Dados Coletados:

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/dadoscoletados.PNG)

##
##### 2) Em LLD:

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/dadoscoletadosemlld.PNG)

##
##### 3) Em Graficos:

##
* 01- Disponibilidade

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/disponibilidade.PNG)

##
* 02- Latencia

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/latencia.PNG)

##
* 03- Perda de Pacotes

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/perdadepacote.PNG)

##
* 04- Tempo Ligado

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/tempoligado.PNG)

##
* 05 Paginas Impressas

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/paginasimpressastotal.PNG)

##
* 06 Paginas Por Dia

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/paginasimpressasdia.PNG)

##
* 07 Paginas Por Semana

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/paginasimpressassemana.PNG)

##
* 08 Paginas Por Mes

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/paginasimpressasmes.PNG)

##
* 09 Tempo de Vida do Fusor

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/tempodevidafusor.PNG)

##
* 10 Nivel de Papel na Bandeja Tray 1

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/nivelpapeltray1.PNG)

##
* 11 Nivel de Papel na bandeja Tray 2

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/nivelpapeltray2.PNG)

##
* 12 Nivel de Papel na bandeja MP Tray

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/nivelpapelmptray.PNG)

##
* 13 Nivel do Black Toner

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/tonnerblack.PNG)

##
* 14 Nivel do Cyan 

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/tonnercyan.PNG)

##
* 15 Nivel do Magenta

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/tonnermagenta.PNG)

##
* 16 Nivel do Yellow

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.4/src/img/Printes/tonneryellow.PNG)


## Configurações Adicionais!

##### 1) Vamos acessar o arquivo de configuração abaixo e inserir a unidade de medida para informar as paginas impressas com os valores reais.

##### com o comando vim vamos editar o arquivo.
##### # vim /usr/share/zabbix/include/func.inc.php

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.2/src/img/impressora-lld-dados-editar-frontend.PNG)


##### 2) Vamos seguir ate a linha 618 e inserir na blackList a unidade de medida para postar as informações desejadas.

![Alt Text](https://github.com/MagnoMonteCerqueira/Zabbix/blob/master/Zabbix_3.2/src/img/impressora-lld-dados-editar-frontend-unidade.PNG)


##
## Contatos:


* Telegram: @Magnopeem
* Skype: magnopeem_rj@hotmail.com
* E-mail: magnopeem@gmail.com
* Linkedin: https://br.linkedin.com/in/magno-monte-cerqueira-976b1587






