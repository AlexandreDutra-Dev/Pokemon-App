# Pokémon App

Aplicativo construido seguindo o tutorial [Consume a Pokemon API in Rails](https://www.youtube.com/watch?v=NXg3oE5JMm0)

# Instalação 
```
cd pokemon_app
bundle install
rake db:{create,migrate}
firgaro install
rails server
Entre em  [http://127.0.0.1:3000](http://127.0.0.1:3000).

```
# Instalação via Docker
```
sudo chown -R $USER:$USER .
sudo docker-compose run --no-deps web rails new . --force --database=postgresql
sudo docker-compose run web bundle exec rake db:{create,migrate}
sudo docker-compose up --build
sudo docker-compose up 
Entre em  [http://127.0.0.1:3000](http://127.0.0.1:3000).

```

