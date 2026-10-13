# PlayerBalancerForVelocity

Fork of [PlayerBalancer](https://github.com/BGHDDevelopment/PlayerBalancer) focused on **Velocity**.

Balances players across servers/sections on a Velocity proxy (lobbies, games, etc.).

## Build

```bash
mvn clean package
```

Main artifact:

- `balancer-velocity/target/PlayerBalancer-Velocity-2.4.0.jar`

Optional modules (Bungee / Spigot addon / PartyAndFriends) remain in the repo but are not required for Velocity.

## Install

1. Place the Velocity jar in the proxy `plugins` folder.
2. Start the proxy once to generate `plugins/playerbalancer/plugin.conf`.
3. Configure sections and set `general.enabled = true`.
4. Restart or use `/balancer reload`.

## Configuration

See the comments in `plugin.conf` (generated from `velocity.conf`).

## Changelog

See [CHANGELOG.md](CHANGELOG.md).

## License

MIT (see [LICENSE](LICENSE)).

Upstream: [BGHDDevelopment/PlayerBalancer](https://github.com/BGHDDevelopment/PlayerBalancer) (archived).
