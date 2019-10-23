# Instalação

## Os pacotes essenciais são
1. Ruby (version >= 2.5)
2. Ruby-dev
3. Ruby RDoc
4. zlib-dev
5. SQLite3 (Opcional)
5. SQLite3-dev (Opcional)
6. NodeJS (Opcional)
7. Yarn (Opcional)

## No Ubuntu


```bash
# apt-get update \
    && apt-get install build-essential \
    ruby \
    ruby-dev \
    zlib1g-dev 
```

```
# gem install rails
```

# Ou

```bash
# curl -sSL https://get.rvm.io | bash -s stable --rails
# source /usr/local/rvm/scripts/rvm
```

## Instalando as dependências opcionais

### SQLite3
```bash
# apt-get install libsqlite3-dev
```

### Yarn

```bash
# apt-get install curl
```

```bash
# curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | apt-key add -
# echo "deb https://dl.yarnpkg.com/debian/ stable main" | tee /etc/apt/sources.list.d/yarn.list
```

```bash
# apt-get update
# apt-get install nodejs yarn
```


# Criando um projeto em Ruby on Rails

```
# rails new blog
```

# Rodando o servidor
```
# cd blog
# rails webpacker:install
# rails server
```

# Problemas encontrados

Deve-se instalar a gem `tzinfo-data` no Ubuntu assim como, segundo a documentação, no Windows também
