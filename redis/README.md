# Redis BDSM Extension

## Usage

  redis <options> <action>

## Options

Path to redis.conf file

    redis --conf /etc/redis/redis.conf

Path to redis pid file

    redis --pid /var/run/redis.pid

Path to redis server binary

    redis --bin /usr/bin

Username to invoke redis as

    redis --user redis

Use to debugging the control script

    redis --trace <action>


## Actions

Start Redis

    redis start

Stop Redis

    redis stop

Restart Redis

    redis restart

Display Redis INFO output for the server

    redis info

Show if Redis is running and on what port if so.

    redis status

Display the CLI usage information

   redis help

