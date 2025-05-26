# **Mapeamento de Tarefas no Azure**  

## 📌 **Introdução:**  

O **Microsoft Azure** é uma das principais plataformas de computação em nuvem, oferecendo diversos serviços para infraestrutura, armazenamento e desenvolvimento de aplicações. Este projeto tem como objetivo mapear tarefas comuns para seus respectivos serviços no Azure, facilitando o entendimento da plataforma.  

Este código permite que usuários insiram uma tarefa e recebam automaticamente o recurso do Azure correspondente. Com uma estrutura modularizada, testes automatizados e containerização, o projeto está pronto para uso profissional e escalável.  

---

## 📂 **Estrutura do Projeto**  

📦 `azure-mapping/`  
┣ 📂 `src/` → Código principal  
┃ ┣ 📄 `functions.py` → Funções auxiliares para identificar os recursos do Azure  
┃ ┣ 📄 `main.py` → Código principal que interage com o usuário  
┣ 📂 `tests/` → Testes automatizados  
┃ ┣ 📄 `tests.py` → Testes unitários para garantir o correto funcionamento do código  
┣ 📄 `Dockerfile` → Arquivo para containerização do projeto  
┣ 📄 `requirements.txt` → Dependências necessárias para execução  
┣ 📄 `README.md` → Documentação do projeto  

---

## 🔍 **Tabela de Mapeamento de Recursos**  

| **Tarefa**                                      | **Recurso Correspondente**           | **Descrição do Recurso** |
|-------------------------------------------------|--------------------------------------|--------------------------|
| Criar um servidor com sistema operacional       | **Máquina Virtual**                  | Serviço que permite a criação de máquinas virtuais para execução de sistemas operacionais e aplicações. |
| Guardar dados em um banco relacional           | **Instância de Banco de Dados**       | Solução para armazenamento de dados estruturados, garantindo segurança e escalabilidade. |
| Explorar os serviços disponíveis               | **Portal Azure**                      | Interface gráfica baseada na web que permite a administração de recursos e serviços do Azure. |
| Criar conta para acessar o Azure               | **Conta Microsoft e Assinatura**      | Credenciais necessárias para acessar e gerenciar os recursos dentro da plataforma Azure. |

---

1️⃣ **Clone o repositório**  

```bash
git clone https://github.com/seu-usuario/azure-mapping.git
cd azure-mapping
```

2️⃣ **Instale as dependências**  

```bash
pip install -r requirements.txt
```

3️⃣ **Execute o código**  

```bash
python src/main.py
```

4️⃣ **Rodar os testes automatizados**  

```bash
python -m unittest tests/tests.py
```

---

## 🐳 **Containerização com Docker**  

Este projeto pode ser executado de forma padronizada usando **Docker**.  

### **1️⃣ Construir o Container**  

```bash
docker build -t azure-mapping .
```

### **2️⃣ Rodar o Container**  

```bash
docker run azure-mapping
```

---

## 🔥 **Melhorias Implementadas:**  

✅ **Código Modularizado** → Separação de funções para facilitar manutenção  
✅ **Tratamento de Entrada** → Validação avançada para evitar erros do usuário  
✅ **Sugestões Inteligentes** → Usa _fuzzy matching_ para reconhecer textos semelhantes  
✅ **Testes Automatizados** → Implementação com `unittest` para garantir qualidade  
✅ **Containerização com Docker** → Facilita execução padronizada  
✅ **Documentação Completa** → README detalhado para fácil entendimento  

---

## 💡 **Conclusão:**  
Este repositório fornece uma maneira prática e eficiente de aprender sobre os serviços do Azure, ajudando usuários a identificarem rapidamente os recursos adequados para cada tarefa.  

Com uma implementação otimizada, modularizada e testada, este projeto se destaca pela qualidade, escalabilidade e facilidade de uso.  
