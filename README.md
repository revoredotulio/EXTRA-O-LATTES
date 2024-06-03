
# Projeto de Extração de Informações do Currículo Lattes

Este repositório contém diversos blocos de códigos em notebooks Jupyter para extrair informações do currículo Lattes. Abaixo estão listados os notebooks com suas respectivas descrições.

## Estrutura do Projeto

IMIP-LATTES/
├── notebooks/
│ ├── EXTRAÇÃO DE ARTIGOS.ipynb
│ ├── EXTRAÇÃO DE CAP DE LIVRO.ipynb
│ ├── EXTRAÇÃO DE DISCIPLINAS.ipynb
│ ├── EXTRAÇÃO DE LIVROS.ipynb
│ ├── EXTRAÇÃO DE ORIENTAÇÕES.ipynb
│ ├── EXTRAÇÃO DE OUTRAS PUBLICAÇÕES.ipynb
│ ├── EXTRAÇÃO DE PRODUÇÃO TÉCNICA.ipynb
│ └── EXTRAÇÃO DE PROJETOS DE PESQUISA.ipynb
├── docs/
│ └── additional_documentation.md
├── LICENSE
├── README.md
├── requirements.txt
└── setup.py

## Requisitos

- Python 3.x
- Jupyter Notebook

## Instalação

1. Clone o repositório:
    ```sh
    git clone https://github.com/revoredotulio/IMIP-LATTES.git
    cd IMIP-LATTES
    ```

2. Instale as dependências:
    ```sh
    pip install -r requirements.txt
    ```

## Uso

1. Abra o Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

2. No navegador, abra o notebook desejado no diretório `notebooks/`, por exemplo, `notebooks/EXTRAÇÃO DE ARTIGOS.ipynb`.

3. Execute as células do notebook para realizar a extração dos dados do Currículo Lattes.

## Exemplos

### Extração de Artigos

Abra `notebooks/EXTRAÇÃO DE ARTIGOS.ipynb` e execute as células para extrair informações sobre artigos publicados. O notebook irá carregar os dados do Currículo Lattes e processar as informações para exibir uma tabela com os artigos.

### Extração de Capítulos de Livro

Abra `notebooks/EXTRAÇÃO DE CAP DE LIVRO.ipynb` e execute as células para extrair informações sobre capítulos de livros. O notebook irá carregar os dados do Currículo Lattes e processar as informações para exibir uma tabela com os capítulos de livros.

## Contribuições

Sinta-se à vontade para contribuir com melhorias ou novas funcionalidades. Para isso, siga os passos abaixo:

1. Faça um fork do repositório.
2. Crie uma branch para suas alterações:
    ```sh
    git checkout -b minha-branch
    ```
3. Faça commit das suas alterações:
    ```sh
    git commit -m "Minha contribuição"
    ```
4. Faça push para a branch:
    ```sh
    git push origin minha-branch
    ```
5. Abra um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para abrir uma issue ou entrar em contato comigo.

---

**Observação**: Este projeto é uma demonstração de como extrair informações do Currículo Lattes utilizando Python e Jupyter Notebook. Certifique-se de ajustar os notebooks de acordo com suas necessidades específicas.
