# DydxTradingBot

![License](https://img.shields.io/badge/license-MIT-blue)
![Version](https://img.shields.io/badge/version-1.0.0-green)

Um robô de trading automatizado e robusto projetado para monitorar e executar operações na descentralizada bolsa de valores (DEX) dYdX v4. Este projeto utiliza estratégias algorítmicas para navegar pelo mercado de criptomoedas de forma eficiente.

## ⚠️ Aviso Legal (Disclaimer)

**Este software é apenas para fins educacionais.**
Operar com criptomoedas envolve riscos financeiros significativos. Os autores não são responsáveis por quaisquer perdas financeiras incorridas ao usar este bot. Negocie sempre de forma responsável e nunca arrisque mais do que pode perder.

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter o seguinte instalado em seu sistema:

*   **Git**: Para clonar o repositório.
*   **Python 3.10+**: A linguagem principal usada para o bot.
*   **pip**: Gerenciador de pacotes do Python.
*   **Conta dYdX**: Você deve ter uma carteira dYdX v4 ativa com fundos suficientes para negociação e taxas de gás.

## 🔧 Instalação

Siga estes passos para configurar o projeto localmente.

1. **Clonar o Repositório**

   bash
   git clone https://github.com/your-username/DydxTradingBot.git
   cd DydxTradingBot
   

2. **Criar um Ambiente Virtual**

   É recomendado usar um ambiente virtual para gerenciar dependências:

   bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   

3. **Instalar Dependências**

   bash
   pip install -r requirements.txt
   

4. **Configuração**

   Renomeie o arquivo `config.example.json` para `config.json` e preencha com suas credenciais e chaves de API. **Nunca faça commit do seu arquivo `config.json` para o Git.**

   
   {
       "wallet_mnemonic": "sua frase mnemônica secreta aqui",
       "api_key": "sua_chave_api_dYdX",
       "trading_pair": "BTC-USD",
       "risk_per_trade": 0.01
   }
   

## 🚀 Uso

Para iniciar o robô de trading, execute o script principal pelo seu terminal:

bash
python main.py


O bot irá inicializar, conectar-se à rede dYdX v4 e começar a monitorar o mercado com base na sua configuração.

*   **Para parar o bot**: Pressione `Ctrl+C` no terminal.

## 🤝 Contribuindo

Contribuições são o que tornam a comunidade de código aberto um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será **grandemente apreciada**.

1. Faça um Fork do Projeto
2. Crie sua Branch de Funcionalidade (`git checkout -b feature/NovaFuncionalidade`)
3. Commite suas Alterações (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a Branch (`git push origin feature/NovaFuncionalidade`)
5. Abra um Pull Request

## 📄 Licença

Distribuído sob a Licença MIT. Veja o arquivo `LICENSE` para mais informações.

## 📞 Suporte

Se você tiver dúvidas ou precisar de suporte, por favor abra uma Issue no repositório.