# [Run Code 1](https://dev98.ml/lab/rc1)
## ลองหา condition ที่หายไป
```
let x,y,str='';
for(x=0;x<10;x++){
    for(y=0;y<10;y++){
        str+=(อะไรบางอย่าง)
    }
}
console.log(str);
```
```
var x,y,str='';
for(x=0;x<10;x++){
    for(y=0;y<10;y++){
        str+= x%2===0 ? `${x/2}` : `${x*y}`
    }
}
```
ผลลัพธ์
```0000000000012345678911111111110369121518212427222222222205101520253035404533333333330714212835424956634444444444091827364554637281```

## ลองเอา condition มาใช้กับ code อื่น
```
let x,y=20,str='';
for(x=0;x<y;x++){
    str+=md5(อะไรบางอย่าง);
    y--;
}
console.log('Ans: '+md5(str));
```
```
var x,y=20,str='';
for(x=0;x<y;x++){
    str+=md5(x%2===0 ? `${x/2}` : `${x*y}`);
    y--;
}
console.log('Ans: '+md5(str));
```
# ans
```
30321e6a9c3ff636805b9516e0d5eeec
```
