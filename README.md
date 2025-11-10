<div align="center">

<h1>✅ Consumindo API com Django</h1>

<p>
Projeto criado para consumir uma API externa, processar dados e exibi-los usando Django e Django REST Framework.
</p>

<img src="https://img.shields.io/badge/Django-5.2-green">
<img src="https://img.shields.io/badge/Python-3.12-blue">
<img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow">

</div>

<hr>

<h2>📌 Sobre o Projeto</h2>

<p>
Este projeto consome uma API externa (ex: Varejonline), envia os dados informados pelo usuário e retorna as informações processadas.  
Perfeito para estudo e aplicações reais envolvendo:
</p>

<ul>
  <li>Consumo de APIs com <strong>requests</strong></li>
  <li>Django REST Framework</li>
  <li>Views com formulários</li>
  <li>Organização profissional de projeto Django</li>
</ul>

<hr>

<h2>🎥 Vídeo Tutorial — roteiro sugerido</h2>

<h3>🎬 Introdução</h3>
<p>"Fala galera, hoje vou mostrar como rodar localmente meu projeto Django que consome uma API externa. Bora!"</p>

<hr>

<h2>✅ 1. Clonar o projeto</h2>

<pre>
git clone https://github.com/ErickFennec01/Consumindo-api
cd Consumindo-api
</pre>

<hr>

<h2>✅ 2. Criar o ambiente virtual</h2>

<strong>Windows:</strong>
<pre>
python -m venv venv
venv\Scripts\activate
</pre>

<strong>Linux/macOS:</strong>
<pre>
python3 -m venv venv
source venv/bin/activate
</pre>

<hr>

<h2>✅ 3. Instalar dependências</h2>

<pre>
pip install -r requirements.txt
</pre>

<hr>

<h2>✅ 4. Ajustar configurações para rodar localmente</h2>

<p>Edite o arquivo <code>core/settings.py</code></p>

<p>Troque:</p>

<pre>
DEBUG = False
</pre>

<p>Por:</p>

<pre>
DEBUG = True
</pre>

<p>Mantenha:</p>

<pre>
ALLOWED_HOSTS = ['*']
</pre>

<hr>

<h2>✅ 5. Inserir Login, Senha e ID</h2>

<p>No arquivo:</p>

<pre>extrator_pedidos/views.py</pre>

<p>Altere:</p>

<pre>
EMAIL = "Coloque seu email"
PASSWORD = "Coloque sua senha"
ACCOUNT_ID = "ID DA SUA CONTA"
</pre>

<hr>

<h2>✅ 6. Rodar o servidor</h2>

<pre>
python manage.py migrate
python manage.py runserver
</pre>

<p>Acesse:</p>

<pre>
http://127.0.0.1:8000/
</pre>

<hr>

<h2>📁 Estrutura do Projeto</h2>

<pre>
Consumindo-api/
├── core/
├── extrator_pedidos/
│   ├── views.py   ← edite login/senha/ID aqui
│   ├── urls.py
│   ├── templates/
│   └── ...
├── requirements.txt
├── db.sqlite3
└── README.md
</pre>

<hr>

<h2>⚙️ Como Funciona</h2>

<ul>
  <li>Usuário envia credenciais</li>
  <li>Django envia request à API</li>
  <li>API retorna dados em JSON</li>
  <li>Django exibe ou processa no endpoint</li>
</ul>

<hr>

<h2>🛠 Tecnologias</h2>

<ul>
  <li>Python</li>
  <li>Requests</li>
  <li>Django</li>
  <li>Django REST Framework</li>
  <li>HTML Templates</li>
  <li>Git / GitHub</li>
</ul>

<hr>

<h2>🤝 Como Contribuir</h2>

<ol>
  <li>Faça um Fork</li>
  <li>Crie uma branch</li>
  <li>Faça suas alterações</li>
  <li>Abra um Pull Request</li>
</ol>

<hr>

<h2>📄 Licença</h2>

<p>MIT — livre para usar e modificar.</p>

<hr>

<div align="center">
<strong>Tamo junto! 🚀</strong>
</div>
