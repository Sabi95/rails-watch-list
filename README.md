# 🎞 Savi's Watchlist

A small web application to keep track of movies you have watched or would like to watch. You can also organize movie lists by genre!

<img width="1248" alt="2022-12-07" src="https://user-images.githubusercontent.com/114859704/206101308-c77d4b5b-4bb0-4a61-a8e2-7fb70f8e696f.png">
<img width="1248" alt="2022-12-07 (1)" src="https://user-images.githubusercontent.com/114859704/206101334-5c88eb3b-f1ad-4150-a02c-0d1254fa538c.png">

<br>
App home: https://savi-watch-list.herokuapp.com/
   

## Getting Started
### Setup

Install gems
```
bundle install
```
Install JS packages
```
yarn install
```

### ENV Variables
Create `.env` file
```
touch .env
```
Inside `.env`, set these variables. For any APIs, see group Slack channel.
```
CLOUDINARY_URL=your_own_cloudinary_url_key

```

### DB Setup
```
rails db:create
rails db:migrate
rails db:seed
```

### Run a server
```
rails s
```

## Built With
- [Rails 7](https://guides.rubyonrails.org/) - Backend / Front-end
- [Heroku](https://heroku.com/) - Deployment
- [PostgreSQL](https://www.postgresql.org/) - Database
- [Bootstrap](https://getbootstrap.com/) — Styling

## Acknowledgements
I have to thank Le Wagon here for sharing this project idea with their students, and inspiring me to make my own movie watchlist!


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License
