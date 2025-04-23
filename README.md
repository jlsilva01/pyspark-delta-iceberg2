# 🔥 Projeto PySpark com Delta Lake e Apache Iceberg

Este projeto demonstra o uso de **PySpark** com suporte aos formatos de dados **Delta Lake** e **Apache Iceberg** para processamento e gerenciamento de dados em larga escala. O ambiente foi configurado com o gerenciador de pacotes **[uv](https://github.com/astral-sh/uv)**, proporcionando performance, segurança e reprodutibilidade.

## 📦 Tecnologias Utilizadas

- [PySpark](https://spark.apache.org/docs/latest/api/python/)
- [Delta Lake](https://docs.delta.io/latest/index.html)
- [Apache Iceberg](https://iceberg.apache.org/)
- [uv (Astral)](https://github.com/astral-sh/uv)
- Python 3.13

---

## ⚙️ Setup do Projeto

### Pré-requisitos

- Python 3.13 ou superior
- `uv` instalado globalmente ([guia de instalação oficial](https://github.com/astral-sh/uv#installation))

### Clonando o projeto

```bash
git clone https://github.com/jlsilva01/pyspark-delta-iceberg2.git
cd pyspark-delta-iceberg2
```

### Criando o ambiente com `uv`

```bash
uv pip install .
```

---

## 🚀 Como Executar

Execute localmente com Spark no modo standalone:

Abrir a pasta notebook, abrir os arquivos `apache-iceberg.ipynb` e `delta-lake.ipynb`, escolher o ambiente virtual do uv como Kernel do Jupiter e executar celula por celula.

---

## 📁 Estrutura do Projeto

```
.
├── assets/               # Diretório de imagens
├── notebook/          # Notebooks de exemplo de uso do delta lake e apache iceberg
├── pyproject.toml      # Dependências do projeto com uv
├── README.md           # Este arquivo
```

---

## 📚 Referências

- [Documentação PySpark](https://spark.apache.org/docs/latest/api/python/)
- [Delta Lake Docs](https://docs.delta.io/)
- [Apache Iceberg Docs](https://iceberg.apache.org/)
- [uv - Astral](https://github.com/astral-sh/uv)

---

## 🧑‍💻 Autor

Desenvolvido por **Jorge Luiz da Silva**.  
Se tiver dúvidas, sugestões ou quiser colaborar, sinta-se à vontade para abrir uma [issue](https://github.com/seu-usuario/seu-repositorio/issues) ou enviar um pull request.

---

## 📄 Licença

Este projeto está licenciado sob a licença MIT - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.