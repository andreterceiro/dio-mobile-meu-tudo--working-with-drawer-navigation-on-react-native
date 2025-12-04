# Initial demo

![initial demo](images/demo-drawer-navigation.png)


# Installation

```
npm install @react-navigation/drawer
```


# Installation of extra packages

Para um projeto "Bare", sem o Expo:

In a project with Expo:
```
npx expo install react-native-gesture-handler react-native-reanimated react-native-worklets
```

In a project without Expo:
```
npm install react-native-gesture-handler react-native-reanimated react-native-worklets
```

**OBS:** in the command inserted by the teacher, he did not installled the package "react-native-worklets", but I got the command I passed above [from the updated manual](https://reactnavigation.org/docs/drawer-navigator/?framework=expo#installation)


# Finishing the installation

To finish the installation teacher said that we must do an import in index.js or App.js (in a demo project I saw only the files index.tsx and App.tsx):

![importing in index js or app js](images/importing-in-index-js-or-app-js.png)

Teacher did this in App.tsx:

![importing in App.tsx](images/importing-in-App-tsx.png)


# Creating the file routes/drawer.routes.tsx

As teacher did with other types of navigations, teacher created the file routes/drawer.routes.tsx.