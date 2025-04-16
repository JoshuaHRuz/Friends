# 👥 Friend App

Una aplicación web sencilla desarrollada con Ruby on Rails que permite a los usuarios gestionar su lista de amigos. Los usuarios pueden registrarse, iniciar sesión, añadir nuevos amigos, ver sus detalles de contacto y editar su perfil.

## ✨ Características

* Autenticación de usuarios utilizando [Devise](https://github.com/heartcombo/devise)
* Añadir, ver y gestionar amigos
* Interfaz de usuario responsive con [Bootstrap](https://getbootstrap.com/)
* Acceso basado en roles (los usuarios solo ven sus propios amigos)

## 🚀 Empezando

Sigue estos pasos para poner en marcha la aplicación en tu entorno local:

1.  **Clona el repositorio:**

    ```bash
    git clone [https://github.com/your-username/friend-app.git](https://github.com/your-username/friend-app.git)
    cd friend-app
    ```

2.  **Instala las dependencias:**

    ```bash
    bundle install
    yarn install # si estás usando webpacker
    ```

3.  **Configura la base de datos:**

    ```bash
    rails db:create db:migrate db:seed
    ```

4.  **Inicia el servidor:**

    ```bash
    rails server
    ```

5.  **Visita** `http://localhost:3000` **en tu navegador.**

## 🔐 Credenciales de Prueba

Utiliza las siguientes cuentas para iniciar sesión y explorar la aplicación:

* **👤 Administrador**
    * Email: `admin@adm.com`
    * Contraseña: `123456`
* **👤 Usuario Regular**
    * Email: `josh@hotmail.com`
    * Contraseña: `123456`

## 🛠 Tecnologías Utilizadas

* [Ruby on Rails](https://rubyonrails.org/)
* [Devise](https://github.com/heartcombo/devise)
* [Bootstrap](https://getbootstrap.com/)
