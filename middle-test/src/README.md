<h1>お問い合わせフォーム</h1>
    <h2>環境構築</h2>
     <p>Docker ビルド</p>
        <ul>
            <li>docker-compose up -d --build</li>
        </ul>
    <p>Laravel環境構築</p>
        <ol>
            <li>docker-compose exec php bash</li>
            <li>composer create-project "laravel/laravel=8.*" . --prefer-dist</li>
        </ol>
    <p>マイグレーション</p>
        <ol>
            <li>php artisan make:migration create_contacts_table</li>
            <li>php artisan make:migration create_categories_table</li>
            <li>php artisan make:migration create_users_table</li>
        </ol>
    <p>シーディング</p>
        <ol>
            <li>php artisan make:seederContactsTableSeeder</li>
            <li>php artisan make:seeder CategoriesTableSeeder</li>
            <li>php artisan make:seeder UsersTableSeeder</li>
        </ol>
    <h2>使用技術</h2>
        <ul>
            <li>PHP7.4.9</li>
            <li>laravel3.8</li>
            <li>mysql8.0.26</li>
            <li>HTML</li>
            <li>CSS</li>
        </ul>
    <h2>URL</h2>
            <li>
                開発環境:<a href="http://localhost/">http://localhost/</a>
            </li>
            <li>
                phpMyAdmin:<a href="http://localhost:8080/">http://localhost:8080/</a>
            </li>
