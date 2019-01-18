swarm
========
쿠마 서버 도커스웜 파일.

```sh
docker swarm init

docker stack deploy -c cloudkeeper.yml cloudkeeper
docker stack deploy -c gitlab.yml      gitlab
docker stack deploy -c hyeonbot.yml    hyeonbot
docker stack deploy -c jokbo.yml       jokbo
docker stack deploy -c langdev.yml     langdev
docker stack deploy -c rust-kr.yml     rust-kr
```

### TODOs
아직 도커스웜으로 감싸지지 않은 서비스들이 있다. 이것들도 감싸자

- [ ] caddy
- [ ] xz-mirror (/etc/systemd/system)
- [ ] `/srv/hyeon.me`
- [ ] `/srv/i.hyeon.me`
- [ ] `/srv/kuma.hyeon.me`
- [ ] `/srv/game.hyeon.me`
