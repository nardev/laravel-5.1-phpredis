PhpRedis Connector for Laravel 5.1
==============================

placement for the `RedisServiceProvider` that comes with Laravel.

Requirements
------------

 - PHP 5.3+
 - Laravel 5.1

Installation
-------------

THIS IS:
laravel-5.1-phpredis
Same package as vetruvet/laravel-phpredis but with small fix for Laravel 5.1

Should Also Add:



'providers' => [
...
	Nardev\PhpRedis\PhpRedisServiceProvider::class,
...
]

comment default "Illuminate\Redis\RedisServiceProvider::class" and add the alias


'aliases' => [
...
        'PHPRedis'  => 'Illuminate\Support\Facades\Redis',
...
]



