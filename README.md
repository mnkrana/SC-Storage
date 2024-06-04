Install dependencies

```
yarn
```

## Usage

1. Run your ganache local chain, by hitting `quickstart` on your ganache application

2. Copy the `RPC SERVER` sting in your ganache CLI, and place it into your `.env` file

```
RPC_URL=http://0.0.0.0:8545
```

3. Hit the key on one of the accounts, and copy the key you see and place it into your `.env` file

```
PRIVATE_KEY=11ee3108a03081fe260ecdc106554d09d9d1209bcafd46942b10e02943effc4a
```

4. Compile your code

```
yarn compile
```

5. Run your application

```
node scripts/deploy.js
```
