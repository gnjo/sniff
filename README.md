# sniff
data reporter
```
//need object
function sniff(o,caller){o= new Proxy(o,{ set:(oo,k,v)=>{return caller(oo,k,v),oo[k]=v } }) }
sniff(param,caller(o,k,v)=>{
})


```
