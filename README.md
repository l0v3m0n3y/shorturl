# shorturl
JavaScript library for shorturl.life
# main
```js
async function main(){
    const {shorturl} = require('./shorturl');
    const short= new shorturl();
    let req=await short.short_url("link")
    console.log(req)
}
main()
```
