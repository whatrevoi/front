# SACMAIS Frontend

>- Passo a passo de como subir a aplicação do frontend.

>- Cada cliente terá uma configuração no railway, vercel e supabase.

---

## Plataformas utilizadas:

- [Vercel][vercel]
- [Railway][railway]
- [Supabase][supabase]

---

## Iniciando para um novo cliente

### 1. Criar uma nova organização no github

É preciso criar uma nova organização no github para que as plataformas realizem o deploy da aplicação e tudo fique bem separado. Uma vez que a organização foi criada, é nela que estrá presente o backend e o frontend.

<img src="./.github/images/1.png" />
<img src="./.github/images/2.png" />

### 2. Criar o repositório do frontend usando o repositório template

Ao usar o repositório template, o mesmo já virá tudo configurado.

<img src="./.github/images/3.png" />
<img src="./.github/images/4.png" />

### 3. Criar o projeto na Vercel

É necessário criaro projeto separado na vercel.

<img src="./.github/images/5.png" />

Selecione a organização e o repositório do frontend criado

<img src="./.github/images/6.png" />

Defina o nome do projeto

<img src="./.github/images/7.png" />

Configure o build

<img src="./.github/images/8.png" />

Defina a variavel de ambiente e depois só realizar o deploy

<img src="./.github/images/9.png" />

A própria vercel irá gerar um link, mas caso queira ter o próprio dominio, só fazer a configuração:

<img src="./.github/images/10.png" />

[vercel]: https://vercel.com
[railway]: https://railway.app
[supabase]: https://app.supabase.com
