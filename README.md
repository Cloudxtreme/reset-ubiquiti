reset-ubiquiti
==============

Codigo para resetar radio ubiquiti/Via terminal

//É necessario ter em mãos o usuario e senha de acesso do radio, caso não resetar manualmente atraves do botão reset

1° Verificar o gateway na sua placa de rede //esse é o endereço do radio ubiquiti
2° Abrir aplicativo ssh e digitar o ip //exemplo: 10.1.1.105
3° Inserir usuario e senha //usuario e senha de acesso do radio (defaul user: ubnt pass: ubnt)
4° cfgmtd -f /user/etc/system.cfg -w && reboot //digite o comando e pressione enter
5° Apos o passo 4° o radio ira reiniciar e voltando as configurações default
6° Dependo do sistema é necessario setar ip manual pois a cfg montada possui o DHCP desativado e em modo bridge
7° IP padrão 192.168.1.20 //setar 192.168.1.100 para ter acesso
8° O Radio voltou a configuração padrão e agora é só configurar conforme sua necessidade

Caso não consiga realizar o procedimento me comunique para que eu possa oferecer um suporte!
