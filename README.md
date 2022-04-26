## Broadcasting with soketi

https://kbouzidi.com/real-time-events-with-laravel-and-soketi?utm_source=newsletter&utm_medium=email&utm_campaign=freek.dev+newsletter+%23149

https://github.com/Safemood/REAL-TIME-LARAVEL-9-SOKETI

1. Prepare laravel to broadcast events
2. Soketi installation
3. Create evetns
4. Create routes
5. Prepare the front
6. Views

1. Preapare
Uncomment broadcastServiceProvider in the array of providers in config/app.php
Update config/broadcasting.php
Install the Pusher Channels PHP SDK
    - composer require pusher/pusher-php-server
Update .env file
Authentication logic - Laravel Breeze
    - composer require laravel/breeze --dev
    - php artisan breeze:install
    - npm install && npm run dev
    - php artisan migrate
2. Instal Soketi
    https://docs.soketi.app/getting-started/installation/cli-installation
    Via docker: docker run -p 6001:6001 -p 9601:9601 quay.io/soketi/soketi:0.17-16-alpine

3. Events

4. Routes

5. Front
    - npm install --save-dev laravel-echo pusher-js axios


