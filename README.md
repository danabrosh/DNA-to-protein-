# DNA-to-protein


Proteins are essential molecules responsible for most of the work inside our cells-support structure, enable biochemical reactions, transport substances, and regulate processes.
The genetic information that cells use to build new proteins is stored in the DNA.
To use this information, cells perform two key steps: 
1. **Transcription** – the DNA is copied into messenger RNA (mRNA).
2. **Translation** – the mRNA is read in sets of three bases called **codons**, each coding for a specific amino acid.
   
## What does this project do? 

This project simulates how cells turn DNA into proteins through transcription and translation. It includes four main parts:

1. **Codon Translation**  
   Converts a 3-letter DNA codon (like ATG) into an RNA codon and then translates it into the corresponding amino acid.
2. **Reading Frames and ORFs**  
   Analyzes a full DNA sequence, prints all three reading frames, finds valid open reading frames (from `AUG` to a stop codon), and translates them. Repeats for the complementary strand.
3. **Motif Search**
   Searches the sequence for known or user-defined motifs (for example,TATA, CG) and reports how many times they appear and their positions.
4. **Mutation Simulation**  
   Introduces random point mutations and shows the mutated sequence with differences- can serve as a biological tool for exploring gene variation.
## Input:
 DNA sequence as a string or a FASTA file.
 
 • The user will be asked to choose which function to run (Codon Translation, Reading Frames, Motif Search, or Mutation Simulation).  
- Depending on the part:
  - A codon (3 letters)
  - A motif (predefined or custom)
  - Number of mutations to introduce
## Output:
- RNA codons and amino acids  
- Reading frames and translated proteins  
- Motif counts and positions  
- Mutated DNA with listed base changes
  
## ⚙️ How to Use
  * This project is written in Python 3.

    Run the following commands in your terminal:
  ```bash
git clone https://github.com/danabrosh/dna-to-protein.git
cd dna-to-protein
pip install -r requirements.txt
python main.py
```

---

This project was created as part of [Basic Programming Skills (Python)](https://github.com/Code-Maven/wis-python-course-2025-03) course at the Weizmann Institute of Science.



