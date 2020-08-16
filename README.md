Added session storage support 

if u want use session storage

add useLocalStorage:false

```
const sessionStorage = new SecureLS({
    encodingType: 'aes',
    + useLocalStorage:false
});

```

**[Main Demo](http://softvar.github.io/secure-ls#live-demo)**
**[Main Package](https://github.com/softvar/secure-ls)**
