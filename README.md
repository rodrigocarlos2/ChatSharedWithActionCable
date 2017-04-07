
# Shared Chat in Network Local

Sample App from https://www.youtube.com/watch?v=n0WUjGkDFS0

## How to run

Clone this repository, and:

```
git clone https://github.com/rodrigocarlos2/ChatSharedWithActionCable.git
```

Install dependencies

```
bundle install
```

You should be able to chat like this:

![c7ERfXIREG.gif](https://qiita-image-store.s3.amazonaws.com/0/7465/b58e0bc4-eb80-3176-9baf-3009323c4485.gif "c7ERfXIREG.gif")

## Network Scenario

![Diagram.pdf](Diagram.pdf "Diagram.pdf")

For run in this scenario, open /config/environments/development.rb and write:

```
config.action_cable.allowed_request_origins = ['http://localhost:3000','http://10.180.40.8:3000']
```

## License

MIT License.

## Update

Rodrigo Carlos Carvalho Lima Barbosa Leal.
