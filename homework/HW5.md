# 1.Bit
## code:
```
CHIP Bit {
    IN in, load;
    OUT out;

    PARTS:
    // Put your code here:
    Mux(a=gayout,b=in,sel=load,out=a);
    DFF(in=a,out=out,out=gayout);
}
```
# 2.














# ![image](5.jpg)
