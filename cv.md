![](https://media.licdn.com/dms/image/D5603AQFSEV5Ap-IDcQ/profile-displayphoto-shrink_400_400/0/1683254921999?e=1704931200&v=beta&t=LMkN-f8cL2hsjIYiSZktCiG1ZgKSsd5RuGmQRoZMJyo)

## Example code
```
function fakeBin(x){
  let result = '';
  let y;
  for (let i = 0; i <= x.length - 1; i++) {
    if (x[i] < 5) {
       y = 0;
    } if (x[i] >= 5) {
      y = 1;
    }
    result = `${result}${y}`
  }
  return result;
}
```