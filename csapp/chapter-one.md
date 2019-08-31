# 计算机系统漫游

源程序实际就是一个由值0和1组成的位（又称比特）序列，8个位被组成一组称为字节。

```c
#include <stdio.h>
int main(){
  printf("hello, world\n");
  return 0;
}
```

通过hello world 程序解释程序运行的流程。

``` flow
st=>start: Start:>https://www.markdown-syntax.com
io=>inputoutput: verification
op=>operation: Your Operation
cond=>condition: Yes or No?
sub=>subroutine: Your Subroutine
e=>end
st->io->op->cond
cond(yes)->e
cond(no)->sub->io
```



