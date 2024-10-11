# Elixir-node
Install and update
# Chạy node Elixir Testnet V3
docker run -d \
  --env-file ~/w1/validator.env \
  --name e_w1 \
  --platform linux/amd64 \
  --restart unless-stopped \
  -p 17691:17690 \
  elixirprotocol/validator:v3
  update: 3.5 aval
