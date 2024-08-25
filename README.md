Controle de Despesas

Descrição

O projeto Controle de Despesas é uma aplicação web desenvolvida em Django para gerenciar e acompanhar despesas pessoais. O sistema permite a criação, visualização, edição e exclusão de despesas, categorizando-as e permitindo a conversão dos valores para diferentes moedas usando taxas de câmbio atualizadas. A aplicação também oferece funcionalidades para gerenciar categorias de despesas e importar taxas de câmbio de uma API externa.

Funcionalidades

Cadastro e Gestão de Categorias: Permite adicionar, editar e excluir categorias de despesas.
Cadastro e Gestão de Despesas: Adicione, edite e exclua despesas, associando-as a categorias específicas e registrando a data da despesa.
Conversão de Moeda: Visualize os valores das despesas convertidos para diferentes moedas com base nas taxas de câmbio mais recentes.
Importação de Taxas de Câmbio: Atualize as taxas de câmbio a partir de uma API externa para garantir a precisão dos valores convertidos.
Tecnologias Utilizadas
Django: Framework web para desenvolvimento rápido de aplicações.
Python: Linguagem de programação utilizada no desenvolvimento.
API de Taxas de Câmbio: Utilizada para obter taxas de conversão de moedas.
HTML/CSS: Para construção das páginas web e estilização.

Instalação

Clone o Repositório
    git clone https://github.com/Matheus-Andre-Soares/workshop-fabrica-2024.2-matheus-andre
    cd seu-repositorio

Crie um Ambiente Virtual
    python -m venv env
    Ative o Ambiente Virtual

No Windows:
    env\Scripts\activate

No macOS/Linux:
    source env/bin/activate

Instale as Dependências
    pip install -r requirements.txt

Configure o Banco de Dados
    python manage.py migrate

Crie um Superusuário (opcional, para administração)
    python manage.py createsuperuser

Inicie o Servidor de Desenvolvimento
    python manage.py runserver
    A aplicação estará disponível em http://127.0.0.1:8000/

 Uso

Página Inicial: Navegue para a página inicial para acessar as funcionalidades do aplicativo.
Gestão de Categorias: Acesse a lista de categorias para adicionar, editar ou excluir categorias.
Gestão de Despesas: Adicione, edite ou exclua despesas através da lista de despesas.
Conversão de Moeda: Use o formulário na página de despesas para converter os valores das despesas para diferentes moedas.
Configuração da API de Taxas de Câmbio
O projeto utiliza uma API externa para obter as taxas de câmbio. Certifique-se de que o URL da API está correto e funcional na função importar_taxas dentro de views.py.

Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests, relatar problemas ou sugerir melhorias.

Contato

Se você tiver alguma dúvida, entre em contato com:

Nome: Matheus André
E-mail: matheusandre2004@gmail.com