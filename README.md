#  ๐๐ PAINEL SSH WEB ๐๐

โ  <b>SISTEMA SUPORTADO:</b>
</br>

๐ <b>(UBUNTU 18)</b>

```
apt install wget -y; bash <(wget -qO- https://raw.githubusercontent.com/Mcassador/SSH-WEB/ubuinst.sh)
```
</br>

# ๐๐ CHAVE DE INSTALAรรO! ๐๐
```
*-*
```

# ๐๐ SINCRONIZAR NA VPS SSH! ๐๐
```
apt install wget -y; bash <(wget -qO- https://raw.githubusercontent.com/Mcassador/SSH-WEB/sincpainel.sh)
```

ALTERAR PORTA DO APACHE2 DE 80 PRA 81

sed -i 's,Listen 80,Listen 81,g' /etc/apache2/ports.conf

REINICIAR APACHE2

sudo service apache2 restart


# ๐๐ ATUALIZAรรES: ๐๐
```
1- Comando pweb
(Funciona via terminal SSH)
(Com bot telegram)

2- Painel Conecta4G 
(Usuรกrio/Senha: admin/admin)

3- Loja de APPS 
(Link na tela de login/Revenda e Login/Admin)
(Troca de cor da Top-Bar e icones nos Textos)

4- Background รrea Revenda e รrea Admin
(Para alterar as imagens, bastar ir em persobalizar no menu lateral do admin e fazer o upload das imagens)

5- Texto Flutuante na Tela Login/Revenda
(๐ฃ NOVIDADES AQUI !!!) Para editar, basta ir em /var/www/html/index.php (linha 86)

6- Pรกgina de Termos de Uso editada
(foi adicionado uma imagem no topo)
(cor do background trocada)

7- Todos os nomes GESTOR-SSH foi trocado por EMPRESA
(quando alterar o NOME DA LOGO no painel pweb, Todos os texto EMPRESA serรก trocado tambรฉm.)
```