# Basic-Logic-Gates-
VHDL code on the basic logic gates using the VHDL code
library IEEE;
use IEEE.STD_LOGIC_1164.ALL;



entity BasicLogGates is
    Port ( a : in  STD_LOGIC;
           b : in  STD_LOGIC;
           y_nota : out  STD_LOGIC;
           y_and : out  STD_LOGIC;
           y_nand : out  STD_LOGIC;
           y_or : out  STD_LOGIC;
           y_nor : out  STD_LOGIC;
           y_xor : out  STD_LOGIC;
           y_xnor : out  STD_LOGIC);
end BasicLogGates;

architecture Behavioral of BasicLogGates is

begin

			y_nota <=nota;
			y_and <=a and b;
			y_or <=a or b;
			y_nand <=a nand b;
			y_nor <=a nor b;
			y_xor <=a xor b;
			y_xnor <=a xnor b;



end Behavioral;
