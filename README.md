# sf_final_2
- Генерируем образ в DockerHub

talyalev/django-pg

- Деплой проекта с Helm Charts:

$ git clone https://github.com/BroccoliPower/sf_final_2.git
$ cd sf_final_2/charts/
$ helm upgrade --install --namespace default --values db/values.yaml mydb db
$ helm upgrade --install --namespace default --values app/values.yaml myapp app

Приложение можно проверить по адресу ноды с портом 5000 
