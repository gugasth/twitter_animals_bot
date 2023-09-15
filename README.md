# Bot de Twitter com Tema de Animais 🐾

Um bot de Twitter com o objetivo de a espalhar alegria por fotos de animais através de retweets, likes, etc.

## Estado Atual 🚀

Atualmente, o bot está configurado apenas para autenticação. Estou trabalhando para torná-lo totalmente funcional em breve!

## Configuração com Chaves de API Protegidas

Para proteger as chaves de API do bot, é utilizado o pacote `python-dotenv`. Abaixo seguem instruções para configurar o ambiente virtual e ativar as variáveis de ambiente:

### Criar o Ambiente Virtual

```shell
python3 -m venv bot_env
```

### Pra ativar o Ambiente Virtual

No windows:

```shell
bot_env\Scripts\activate
```

No linux:

```shell
source bot_env/bin/activate
```

### Instalação de dependências

```shell
pip install -r requirements.txt
```

Agora é só criar um .env no repositório raíz e colocar nas variáveis de ambiente as keys do bot.

```makefile
TWITTER_CONSUMER_KEY= ...
TWITTER_CONSUMER_SECRET= ...
TWITTER_ACCESS_TOKEN= ...
TWITTER_ACCESS_TOKEN_SECRET= ...
``````


