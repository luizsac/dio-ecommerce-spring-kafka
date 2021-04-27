### Instruções para rodar

* No menu do Gradle, executar o comando "generateAvroJava" em Tasks > source generation. Fazer isso tanto para o serviço de checkout quanto para o serviço de payment;
* Abrir o terminal na pasta dio-ecommerce-checkout-api/docker e executar o comando ```docker-compose up --build -d``` para instanciar o container do docker;
* Executar CheckoutApplication e PaymentApplication