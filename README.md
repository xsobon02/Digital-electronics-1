# Digital-electronics-1
## Headers

### Emphasis

*Emphasis italics*
**Emphasis bold**

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
