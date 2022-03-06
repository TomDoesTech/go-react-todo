## Initialize Go app
go mod init github.com/tomdoestech/go-react-todo

## Install Fiber v2
go get -u github.com/gofiber/fiber/v2

## Create client app with Vite
yarn create vite client -- --template react-ts

## Install dependencies
yarn add @mantine/hooks @mantine/core swr @primer/octicons-react