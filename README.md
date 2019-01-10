# nextjs-typescript-hapi-saga-immutable

## RUN
```bash
yarn install
yarn dev

# open localhost:3100
```

## TODO
* saga ---> success
* immutable ---> success
* env
* md
* intl
* styled-components
* fetch cancel requests
* hapijs
* header
* pm2.json
* try / catch & React Error Boundary

## *intl 国际化 方案*

> 参考其他方案:
>
> 1. next-i18next-example

切换语言时, 请保留当前 路由信息, 然后 **硬跳转 (丢失 redux 信息; 重新初始化)**, 并提示用户 重新获取信息中
