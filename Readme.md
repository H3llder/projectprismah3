# MKI - Aprendendo a usar o prisma para o TCC

*Primeiros comandos*
<div style="background-color: #ccc; padding: 20px;">

<p>| yarn init -y</p>
<p>| npm install prisma typescript ts-node @types/node --save-dev</p>

</div>

*Após isso*
<p>| yarn prisma</p>
<p>| yarn prisma init</p>


-- ESTOU USANDO MYSQL, LOGO MINHAS CONFIGURAÇÕES, ESTARÃO BASEADAS NELE
Ex: DATABASE_URL="mysql://user:password@localhost:0000/db"

Após isso, criar em schema.prisma a estrura do banco;
<p>| yarn prisma migrate dev</p>


### Instalando Prisma Client
<p>| yarn add @prisma/client</p>

### Prisma Studio
<p>| yarn prisma studio</p>
