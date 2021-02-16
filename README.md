# Digital-electronics-1
## git hub link
https://github.com/xsobon02/Digital-electronics-1

## De Morgan's laws

### VHDL
```vhdl
architecture dataflow of gates is
begin
    f_o  <= ((not b_i) and a_i) or ((not c_i) and (not b_i)) ;
    fnand_o <= not(not(not b_i and a_i) and not(not c_i and not b_i));
    fnor_o <= not(b_i or not a_i) or not(c_i or b_i);

end architecture dataflow;
      
```
![DeMorgan signals](https://github.com/xsobon02/Digital-electronics-1/blob/main/demorgan.png)
### Lists
1. list1
2. list2

* Item 1
* Item 2
  * Item 2a
  * Item 2b

### Links
[Google link](https://www.google.com)

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


