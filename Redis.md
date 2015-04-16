# Redis

http://redis.io/

## Bash Shortcuts

### Start `redis-server` in User Directory with Command `rs`

``` bash
# Redis-Server in User Directory (`~/redis`)

rs() {
  mkdir -p ~/redis
  cd ~/redis
  redis-server &
  cd -
}
```
