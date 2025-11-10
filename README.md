# Extrator de Pedidos – BrandsHUB

Projeto criado para consumir a API do BrandsHUB e gerar uma planilha contendo todos os itens dos pedidos de compra.

---

## 🔧 Funcionalidades

- Consome a API do BrandsHUB.
- Extrai todos os itens dos pedidos de compra.
- Gera planilhas em Excel/CSV com os dados coletados.
- Ideal para automação de compras e controle de estoque.

---

## 🛠️ Tecnologias Utilizadas

- **Python**
- **Requests**
- **Pandas**
- **OpenPyXL**
- **Git / GitHub**

---

## 🚀 Como Usar

### 1. Clonar o repositório
```bash
git clone https://github.com/ErickFennec01/Consumindo-api.git
cd Consumindo-api
2. Instalar dependências
bash
Copiar código
pip install -r requirements.txt
3. Configurar credenciais
Crie um arquivo .env ou ajuste diretamente no código:

ini
Copiar código
BRANDSHUB_API_KEY=SEU_TOKEN
BRANDSHUB_API_URL=https://api.brandshub.com.br/...
4. Executar o extrator
bash
Copiar código
python extrator_pedidos.py
A planilha final será salva dentro da pasta output/.

📂 Estrutura do Projeto
bash
Copiar código
Consumindo-api/
│
├─ extrator_pedidos.py       # Script principal
├─ requirements.txt          # Dependências
├─ config/                   # Configurações e arquivos auxiliares
└─ output/                   # Planilhas geradas
✅ Melhorias Futuras
Adicionar logs detalhados.

Tratar erros de conexão/timeout com a API.

Enviar planilha automaticamente por e-mail.

Dashboard web ou interface gráfica.

📌 Observação
Este projeto foi desenvolvido com foco em automação interna de pedidos, garantindo rapidez e precisão na geração das planilhas.

📜 Licença
Projeto disponibilizado sob licença MIT.

yaml
Copiar código

---

Se quiser, posso:

• criar um **badge de status**,  
• adicionar **GIF de demonstração**,  
• personalizar com **ícones e logos**,  
• ou criar um **banner visual** para o topo do README.

Só pedir.
