Extrator de Pedidos – API BrandsHUB API

Projeto que consome a API da BrandsHUB para gerar uma planilha com todos os itens dos pedidos de compra.

🔧 Funcionalidades

Conecta-se à API BrandsHUB para obter dados de pedidos de compra.

Extrai os itens de cada pedido (produto, SKU, quantidade, fornecedor etc.).

Gera uma planilha (por exemplo, em formato Excel ou CSV) com todos os itens de compras.

Permite automatização e uso em integração com sistemas de pedidos ou estoque.

🛠️ Tecnologias e ferramentas utilizadas

Linguagem: Python

Bibliotecas principais: (ex: requests, pandas, openpyxl)

Controle de versão: Git / Git Hub

Ambiente de execução: Local / servidor conforme necessidade

🚀 Como usar

Clone o repositório:

git clone https://github.com/ErickFennec01/Consumindo-api.git
cd Consumindo-api


Instale as dependências (exemplo usando pip):

pip install -r requirements.txt


Configure as credenciais da API (por exemplo, criando um arquivo .env ou passando variáveis de ambiente):

BRANDSHUB_API_KEY=seu_token
BRANDSHUB_API_URL=https://api.brandshub.com.br/…


Execute o script principal:

python extrator_pedidos.py


Ao finalizar, será gerada uma planilha com os itens dos pedidos no diretório de saída definido.

📁 Estrutura do projeto
/Consumindo-api
│
├─ extrator_pedidos.py         # Script principal que consome a API e gera a planilha  
├─ requirements.txt            # Dependências do projeto  
├─ config/                     # Configurações da API, variáveis de ambiente etc.  
└─ output/                     # Pasta onde a planilha gerada será salva  

✅ Possíveis melhorias

Adição de logs mais detalhados para acompanhamento da execução.

Tratamento robusto de erros de rede ou de resposta da API.

Suporte a formatos adicionais de saída (ex: Google Sheets, base de dados).

Integração com sistema de envio automático da planilha por e-mail.

Interface gráfica simples ou painel web para execução facilitada.

📝 Licença

Este projeto está licenciado sob a MIT License
. Sinta-se à vontade para adaptar conforme suas necessidades.
