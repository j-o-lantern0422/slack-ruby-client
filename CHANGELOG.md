### 0.1.1 (Next)

* [#2](https://github.com/dblock/slack-ruby-client/pull/2): `Slack::RealTime::Socket` now pings frames every 30s, as recommended by Slack - [@samdoiron](https://github.com/samdoiron).
* [#3](https://github.com/dblock/slack-ruby-client/issues/3): RealTime client WebSocket frame ping frequency is now configurable with `Slack::RealTime::Client.websocket_ping` - [@dblock](https://github.com/dblock).
* [#3](https://github.com/dblock/slack-ruby-client/issues/3): RealTime client WebSocket proxy is now configurable with `Slack::RealTime::Client.websocket_proxy` - [@dblock](https://github.com/dblock).
* [#3](https://github.com/dblock/slack-ruby-client/issues/3): Added global `Slack::Web::Client` and `Slack::RealTime::Client` configuration options via `Slack::Web::Client.configure` and `Slack::RealTime::Client.configure` - [@dblock](https://github.com/dblock).
* Exposed `Slack::RealTime::Client.url`, `team`, `self`, `users`, `channels`, `groups`, `ims` and `bots` - [@dblock](https://github.com/dblock).
* Default user-agent for `Slack::Web::Client` now includes a slash, eg. _Slack Ruby Client/0.1.1_ - [@dblock](https://github.com/dblock).
* Fix: set `Slack::Web::Client` connection options for `ca_path`, `ca_file`, and `proxy` - [@dblock](https://github.com/dblock).

* Your contribution here.

### 0.1.0 (7/25/2015)

* Initial public release with Web and RealTime Messaging API support - [@dblock](https://github.com/dblock).
