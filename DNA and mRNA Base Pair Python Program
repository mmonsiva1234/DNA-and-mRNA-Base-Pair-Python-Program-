def dna_to_mrna(sequence):
    mrna_list = []
    sequence_list = list(sequence)
    for dna_nucleotide in sequence_list: 
        if dna_nucleotide == 'G':
            mrna_list.append('C')
        if dna_nucleotide == 'T':
            mrna_list.append('A')
        if dna_nucleotide == 'A':
            mrna_list.append('U')
        if dna_nucleotide == 'C':
            mrna_list.append('G')
        
    return mrna_list

def mrna_to_dna(sequence):
    dna_list = []
    sequence_list2 = list(sequence)
    for mrna_nucleotide in sequence_list2:
        if mrna_nucleotide == 'C':
            dna_list.append('G')
        if mrna_nucleotide =='U':
            dna_list.append('A')
        if mrna_nucleotide == 'G':
            dna_list.append('C')
        if mrna_nucleotide == 'A':
            dna_list.append('T')
        
    return dna_list 

while True: 
    
    choice = input("Do you want to transcribe or retrotranscribe, type t for transcribe and r for retrotranscribe?")
    sequence = input('Type in the sequence here:').upper()
    
    if choice ==  't':
        print(dna_to_mrna(sequence))
        rerun = input("Would you like to type in another sequence?")
        if rerun == 'yes': 
            continue 
        if rerun == 'no':
            print('Thank you, see you next time')
            break

    if choice == 'r':
        print(mrna_to_dna(sequence))
        rerun = input("Would you like to type in another sequence?")
        if rerun == 'yes': 
            continue 
        if rerun == 'no':
            print('Thank you, see you next time')
            break
