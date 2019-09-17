# checkpoint1

My hierarchical decoder tree is:
 Top level： alu;
      Second level: ADD, SUBTRACT, AND32, OR32, SLL, SRA, mux32_8, mux;
            ADD: RCA_16, mux16, overflow;
                  RCA_16: fa;
            SUBTRACT: ADD, overflow, isNotEqual, isLessThan;
            ADD: RCA_16, mux16, overflow;
                  RCA_16: fa;
            SLL: mux;
            SRA: mux;
            mux32_8: mux32;
     
     
