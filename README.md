# To-do List

Aplicação de lista de tarefas com interface em Next.js e API em NestJS. Cada parte fica em uma pasta própria e sobe em um processo separado.

## Stack

Versões instaladas nos `package-lock.json`.

### Front-end (`front-end`)

| Tecnologia | Versão |
| --- | --- |
| Next.js | 16.4.6 |
| React | 19.3.0 |
| React DOM | 19.3.0 |
| TypeScript | 5.9.3 |
| Tailwind CSS | 4.3.3 |
| ESLint | 9.39.5 |

### Back-end (`back-end`)

| Tecnologia | Versão |
| --- | --- |
| NestJS (`@nestjs/core`, `@nestjs/common`, `@nestjs/platform-express`) | 12.5.1 |
| Nest CLI | 12.0.13 |
| TypeScript | 6.0.3 |
| RxJS | 7.8.2 |
| Vitest | 4.1.12 |

## O que instalar

- [Node.js](https://nodejs.org/) **22.22.3 ou superior** na linha 22, ou **24.15.0 ou superior** na linha 24. O Next.js aceita Node `>= 20.9.0`; as ferramentas do NestJS deste projeto pedem `^22.22.3`, `^24.15.0` ou `>= 26`.
- **npm**, que já vem com o Node.js. Não é necessário instalar o Next.js nem o NestJS de forma global: as dependências ficam em cada pasta depois do `npm install`.

## Como rodar

Abra dois terminais, um para cada pasta. O front-end sobe na porta **3000** e o back-end na porta **4000**.

### Front-end

```bash
cd front-end
npm install
npm run dev
```

A aplicação fica em [http://localhost:3000](http://localhost:3000).

### Back-end

```bash
cd back-end
npm install
npm run start:dev
```

A API fica em [http://localhost:4000](http://localhost:4000). `start:dev` reinicia o servidor quando os arquivos mudam.

Para subir o back-end sem o modo de observação de arquivos:

```bash
npm run start
```
