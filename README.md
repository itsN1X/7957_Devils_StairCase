# 7957_Devils_StairCase
![](112.png) v/s ![](1211.jpg) v/s  a temporal correlation to ![](wk.png) at the `#et7956` timeseries datapoints.

### References:

 - [ ] 1: Mons. [Minkowski](https://en.wikipedia.org/wiki/Hermann_Minkowski) !
 - [ ] 2: Mons. [Cantor](https://en.wikipedia.org/wiki/Georg_Cantor) !!

### Cold Rex


`/* Minkowski's question-mark function */`

```
double minkowski(double x) {
        long p=x; if ((double)p>x) --p; /* p=floor(x) */
        long q=1, r=p+1, s=1, m, n;
        double d=1, y=p;
        if (x<(double)p||(p<0)^(r<=0)) return x; /* out of range ?(x) =~ x */
        for (;;) /* invariants: q*r-p*s==1 && (double)p/q <= x && x < (double)r/s */
        {
                d/=2; if (y+d==y) break; /* reached max possible precision */
                m=p+r; if ((m<0)^(p<0)) break; /* sum overflowed */
                n=q+s; if (n<0) break; /* sum overflowed */
 
                if (x<(double)m/n) r=m, s=n;
                else y+=d, p=m, q=n;
        }
        return y+d; /* final round-off */
}
```

### See files like:

![](1.svg)


### More meta to glob upon!

#### Definition

!: `Cantor function` - To formally define the Cantor function 'c' : [0,1] → [0,1], let x be in [0,1] and obtain c(x) by the following steps:

 - Express x in base 3.
 - If x contains a 1, replace every digit after the first 1 by 0.
 - Replace all 2s with 1s.
 - Interpret the result as a binary number. The result is c(x)


---

## More c00L hedges to be unravelled at [`N1X.site`](https://n1x.site)
