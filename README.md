# Cesarcyf
BruteForce em cifras de César<br>
Dev by: VandalVNL<br>
Linguagem: Shell Script<br>
<br>
<b>Não há dependências para usar este programa.</b><br>
<br>
Cesarcyf é um script para testar todas as possíveis combinações em uma Cifra de César.<br>
Sendo em Bash Script, é de uso rápido, evitando o uso de ferramentas online<br>

<b>Este programa cria arquivos em seu diretório "/tmp"</b><br>
Entradas do cesarcyf
<ul>
  <li>Este script aceita caracteres especiais</li>
  <li>Strings informadas com acento, porém perderam seu acento após a cifragem/decifragem</li>
  <li>Seu $1 deve ser a string a ser analisada</li>
  <li>Seu $2 deve ser o número de passos da cifra, caso não saiba use: -a || --all</li>
 </ul>
<blockquote>
  ./cesarcyf "Olssv Mypluk" -19<br>
  $ [nn] > 	palavra<br>
  $ [19] >	Hello Friend<br>
</blockquote>

<blockquote>
  ./cesarcyf "Hello Hacker" -a<br>
  $ [nn] > 	palavra<br>
  $ [01] >	Ifmmp Ibdlfs<br>
  $ [02] >	Jgnnq Jcemgt<br>
  $ [03] >	Khoor Kdfnhu<br>
  $ [04] >	Lipps Legoiv<br>
  $ [05] >	Mjqqt Mfhpjw<br>
  $ [06] >	Nkrru Ngiqkx<br>
  $ [07] >	Olssv Ohjrly<br>
  $ [08] >	Pmttw Piksmz<br>
  $ [09] >	Qnuux Qjltna<br>
  $ [10] >	Rovvy Rkmuob<br>
  $ [11] >	Spwwz Slnvpc<br>
  $ [12] >	Tqxxa Tmowqd<br>
  $ [13] >	Uryyb Unpxre<br>
  $ [14] >	Vszzc Voqysf<br>
  $ [15] >	Wtaad Wprztg<br>
  $ [16] >	Xubbe Xqsauh<br>
  $ [17] >	Yvccf Yrtbvi<br>
  $ [18] >	Zwddg Zsucwj<br>
  $ [19] >	Axeeh Atvdxk<br>
  $ [20] >	Byffi Buweyl<br>
  $ [21] >	Czggj Cvxfzm<br>
  $ [22] >	Dahhk Dwygan<br>
  $ [23] >	Ebiil Exzhbo<br>
  $ [24] >	Fcjjm Fyaicp<br>
  $ [25] >	Gdkkn Gzbjdq<br>
</blockquote>
