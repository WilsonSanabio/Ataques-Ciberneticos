## 🛡️ Painel Interativo de Ataques Cibernéticos

Este projeto apresenta uma interface web interativa para explorar os principais tipos de ataques cibernéticos, organizados por categoria e ilustrados com ícones temáticos. Desenvolvido com HTML, CSS e JavaScript, o painel permite:

- 📂 Visualizar ataques agrupados por categoria (Autenticação, Malware, Engenharia Social etc.)
- 🔍 Acessar detalhes completos de cada ameaça com exemplos reais, ferramentas utilizadas e notas de mitigação
- 📱 Navegar de forma responsiva em qualquer dispositivo (desktop, tablet ou celular)
- 🧠 Utilizar navegação dinâmica entre páginas com armazenamento local (`localStorage`)
- 🧪 Rodar localmente via servidor Python para testes offline

### 📁 Estrutura do Projeto

- `ataques.html`: página principal com os cards de ataques
- `detalhes.html`: página de detalhes individuais
- `ataques.json`: base de dados com os ataques e suas características
- `estilo.css` e `estilo-detalhes.css`: arquivos de estilização separados
- `servidor.py`: script opcional para rodar localmente com suporte ao botão de encerramento

### 🚀 Como executar
Abra o terminal (Prompt de Comando ou PowerShell)
Navegue até o diretório do projeto
cd caminho/para/Ataques-Ciberneticos
Execute o servidor local com Python
python server.py
O navegador será aberto automaticamente com a página ataques.html.

### 🚀 Como visualizar online

Este projeto pode ser hospedado diretamente via **GitHub Pages**, bastando ativar a opção nas configurações do repositório. Basta acessar:

https://WilsonSanabio/Ataques-Ciberneticos/ataques.html
