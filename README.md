# Conteúdo navegável de eqgrp-auction-file.tar.xz
- Arquivo original: https://mega.nz/#!zEAU1AQL!oWJ63n-D6lCuCQ4AY0Cv_405hX8kn7MEsa1iLH5UjKU
- Senha: `CrDj"(;Va.*NdlnzB9M?@K2)#>deB7mN` (conforme divulgado pelos ShadowBrokers, [fonte](https://medium.com/@shadowbrokerss/dont-forget-your-base-867d304a94b1))
- Este resumo é fornecido pela comunidade: reclamações/créditos para `jvoisin` @ `dustri.org` e [@x0rz](https://www.twitter.com/x0rz)

⚠️ Alguns binários podem ser detectados por você Antivírus

Os arquivos Tar aninhados foram descompactados na pasta [archive_files](/archive_files).

- windows: contains Windows exploits, implants and payloads
- swift: contains operational notes from banking attacks
- oddjob: docs related to the ODDJOB backdoor

# Conteúdo
# Desconhecido
- **JACKLADDER**
- **DAMPCROWD**
- **ELDESTMYDLE**
- **SUAVEEYEFUL**
- **WATCHER**
- **YELLOWSPIRIT**

# Diversos
- **DITTLELIGHT (HIDELIGHT)** exibe a janela **NOPEN** para executar scripts de banco de dados Oracle Unix
- **DUL** compactador de shellcode
- **egg_timer** retardador de execução (equivalente a `at`)
- **ewok** [snmpwalk](http://www.net-snmp.org/docs/man/snmpwalk.html)-like?
- **gr** Gerenciador de crontabs da web? wtf. A NSA é do Webscale, cara?
- **jackladderhelper** vinculador de porta simples
- **magicjack** Implementação de [DES](https://en.wikipedia.org/wiki/Data_Encryption_Standard) em Perl
- **PORKSERVER** servidor baseado em inetd para o implante **PORK**
- **ri** equivalente a `rpcinfo`
- **uX_local** servidor Micro X, provavelmente para gerenciamento remoto
- **ITIME** Data/Hora da última alteração em um arquivo de um sistema de arquivos Unix

# Execução Remota de Código
## Solaris
- **CATFLAP** Solaris 7/8/9 (SPARC e Intel) RCE (para [__LOT__]( https://twitter.com/hackerfantastic/status/850799265723056128 ) versões)
- **EASYSTREET**/**CMSEX** e **cmsd** raiz remota `rpc.cmsd` do Solaris
- **EBBISLAND**/**ELVISCICADA**/**snmpXdmid** e **frown**: `CVE-2001-0236`, Solaris 2.6-2.9 - Estouro de Buffer snmpXdmid
- **sneer**: *mibissa* (Sun snmpd) RCE, com símbolos *DWARF* :D
- **dtspcdx_sparc** dtspcd RCE para SunOS 5. -5.8. Que exploit inútil!
- **TOOLTALK** DEC, IRIX ou Sol2.6 ou anterior Tooltalk estouro de buffer RCE
- **VIOLENTSPIRIT** RCE para daemon ttsession em CDE no Solaris 2.6-2.9 no SPARC e x86
- **EBBISLAND** RCE Solaris 2.6 -> 2.10 Injeta shellcode em serviço rpc vulnerável

## Servidor Netscape
- **xp_ns-httpd** RCE do Servidor NetScape
- **nsent** RCE para o servidor NetScape Enterprise 4.1 para Solaris
- **eggbasket** outro RCE do NetScape Enterprise, desta vez versão `3.5`, provavelmente apenas SPARC

## Servidores FTP
- **EE** proftpd 1.2.8 RCE, para RHL 7.3+/Linux, `CVE-2011-4130`? Outro motivo para não usar o proftpd
- **wuftpd** provavelmente `CVE-2001-0550`

## Web
- **ESMARKCONANT** explora a execução remota de comandos do phpBB (<[2.0.11](https://www.phpbb.com/community/viewtopic.php?t=240636)) `CVE-2004-1315`
- **ELIDESKEW** Público Vulnerabilidade conhecida no [SquirrelMail](https://squirrelmail.org/) versões 1.4.0 - 1.4.7
- **ELITEHAMMER** Executa no RedFlag Webmail 4, retornando o usuário `nobody`
- **ENVISIONCOLLISION** RCE para phpBB (derivado)
- **EPICHERO** RCE para Avaya Media Server
- **COTTONAXE** RCE para recuperar log e informações no LiteSpeed ​​Web Server

## Diversos
- **calserver** spooler RPC baseado em RCE
- **EARLYSHOVEL** RCE RHL7 usando sendmail ` CVE-2003-0681 ` ` CVE-2003-0694 `
- **ECHOWRECKER**/**sambal**: samba 2.2 e 3.0.2a - 3.0.12-5 RCE (com símbolos *DWARF*), para FreeBSD, OpenBSD 3.1, OpenBSD 3.2 (com uma pilha não executável, zomg) e Linux. Provavelmente `CVE-2003-0201`. Há também uma versão para Solaris.
- **ELECTRICSLIDE** RCE (heap-overflow) no [Squid](http://www.squid-cache.org/), com um vetor com aparência chinesa.
- **EMBERSNOUT** um exploit remoto contra o httpd-2.0.40-21 do Red Hat 9.0.
- **ENGAGENAUGHTY**/**apache-ssl-linux** Apache2 mod-ssl RCE (2008), SSLv2.
- **ENTERSEED** Postfix RCE, para 2.0.8 - 2.1.5.
- **ERRGENTLE**/**xp-exim-3-remote-linux** Exim remoto root, provavelmente. `CVE-2001-0690`, Exim 3.22 - 3.35
- **EXPOSITTRAG** ​​exploit pcnfsd versão 2.x
- **extinctspinash**: RCE com `Chili!Soft ASP`? E *Cobalt RaQ* também?
- **KWIKEMART** (binário **km**) RCE para preenchimento SSH1 crc32 (https://packetstormsecurity.com/files/24347/ssh1.crc32.txt.html)
- **prout** (ab)uso do programa RPC `pcnfs` (somente versão 2) (1999)
- **slugger**: RCE de várias impressoras, parece com `CVE-1999-0078`
- **statdx** exploit de root remoto rpc.statd do Red Hat Linux 6.0/6.1/6.2 (IA32)
- **telex** Telnetd RCE para RHL? `CVE-1999-0192`?
- **toffeehammer** RCE para `cgiecho`, parte de `cgimail`, explora fprintf
- **VS-VIOLET** Solaris 2.6 - 2.9, algo relacionado ao [XDMCP](https://en.wikipedia.org/wiki/X_display_manager_(program_type)#X_Display_Manager_Control_Protocol)
- **SKIMCOUNTRY** Rouba dados de registro de celular
- **SLYHERETIC_CHECKS** Verifica se um alvo está pronto para **SLYHERETIC** (não incluído)
- **EMPTYBOWL** RCE para MailCenter Gateway (mcgate) - um aplicativo que acompanha o servidor de e-mail do Asia Info Message Center; estouro de buffer permite que uma string passada para a chamada popen() seja controlada por um invasor; execução de comando arbitrário que funciona apenas para a versão AIMC 2.9.5.1
- **CURSEHAPPY** Analisador de CDR (Registros de Detalhes de Chamadas) (siemens, alcatel,
