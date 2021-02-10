# Digital-electronics-1
## Headers

### Emphasis

*Emphasis italics*
**Emphasis bold**

### Lists
1. list1
2. list2
⋅⋅* Unordered sub-list. 
1. un list
⋅⋅1. Ordered sub-list
4. list4

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

### VHDL
```vhdl
clkgen: process(clk_in, reset)
      begin
        if reset = '1' then
          clk_gen <= '1';
        elsif clk_in'event and clk_in = '1' then
          clk_gen <= q2;
        end if;
      end process clkgen;
      
```
