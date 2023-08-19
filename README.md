## Simple React Context Example

React Context Example: Theme and User Contexts

### Description

This project demonstrates the usage of React Context API to manage theme and user data between different components within a React application. It illustrates how to create, provide, and consume contexts to maintain global state within a React app.

### Contexts

#### Theme Context

The Theme Context is responsible for managing the application's theme. It allows users to switch between light and dark themes. The theme choice is stored in the browser's localStorage for persistence.

#### User Context

The User Context manages user-related data. It handles user login and logout functionalities.

### Components

#### Profile

The `Profile` component displays user information and provides functionality for logging in and logging out.

#### Header

The `Header` component displays the active theme and provides a button to toggle between light and dark themes.

#### Button

The `Button` component displays the active theme and provides a button to toggle between light and dark themes. This component can be used both within the `Container` component and as a standalone component.

---

## Basit React Context Örneği

React Context Örneği: Tema ve Kullanıcı Kontekstleri

### Açıklama

Bu proje, React Context API'nın kullanımını göstererek, bir React uygulamasındaki farklı bileşenler arasında tema ve kullanıcı verilerini yönetmeyi sergiler. React uygulaması içinde global durumu korumak için bağlamaları oluşturmayı, sağlamayı ve tüketmeyi gösterir.

### Kontekstler

#### Tema Konteksti

Tema Konteksti, uygulamanın temasını yönetmekten sorumludur. Kullanıcılara açık ve karanlık tema arasında geçiş yapma olanağı sunar. Tema seçimi tarayıcının localStorage'unda süreklilik için saklanır.

#### Kullanıcı Konteksti

Kullanıcı Konteksti, kullanıcıyla ilgili verileri yönetir. Kullanıcı girişi ve çıkışı işlevselliğini yönetir.

### Bileşenler

#### Profil

`Profil` bileşeni kullanıcı bilgilerini görüntüler ve giriş yapma ile çıkış yapma işlevselliği sunar.

#### Başlık

`Başlık` bileşeni etkin temayı görüntüler ve açık ve karanlık temalar arasında geçiş yapma düğmesi sağlar.

#### Düğme

`Düğme` bileşeni etkin temayı görüntüler ve açık ve karanlık temalar arasında geçiş yapma düğmesi sağlar. Bu bileşen hem `Container` içinde hem de bağımsız bir bileşen olarak bulunabilir.
