AI Use Log 

Task #1
Tool/model & version: Chat-GPT 5 mini
What I asked for: Help me set up code to run RBH for SPR-5 and KDM1A to confirm orthology
What I changed before committing: I added extra sections of code to uncompress the large proteome files because the BLAST databases would not work due to the code still being compressed.
How I verified correctness (tests, sample data): I used commands  !head -n 5 humanproteome.fasta and
!head -n 5 celegansproteome.fasta to view file format before creating databases. 

Task #2 
Tool/model & version: Chat-GPT 5 mini
What I asked for: Help me run the forward and reverse best hits. Also help me summarize the top results in a seperate table.
What I changed before committing: I edited code to help with formatting the table.
How I verified correctness (tests, sample data): I looked up each TrEMBL ascession in UniProt to verify if follow-up hits were isoforms. I also compared the reciprocal hits which complement each other when analyzing outputs like percent identiy, evalue, and bitscore. 


Tool/model & version: 
What I asked for: 
What I changed before committing: 
How I verified correctness (tests, sample data): 

Tool/model & version: 
What I asked for: 
What I changed before committing: 
How I verified correctness (tests, sample data): 

Tool/model & version: 
What I asked for: 
What I changed before committing: 
How I verified correctness (tests, sample data): 
