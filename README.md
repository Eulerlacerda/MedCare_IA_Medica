# MedCare_IA_Medica
IA_Medica_Disgnostico

# 🏥 MedCare - IA Médica Virtual

O **MedCare** é um sistema inteligente de pré-diagnóstico médico que utiliza inteligência artificial para analisar sintomas e sugerir possíveis condições de saúde. Desenvolvido com Flask e SQLite, o sistema oferece uma interface web simples e eficaz para usuários descreverem seus sintomas e receberem orientações iniciais.

---

## 🚀 Funcionalidades

- 🔍 Diagnóstico baseado em sintomas descritos pelo usuário
- 🧠 Detecção de sentimentos e emoções no texto
- 📚 Base de dados com doenças, sintomas, descrições e recomendações
- 🗂️ Armazenamento de consultas realizadas
- 🌐 Interface web com renderização via Flask
- 🛠️ Inicialização automática do banco de dados com `schema.sql`

---

## 🧪 Exemplos de Condições Detectadas

- Gripe
- Resfriado
- Diabetes
- Hipertensão
- Ansiedade
- Depressão
- COVID-19
- Enxaqueca
- Gastrite
- Insônia

---

## 🧠 Tecnologias Utilizadas

- **Backend**: Python, Flask
- **Banco de Dados**: SQLite
- **Outros**:
  - JSON para estrutura de dados
  - HTML (via `render_template`) para interface
  - `schema.sql` para estruturação do banco

---

## 📦 Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/medcare.git
   cd medcare
Instale as dependências (se necessário):

bash
pip install flask
Execute o servidor:

bash
python app.py

⚠️ Aviso Importante
Este sistema fornece um pré-diagnóstico automatizado com base em sintomas descritos pelo usuário. Não substitui a consulta com um profissional de saúde. Sempre procure orientação médica adequada.

👨‍💻 Autor
Euler Lacerda Desenvolvedor Full Stack apaixonado por soluções que unem tecnologia e saúde.
