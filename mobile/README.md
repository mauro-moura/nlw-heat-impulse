# Dia 3

## O que vamos aprender nessa aula?

Faremos a versão mobile

* Splash Screen
* Autenticação com Github

## Criação do projeto com React Native Expo e Typescript
    Expo-CLI: npm install -g expo-cli
    expo init mobile
* Organização da pasta
* Criar Interface Home
* Assets do Projeto
* Fonte Personalizada
    expo install expo-font @expo-google-fonts/roboto
    expo install expo-app-loading
* Criar Header
* SVG
    expo install react-native-svg
    yarn add --dev react-native-svg-transformer
* Chanfro do Celular
    yarn add react-native-iphone-x-helper
* LinearGradient
    expo install expo-linear-gradient
* Criar Componente de Mensagens
* Animação com Moti
    yarn add moti
    expo install react-native-reanimated

    adicionar no babel.config.js:
        plugins: ['react-native-reanimated/plugin']
* SignIn
* Button
* Envio de Mensagem

* Integração com a API
    Hooks usando context api

    Api do Expo: AuthSession
        expo install expo-auth-session expo-random
* Criar conta do Expo
    no app colocar expo login
* Para requisições Web
    yarn add axios

* Async Storage
    expo install @react-native-async-storage/async-storage

*

* Para conexão em realtime
    yarn add socket.io-client

Componente Básico de React
```js
import React from 'react';

import { View } from 'react-native';

import { styles } from './styles';

export function Header() {
    return(
        <View>

        </View>
    )
}
```

Estilo

```js
import { StyleSheet } from 'react-native';

export const styles = StyleSheet.create({
    container: {
        flex: 1,
    }
});
```

