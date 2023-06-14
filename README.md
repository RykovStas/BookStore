# BookStore

---

### This repository serves as a comprehensive platform for selling books, encompassing multiple services. The core concept behind this project involves utilizing a dedicated store API to facilitate the management of book information, inventory updates, order processing, and order status tracking. The store service is responsible for communicating with the API through requests in order to accomplish tasks such as periodically synchronizing book data, creating new orders, and regularly updating order statuses. To streamline communication processes, the Celery service is employed to handle API requests and email notifications. Consequently, customers receive email notifications upon order submission and whenever there are changes to their order status.

---
# Stack
* Django
* Django Rest Framework
* Docker
* PostgreSQL
* Nginx
* Celery
* RabbitMq
* REDIS
* Bootstrap
* jQuery, AJAX
* MailHog
* Debug ToolBar
