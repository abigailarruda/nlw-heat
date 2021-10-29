# NLW Heat

<p align="center">
  <img src="https://user-images.githubusercontent.com/26419930/139450578-2f26fda1-b130-4bad-aa61-a9f9e55c0be9.png" alt="NLW Heat"/>
</p>

## Execução

1. Clone o repositório e acesse a pasta <code>node-heat</code>

```bash
git clone https://github.com/abigailarruda/nlw-heat.git
```

2. Crie um arquivo <code>.env</code> na raiz do projeto, utilizando o exemplo a
   seguir:

```bash
GITHUB_CLIENT_SECRET=
GITHUB_CLIENT_ID=
JWT_SECRET=
```

3. Instale as dependências

```bash
yarn
```

4. Execute as migrations

```bash
yarn prisma migrate dev
```

5. Inicie o servidor

```bash
yarn dev
```

6. Acesse a pasta <code>react-heat</code> e crie um arquivo <code>.env</code> na
   raiz do projeto, utilizando o exemplo a seguir:

```bash
VITE_GITHUB_CLIENT_ID=
```

7. Instale as dependências

```bash
yarn
```

8. Execute a aplicação

```bash
yarn dev
```
