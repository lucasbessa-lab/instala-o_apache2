COMO INSTALAR O APACHE2 NA SUA MÁQUINA VIRTUAL:

1. Execute o comando para atualizar os programas:

<pre><code>sudo apt-get update</code></pre>

2. Execute o comando para instalar o apache2:
<code>sudo apt-get install apache2</code>
Clique no s para continuar.

3.Verifique o status do servidor pelo comando:
<code>/etc/init.d/apache2 status</code>
Precisa estar com o status active (running).

4.Verifique o ip da sua máquina com o comando:
<code>ip a</code>
Pesquise seu IP no navegador, irá abrir uma página do apache2.
Outra forma é pesquisando http//localhost.
