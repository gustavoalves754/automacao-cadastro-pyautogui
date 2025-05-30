# Automação de Cadastro com PyAutoGUI

Este projeto foi desenvolvido como parte de um curso de automação em Python, usando a biblioteca **PyAutoGUI** para simular interações humanas com o computador. O script realiza o login em um sistema web e cadastra automaticamente produtos a partir de uma base de dados em CSV.

---

## 🚀 Tecnologias utilizadas

- Python 3
- PyAutoGUI
- Pandas

---

## 📋 Funcionalidades

✅ Abrir o navegador e acessar o site do sistema  
✅ Realizar login automático com e-mail e senha  
✅ Ler arquivo `produtos.csv` com os dados dos produtos  
✅ Preencher e cadastrar cada produto no sistema  
✅ Repetir o processo para todos os itens da base  

---

## 🏗 Como executar o projeto

1️⃣ Clone o repositório ou baixe os arquivos  
```bash
git clone https://github.com/gustavoalves754/automacao-cadastro-pyautogui.git

2️⃣ Instale as bibliotecas necessárias:

pip install pyautogui pandas

3️⃣ Certifique-se de ter o arquivo produtos.csv na mesma pasta do script.

4️⃣ Execute o script:

python automocao.py

⚠️ Observações importantes
O script depende da posição exata dos elementos na tela (coordenadas x, y), então pode ser necessário ajustar esses valores conforme o seu monitor e resolução.

Mantenha o navegador em tela cheia e o sistema corretamente aberto para o funcionamento ideal.

Não mexa no computador enquanto o script está rodando, pois ele simula teclado e mouse!
