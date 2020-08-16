Added session storage support 

if u want use session storage

add useLocalStorage:false

```
const sessionStorage = new SecureLS({
    encodingType: 'aes',
    + useLocalStorage:false
});

```

**[Main Demo](https://github.com/softvar/secure-ls)**
**[Main Package](http://softvar.github.io/secure-ls#live-demo)**
