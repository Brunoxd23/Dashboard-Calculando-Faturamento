# Dashboard de Empregabilidade

## 📊 Sobre o Projeto
Dashboard desenvolvido para análise de empregabilidade dos alunos. O sistema permite visualizar métricas importantes, gráficos interativos e exportar dados em diferentes formatos.

## 🚀 Funcionalidades

- **Visualização de Métricas**
  - Total de alunos
  - Taxa de empregabilidade
  - Contratações Einstein
  - Outras instituições

- **Gráficos Interativos**
  - Evolução da empregabilidade
  - Distribuição por instituição
  - Visualização em tela cheia
  - Interação com dados

- **Exportação de Dados**
  - Download em CSV
  - Apresentação em PowerPoint
  - Gráficos em alta resolução

## 🛠️ Tecnologias Utilizadas

- Python 3.8+
- Streamlit
- Plotly
- Pandas
- Python-PPTX

## ⚙️ Instalação

1. Clone o repositório:

git clone https://github.com/seu-usuario/dashboard-einstein.git
cd dashboard-einstein

Instale as dependências:  pip install -r requirements.txt

streamlit run empregabilidade/dashboard.py

## 📦 Dependências

pip install -r requirements.txt

streamlit==1.31.1
pandas==2.1.4
plotly==5.18.0
python-pptx==0.6.21
openpyxl==3.1.2
kaleido==0.2.1

# Instalação das dependências na AWS

mkdir meu_projeto

CD meu_projeto

python3 -m venv venv
source venv/bin/activate

# 1. Atualize o sistema
sudo yum update -y

# 2. Instale o Python e pip
sudo yum install python3 python3-pip -y

# 3. Instale o git
sudo yum install git -y

# 4. Clone seu repositório
git clone https://github.com/Brunoxd23/Dashboard-Empregabilidade-Ensino.git
cd Dashboard-Calculando-Faturamento

# 5. Instale as dependências
pip3 install -r requirements.txt

# 6. Instale o Streamlit
pip3 install streamlit

# 7. Instale e use o tmux para manter o dashboard rodando
sudo yum install tmux -y
tmux new -s dashboard

# 8. Dentro da sessão tmux, execute o dashboard
streamlit run dashboard.py --server.port 8501 --server.address 0.0.0.0
source venv/bin/activate

# 9. Puxe as atualizações do GitHub
git pull origin main


## 🖥️ Uso

1. Selecione a turma desejada no dropdown
2. Visualize as métricas principais nos cards
3. Interaja com os gráficos
4. Exporte os dados conforme necessário
5. Use o modo tela cheia para apresentações

## 🎨 Personalização

O dashboard possui tema escuro com gradientes modernos e é totalmente responsivo. Os elementos visuais são otimizados para apresentações e exportações.

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👤 Autor

Bruno Monteiro

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Reportar bugs
2. Sugerir novas funcionalidades
3. Enviar pull requests

---
Desenvolvido por Bruno Monteiro
