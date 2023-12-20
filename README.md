##Minha Pasta Zipada
Bem-vindo à minha pasta zipada! Aqui você encontrará uma aplicação em React Native para mapear os pontos de área de risco na zona sul da cidade de Recife.

**Desculpem o transtorno. Foi necessário o envio dos arquivos de forma zipada no GitHub devido a um erro no Git.**

##Como usar
1.Faça o download do arquivo zip clicando em "Code" e selecionando "Download ZIP".
2.Extraia o conteúdo do arquivo zip em seu computador.
3.Abra as pastas no compilador desejado.

##Contribuição
Sinta-se à vontade para contribuir, abrir problemas ou sugerir melhorias. Se precisar de ajuda, não hesite em entrar em contato.

Apreciaremos sua colaboração!

Este projeto se trata de uma aplicação em React Native para mapear os pontos de área de risco na zona sul da cidade de Recife.

Utilizei de um arquivo .GeoJSON para a implementação dos dados vistos no mapa, obtidos através da seguinte plataforma governamental de Recife: http://dados.recife.pe.gov.br/dataset/defesa-civil

Estes são os componentes que necessitam ser instalados para o funcionamento correto da aplicação:

npm install

npm install react react-dom

npm install @react-navigation/native

npm install @react-navigation/native-stack

npm install react-native-vector-icons

npm install axios

npx expo install expo-location

npx expo install react-native-maps

npm install haversine

npx expo start
