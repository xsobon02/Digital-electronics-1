# Digital-electronics-1
## git hub link
https://github.com/xsobon02/Digital-electronics-1

## De Morgan's laws

### VHDL
```vhdl
architecture dataflow of gates is
begin
    f_o  <= ((not b_i) and a_i) or ((not c_i) and (not b_i)) ;
    fnand_o <= (not(not b_i and a_i) nand not(not c_i and not b_i));
    fnor_o <= not(b_i or not a_i) or not(c_i or b_i);

end architecture dataflow;
      
```
![DeMorgan signals](https://github.com/xsobon02/Digital-electronics-1/blob/main/Labs/01-gates/demorgan1.png)

[EDA Playground example](https://www.edaplayground.com/x/DUUw)

## Distributive laws

### VHDL
```vhdl
architecture dataflow of gates is
begin
    f1_o  <= (a_i and b_i) or (a_i and c_i) ;
    f2_o <= a_i and (b_i or c_i) ;
    f3_o <= (a_i or b_i) and (a_i or c_i) ;
    f4_o <= a_i or (b_i and c_i) ;

end architecture dataflow;
      
```
![DeMorgan signals](https://github.com/xsobon02/Digital-electronics-1/blob/main/Labs/01-gates/distributive.png)

[EDA Playground example](https://www.edaplayground.com/x/u9Gi)


### Table
| **c** | **b** |**a** | **f(c,b,a)** |
| :-: | :-: | :-: | :-: |
| 0 | 0 | 0 |  |
| 0 | 0 | 1 |  |
| 0 | 1 | 0 |  |
| 0 | 1 | 1 |  |
| 1 | 0 | 0 |  |
| 1 | 0 | 1 |  |
| 1 | 1 | 0 |  |
| 1 | 1 | 1 |  |


