# development-platform-codespaces


```shell
git clone --recurse-submodules https://${CUSTOM_GITHUB_TOKEN}:x-oauth-basic@github.com/mss-boot-dev/development-platform.git
git clone --recurse-submodules https://${CUSTOM_GITHUB_TOKEN}:x-oauth-basic@github.com/mss-boot-dev/development-platform-ui.git
cd development-platform && go mod download && cd .. && go run . migrate && go run . server -a
cd development-platform-ui && pnpm i
```