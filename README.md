## Next.js + postgres の devcontainer
### devcontainer で開いたら下記でアプリケーションが立ち上がる
1. git clone https://github.com/teftef-TY/nextjs-prisma.git .
2. npm install && npx prisma migrate dev --name init
3. npm run dev

上記 2 までを実行後は通常通り開発を行える。

workspace の中のリポジトリは git clone で取ってくるようにしているが、submodule にした方がいいのか悩むけど、環境を提供することが目的なためこれでOKとしておく。
