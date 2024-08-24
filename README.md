# EN

# Node.js Starter Template

This project provides a starter kit for Node.js. The kit includes features such as authentication (login, registration, password reset, account verification, etc.), image uploading, email sending, and error handling. The project is containerized using Docker and pushed to Docker Hub..

## Features

- **Authentication**: Login, registration, password reset, account verification
- **Image Uploading**: Allows users to upload their profile pictures
- **Email Sending**: Sends password reset and account verification emails
- **Error Handling**: Captures and handles errors appropriately
- **API Request Logging**:  Logs API requests

## Getting Started

### Local Development

1. **Requirements**:
   - Node.js (v20 or newe)
   - NPM (or Yarn)
  
2. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd nodejs_starter_template
   ```
3. **Install Dependencies**:
   - npm install
   - npm run start:dev 


This command runs your application in development mode and uses nodemon for automatic reloading.

### Production Environment

Run Docker Image: To run your application using Docker:

```bash
docker run -d -p 5000:5000 nodejs_starter_template
```
This command starts the Docker container in the background and listens to your application on port 5000.
Run with Docker Compose: You can run your project using Docker Compose. After creating the docker-compose.yml file:

```bash
docker-compose up --build
```

Docker Hub
The project is uploaded to Docker Hub. To pull and run the image:


### Pull the Image from Docker Hub:


``` bash
docker pull rumeysayuk/nodejs_starter_kit
```

Start the Docker Container:


``` bash
docker run -d -p 5000:5000 rumeysayuk/nodejs_starter_kit
```


### Operation Principles
Development Mode: The application is run in development mode with npm run start:dev. This allows for automatic reloading of code changes with nodemon.
Production Mode: The application is run in production mode with npm run start:prod. This command starts the Node.js application without additional features like debugging and logging.
Docker: Using Docker, you can run your application inside a container. Docker provides a portable environment with all the application's dependencies


# Contributors
## Rumeysa Yük:  Project Developer


# TR

# Node.js Starter Template

Bu proje, Node.js için bir başlangıç kiti sağlar. Kit, kimlik doğrulama işlemleri (giriş, kayıt, şifre sıfırlama, hesap doğrulama vb.), resim yükleme, e-posta gönderimi ve hata yakalama gibi özellikleri içerir. Proje, Docker ortamında containerize edilmiştir ve Docker Hub'a yüklenmiştir.

## Özellikler

- **Kimlik Doğrulama**: Giriş, kayıt, şifre sıfırlama, hesap doğrulama
- **Resim Yükleme**: Kullanıcıların profil resimlerini yüklemelerine olanak tanır
- **E-posta Gönderimi**: Şifre sıfırlama ve hesap doğrulama e-postaları gönderir
- **Hata Yönetimi**: Hataları yakalar ve uygun şekilde işler
- **API İsteklerini Loglama**: API isteklerini loglar

## Başlarken

### Yerel Geliştirme

1. **Gereksinimler**:
   - Node.js (v20 veya daha yeni)
   - NPM (veya Yarn)
  
2. **Projeyi Klonlayın**:
   ```bash
   git clone <repository-url>
   cd nodejs_starter_template
   ```
3. **Bağımlılıkları Yükleyin**:
   - npm install
   - npm run start:dev 


Bu komut, uygulamanızı geliştirme modunda çalıştırır ve nodemon kullanarak otomatik yeniden yükleme sağlar.

### Üretim Ortamında
Docker İmajını Çalıştırın: Docker kullanarak uygulamanızı çalıştırmak için:

```bash
docker run -d -p 5000:5000 nodejs_starter_template
```
Bu komut, Docker container'ını arka planda başlatır ve uygulamanızı 5000 portunda dinler.

Docker Compose ile Çalıştırın: Docker Compose kullanarak projenizi çalıştırabilirsiniz. docker-compose.yml dosyasını oluşturduktan sonra:

```bash
docker-compose up --build
```
Docker Hub
Proje Docker Hub'a yüklendi. İmajı çekmek ve çalıştırmak için:


### Docker Hub'dan İmajı Çekin:

``` bash
docker pull rumeysayuk/nodejs_starter_kit
```
Docker Container'ını Başlatın:


``` bash
docker run -d -p 5000:5000 rumeysayuk/nodejs_starter_kit
```


### Çalışma Prensibi
Geliştirme Modu: npm run start:dev komutu ile uygulama, nodemon ile geliştirme modunda çalıştırılır. Bu, kodda yapılan değişikliklerin otomatik olarak yüklenmesini sağlar.
Üretim Modu: npm run start:prod komutu ile uygulama, üretim modunda çalıştırılır. Bu komut, Node.js uygulamasını başlatır ve hata ayıklama, loglama gibi ek özellikler içermez.
Docker: Docker kullanarak uygulamanızı container içinde çalıştırabilirsiniz. Docker, uygulamanızın tüm bağımlılıklarıyla birlikte taşınabilir bir ortamda çalışmasını sağlar.
# Katkıda Bulunanlar
## Rumeysa Yük: Proje geliştiricisi
