-   [doc](https://laravel.com/docs/8.x/sanctum#spa-authentication)

1.  you can see in `confg/sanctum.php` file, and need to create **SANCTUM_STATEFUL_DOMAINS** in `.env` file. It is allow client to use session cookies to authenticate in server. In client you can set `axios.defaults.withCredentials = true;`
2.  In `config/session.php` file, you can see `domain` then you need to set **SESSION_DOMAIN** in `.env` file`
