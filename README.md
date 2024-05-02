# Lista de Tarefas com Django

Este é um projeto simples de uma lista de tarefas desenvolvido utilizando o framework Django. O projeto permite que os usuários criem, visualizem, atualizem e excluam tarefas da lista.

## Funcionalidades

- **Criação de tarefas:** Os usuários podem adicionar novas tarefas à lista, especificando um título e uma data de entrega.
- **Visualização de tarefas:** Os usuários podem visualizar todas as tarefas na lista de tarefas.
- **Atualização de tarefas:** Os usuários podem editar o título e a data de entrega de tarefas existentes.
- **Exclusão de tarefas:** Os usuários podem excluir tarefas da lista.
- **Marcação de tarefas como concluídas:** Os usuários podem marcar tarefas como concluídas, registrando a data de conclusão.

## Pré-requisitos

- Python 3.x
- Django 3.x

## Instalação

## Clone o repositório
```bash
git clone https://github.com/devgustavoalves/to-do-list.git
```

## Navegue até o diretório do projeto
```bash
cd nome-do-repositorio
```

## Crie um ambiente virtual (opcional, mas recomendado)
```bash
python -m venv venv
```

## Ative o ambiente virtual (se estiver usando um)
### No Windows
```bash
venv\Scripts\activate
```

### No macOS e Linux

```bash
source venv/bin/activate
```
## Instale as dependências do projeto
```bash
pip install -r requirements.txt
```

## Execute as migrações do banco de dados
```bash
python manage.py migrate
```

## Inicie o servidor de desenvolvimento
```bash
python manage.py runserver
```

### Acesse o projeto no seu navegador em `http://localhost:8000/`.

## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request ou relatar um problema.

## Licença

Este projeto é licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT).

