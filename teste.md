## Instalando servidor Hybris


#### Requisitos
- Cópia do Hybris
- Banco de dados MySQL
- dbdriver
- Java

#### Estrutura das pastas
Crie uma pasta `HYBRIS` dentro da sua home

```bash
$ mkdir -p ~/HYBRIS
```

Crie a pasta do projeto que está desenvolvendo

```bash
$ mkdir -p ~/HYBRIS/project_name
```

Extraia a pasta `bin/` do `HYBRIS` para dentro da pasta criada no passo anterior

Compile o `HYBRIS` pela primeira vez

```bash
$ cd ~/HYBRIS/project_name/bin/platform
$ ./apache-ant-1.9.1/bin/ant clean all
```

Isso vai criar a pasta config
