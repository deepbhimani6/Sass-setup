### scss project

npm init -y

npm i laravel-mix --save-dev

touch webpack.mix.js

write in webpack {
let mix = require("laravel-mix");
mix.sass("src/main.scss", "public/style.css");
}

npx mix watch

npm i sass-loader@^12.1.0 sass resolve-url-loader@^5.0.0 --save-dev

npx mix watch
