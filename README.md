<h1 align="center">ConnectedIn: Protótipo de Rede Social com Django</h1>

<p align="center">
	<img alt="Django" src="https://img.shields.io/badge/Django-4.x-0C4B33?logo=django&logoColor=white">
	<img alt="Python" src="https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white">
	<img alt="Status" src="https://img.shields.io/badge/Projeto-Educacional-1F6FEB">
</p>

Este projeto foi desenvolvido como um ambiente de estudo para praticar desenvolvimento web com Django em um contexto realista: uma rede social com cadastro, login, perfis, conexoes e publicacoes.

## O que voce vai praticar

- Estrutura de projeto Django em apps separados.
- Fluxo de autenticacao de usuarios.
- Relacionamentos entre modelos no banco de dados.
- Operacoes de CRUD com formularios e views.
- Organizacao de templates, arquivos estaticos e media.

## Funcionalidades principais

- Cadastro de usuario.
- Login e logout.
- Visualizacao e edicao de perfil.
- Convites de conexao entre perfis.
- Publicacao e exclusao de postagens.
- Upload de imagem de perfil e capa.

## Tecnologias utilizadas

- Python
- Django
- SQLite
- HTML, CSS e JavaScript
- Bootstrap

## Capturas de tela

<img src="docs/images/tela-cadastro-nova.png" width="100%" alt="Tela de cadastro" />
<img src="docs/images/tela-feed-nova.png" width="100%" alt="Tela de primeiro acesso ao feed" />
<img src="docs/images/login.png" width="100%" alt="Tela de login" />
<img src="docs/images/perfil.png" width="100%" alt="Tela de perfil" />

## Como executar o projeto

1. Clonar o repositorio:

```bash
git clone https://github.com/maristelaoliveira/rede-social.git
cd rede-social
```

2. Criar e ativar ambiente virtual:

```bash
python -m venv .venv
source .venv/bin/activate
```

3. Instalar dependencias:

```bash
pip install -r requirements.txt
python -m pip install pillow
```

4. Aplicar migracoes:

```bash
python manage.py makemigrations
python manage.py migrate
```

5. Iniciar servidor local:

```bash
python manage.py runserver
```

6. Abrir no navegador:

```text
http://127.0.0.1:8000/
```

## Estrutura simplificada do projeto

```text
connectedin/   -> configuracoes gerais do projeto
perfis/        -> funcionalidades da rede social (perfil, conexoes, postagens)
usuarios/      -> autenticacao e gerenciamento de usuarios
docs/images/   -> imagens usadas no README
media/         -> uploads realizados na aplicacao
```

## Desafios sugeridos para os alunos

- Implementar curtidas nas postagens.
- Adicionar comentarios em cada post.
- Criar pagina de notificacoes.
- Permitir busca por nome e email.
- Criar testes automatizados para views principais.

## Observacoes para estudo

- Analise como as urls estao organizadas no projeto.
- Observe o uso de templates herdando uma base comum.
- Repare como os arquivos estaticos e media sao tratados no Django.

## Autoria

Projeto utilizado para fins educacionais.

Feito com o coração pela Prof.ª Maristea
