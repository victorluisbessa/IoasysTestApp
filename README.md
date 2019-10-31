# IoasysTestApp

Esta é uma aplicação criada como teste para o cargo desenvolvedor react-native na empresa Ioasys, utilizando react-native, e a abstração Expo.

Foi utilizada uma ApiFake com python flask, para a comunicação e simulação do uso da Api testes da ioasys, que estava em erro no prazo do teste. Foram utilizadas diversas formas de estruturação de código para apresentação das diferentes formas. É extremamente recomendado a utilização de apenas uma padronização de códigos.

Estão disponíveis fotos da aplicação rodando em um aparelho Samsung Galaxy a50 na pasta Screenshot.

É possível ver a aplicação em funcionamento no link a seguir: https://youtu.be/e-YiciOnvkw

Infelizmente não foi possível simular todos os EndPoints disponibilizados devido ao prazo diminuto.

Os Arquivos .py da aplicação fakeApi estão disponíveis na pasta fakeApi. 
Para executá-la basta navegar até a pasta e executar o comando python api.py

Para rodar a aplicação é necessário:

1. Python 3x

2. Flask (Para instalar basta executar "pip install flask" no terminal)

3. Lembre-se de mudar o arquivo api.js localizado na pasta Services, mudando a variável baseUrl para o IP da sua máquina. É possível descobrir seu IP digitando ipconfig no terminal. O aplicativo só consegue conectar ao servidor Flask estando na mesma rede local (roteador).

O aplicativo foi desenvolvido a ultima versão do Expo SDK 35.00 (31/10/2019), portanto o sistema de geração de APKS ainda não foi atualizado para a nova versão. Assim que liberado haverá um update com a APK gerada. (Se necessário, para o teste).

No aplicativo foram utilizadas as seguintes dependências:
1.  Axios => Utilizado para a conexão e consumo da Api via POST. Embora não tenha havido tempo a API simulada é capaz de receber parametros GET>
2.  Expo => Permite rápido prototipagem e geração de arquivos .apk, acelerando a produção da aplicação.
3.  Lottie => Permite a execução de animações AfterEffects dentro de aplicações nativas (React-native)
4.  React Navigation e dependencias => Permite o roteamento de telas. Foi utilizado arquivo Routes.js para a navegação.
5.  React Native Vector Icons => Pacote de icones "estilo material design", perfeitos para uso e prototipagem. 
