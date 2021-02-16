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
![DeMorgan signals](https://github.com/xsobon02/Digital-electronics-1/blob/main/Labs/01-gates/demorgan.png)

[EDA Playground example](https://www.edaplayground.com/x/DUUw)




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


