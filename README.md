# SpotCodeV2

## Preparando seu ambiente
Para conseguir executar com perfeição cada passo dado nesta série você precisa de alguns softwares instalados na sua máquina, eu recomendo que você siga este tutorial completo do [GoRails](https://gorails.com/setup) para realizar a instalação deles.
1. Escolha seu sistema operacional
2. Instale as seguintes dependências apresentadas lá:

**Ruby**

**Ruby On Rails**

**Git**

**NodeJs**

**Yarn**

Obs: Não é necessário instalar o PostgreSQL nem o MySQL

Obs2: Caso você tenha algum problema por não possuir o SQLite3 basta instalar [aqui](https://www.servermania.com/kb/articles/install-sqlite)

## Criando o Projeto
**1. Instale a versão 6 do Rails:**

```gem install rails -v '6.0.2.1'```

**2. Crie o app:**

```rails _6.0.2.1_ new spotcode```

**3. Crie o controller Home:**

```rails g controller home index```

**4. (_config/routes.rb_) com o seguinte conteúdo:**
```
Rails.application.routes.draw do
root to: "home#index"
end
```

**5. Agora vamos iniciar o servidor**
```
Rails.application.routes.draw do
root to: "home#index"
end
```

**6. E ir ao browser testar nossa rota raiz:**
- Abrir o Browser e testar a URL *localhost:3000*
