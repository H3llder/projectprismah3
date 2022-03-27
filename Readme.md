## MKI - Aprendendo a usar o prisma para o TCC

*Primeiros comandos*

| yarn init -y
| npm install prisma typescript ts-node @types/node --save-dev

*Após isso*

| yarn prisma
| yarn prisma init

-- ESTOU USANDO MYSQL, LOGO MINHAS CONFIGURAÇÕES, ESTARÃO BASEADAS NELE
Ex: DATABASE_URL="mysql://user:password@localhost:0000/db"

Após isso, criar em schema.prisma a estrura do banco;
| yarn prisma migrate dev


# Instalando Prisma Client

| yarn add @prisma/client

# Prisma Studio

| yarn prisma studio
