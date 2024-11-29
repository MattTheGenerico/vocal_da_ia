# vocal_da_ia
IA de TTS (Text to Speech) usando o GTTS (Google Text To Speech)

Vocal da IA
Este é um projeto simples de geração de vocais a partir de texto usando Flask e GTTS (Google Text-to-Speech). O projeto permite gerar vocais em MP3 a partir de uma entrada de texto dada pelo usuário.

Pré-requisitos
Antes de rodar o projeto, é necessário ter o Python instalado no seu computador. Caso não tenha o Python instalado, você pode baixá-lo e instalá-lo em python.org.

Além disso, você precisará instalar algumas bibliotecas para o projeto funcionar:

Flask: Framework para criar a aplicação web.
GTTS (Google Text-to-Speech): Biblioteca para converter texto em áudio.
Instalação
Siga os passos abaixo para configurar o ambiente e rodar o projeto.

Passo 1: Baixar o repositório
Clone este repositório para o seu computador:

bash
Copiar código
git clone https://github.com/SEU_USUARIO/vocal-da-ia.git
Passo 2: Criar um ambiente virtual (opcional, mas recomendado)
Para evitar conflitos de versão com outras bibliotecas que você já tenha instalado, é recomendável criar um ambiente virtual para o projeto.

No terminal, na pasta do projeto, execute os seguintes comandos:

bash
Copiar código
python -m venv venv
Isso criará uma pasta chamada venv com o ambiente virtual.

Passo 3: Ativar o ambiente virtual
No Windows:
bash
Copiar código
venv\Scripts\activate
No macOS/Linux:
bash
Copiar código
source venv/bin/activate
Passo 4: Instalar as dependências
Instale as bibliotecas necessárias para o projeto:

bash
Copiar código
pip install -r requirements.txt
Ou, se preferir instalar manualmente as bibliotecas:

bash
Copiar código
pip install flask gtts pyttsx3
Passo 5: Rodar o servidor
Com o ambiente configurado, execute o servidor Flask:

bash
Copiar código
python app.py
Isso iniciará o servidor localmente. O servidor estará disponível em http://127.0.0.1:5000.

Passo 6: Acessar no navegador
Abra o seu navegador e acesse o seguinte endereço:

arduino
Copiar código
http://127.0.0.1:5000
A partir daí, você poderá interagir com o formulário para gerar os vocais a partir do texto.

Como funciona
Quando você envia um texto pelo formulário, o Flask processa a entrada e usa o GTTS (Google Text-to-Speech) para gerar o vocal.
O vocal gerado será salvo como um arquivo MP3 e exibido para o usuário baixar ou ouvir.
Contribuindo
Sinta-se à vontade para contribuir com melhorias, correções ou novas funcionalidades. Caso queira contribuir, basta seguir os passos abaixo:

Faça um fork deste repositório.
Crie uma branch para a sua modificação (git checkout -b minha-modificacao).
Faça o commit das suas alterações (git commit -am 'Adiciona nova funcionalidade').
Envie a sua branch para o repositório remoto (git push origin minha-modificacao).
Abra um pull request explicando as suas alterações.
Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.

Detalhes Adicionais:
Se você tiver um arquivo requirements.txt, adicione as bibliotecas e suas versões nele. Para criar esse arquivo, você pode usar o comando pip freeze > requirements.txt, que irá gerar um arquivo com todas as bibliotecas instaladas no ambiente virtual.

