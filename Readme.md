# Kafka Demo

Bu proje kafka demosu olarak geçmekte ve silngle instance olarak çalışmakta

1. Projede ilk önce kafkayı docker olarak kurmanız gerekmekte.

    ```bash
    cd docker
    docker-compose -f docker-compose-single-broker.yml up
    ```

2. Ana dizinde `consumer.js` başlatmamız gerekmekte.

    ```bash
    node consumer.js
    ```

3. Mesaj gönderme aşamasında ise `publisher.js` çalıştırmak gerekmekte

    ```bash
    node publisher.js
    ```

Vualla gönderilmiş mesaj için consumer.js konsolunu kontrol edebilirsiniz.
