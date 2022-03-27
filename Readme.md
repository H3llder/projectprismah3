# MKI - Aprendendo a usar o prisma para o TCC

*Primeiros comandos*
```js
| yarn init -y
| npm install prisma typescript ts-node @types/node --save-dev
```

*Após isso*
```js
| yarn prisma
| yarn prisma init
```

<p style="color: #00ff00;">ESTOU USANDO MYSQL, LOGO MINHAS CONFIGURAÇÕES, ESTARÃO BASEADAS NELE</p>
<p>Ex: DATABASE_URL="mysql://user:password@localhost:0000/db"</p>

Após isso, criar em schema.prisma a estrura do banco;
```js
| yarn prisma migrate dev
```


### Instalando Prisma Client
```js
| yarn add @prisma/client
```

### Prisma Studio
```js
| yarn prisma studio
```
