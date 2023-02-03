<h1 align="center"> configuração </h1>

![pngwing com (1)](https://user-images.githubusercontent.com/101403126/216649846-916befce-0dc3-4519-9319-6ad7a25583e0.png)

<h1 align="center"> como fazer instalação </h1>

#### Lançamentos de software pfSense e FreeBSD: https://docs.netgate.com/pfsense/en/latest/releases/versions.html#x

#### Atualização pfSense 2.6.0: https://docs.netgate.com/pfsense/en/latest/releases/22-01_2-6-0.html

#### Versão anterior do pfSense 2.5.2: https://docs.netgate.com/pfsense/en/latest/releases/2-5-2.html

#### Versão anterior do pfSense 2.5.1: https://docs.netgate.com/pfsense/en/latest/releases/21-02-2_2-5-1.html

#### pfSense Base Release 2.5.0: https://docs.netgate.com/pfsense/en/latest/releases/2-5-0.html

<h1 align="center"> Hardware mínimo </h1>

* #### Hardware mínimo pfSense: https://docs.netgate.com/pfsense/en/latest/hardware/minimum-requirements.html

* #### Seleção de hardware pfSense: https://docs.netgate.com/pfsense/en/latest/hardware/selection.html

* #### Diretrizes de dimensionamento de hardware pfSense: https://docs.netgate.com/pfsense/en/latest/hardware/size.html

* #### Sistema de arquivos UFS e particionamento: https://docs.netgate.com/pfsense/en/latest/install/install-ufs.html

* #### Sistema de arquivos ZFS e partições: https://docs.netgate.com/pfsense/en/latest/install/install-zfs.html
 
<h1 align="center"> Instale o pfSense </h1>

 1. VM pfSense: Iniciar
 2. Selecione o disco rígido de inicialização
Selecione o arquivo de disco óptico virtual
3. Seletor de disco óptico
Adicionar
Selecione o arquivo de disco óptico virtual: pfSense-CE-2.6.0-RELEASE-amd64.iso
<Abrir>
  4. Não conectado
Selecione: pfSense-CE-2.6.0-RELEASE-amd64.iso
<Selecione>
Iniciar
  
  #
  01. Aviso de direitos autorais e distribuição:
Aceitar - <Enter>
02. Bem-vindo ao pfSense!
Instalar (Instalar pfSense) - <Enter>
03. Seleção do mapa-chave
Brasileiro (teclas acentuadas) - <Enter>
Continue com o mapa de teclado br.kdb - <Enter>
04. Divisão
Auto (ZFS) Root-on-ZFS guiado - <Enter>
04.1 Opções de configuração:
>>> Instalar (continuar a instalação) - <Enter>
Tipo T/Discos: faixa: 0 discos
- Digitalize o dispositivo novamente*
-Informações do disco*
N Nome do pool pfsense
4 Forçar setores 4K? SIM
E a criptografia de disco? EM
Esquema de partição P GPT (BIOS)
Com Troca Tamanho 1g
Substituir o espelho M? EM
W Criptografar Swap? EM
04.2 Selecione o tipo de dispositivo virtual:
Stripe Stripe - Sem Redundância <Enter>
04.3 Seleção do disco rígido
[*] ada0 VBOX HARDDISK - <Barra de espaço> - <Enter>
04.4 Última chance! - <Sim> - <Entre>
05. Configuração manual:
<Não> - <Entrar>
06. Acabamento:
<Reiniciar> - <Enter>
