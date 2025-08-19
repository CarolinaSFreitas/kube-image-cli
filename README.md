# Kubernetes Get Images

Este projeto contém scripts e arquivos de configuração para auxiliar na gestão de imagens de containers em clusters Kubernetes.

## Descrição

- **kubernetes-get-images.py**: Script Python para listar imagens de containers em recursos do Kubernetes.
- **nginx.yml**: Exemplo de manifesto YAML para deploy de um serviço NGINX no Kubernetes.
- **config.yml**: Arquivo de configuração (detalhes de uso dependem do contexto do projeto).
- **requirements.txt**: Lista de dependências Python necessárias para rodar o script.

## Pré-requisitos

- Python 3.7+
- Acesso a um cluster Kubernetes
- `kubectl` configurado

## Instalação

1. Clone este repositório:
   ```sh
   git clone https://github.com/CarolinaSFreitas/kube-image-cli.git
   cd Projeto2
   ```
2. (Opcional) Crie e ative um ambiente virtual:
   ```sh
   python -m venv .venv
   .venv\Scripts\activate  # Windows
   source .venv/bin/activate  # Linux/Mac
   ```
3. Instale as dependências:
   ```sh
   pip install -r requirements.txt
   ```

## Uso

1. Certifique-se de que o arquivo de configuração do Kubernetes (`.kube/config` ou similar) está disponível.
2. Execute o script principal:
   ```sh
   python kubernetes-get-images.py
   ```

## Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
