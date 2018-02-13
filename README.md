# left-recusion
c programe to remove Left Recursion in a Grammer.

INPUT: A->Aa/Ab/Ac/.........../x/y/z......

OUTPUT: A->xA'/yA'/zA'......
        A'->aA'/bA'/cA'/....../$(null)
        
NOTE: IT only works for Direct left recursionnot indirect.
