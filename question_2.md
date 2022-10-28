# Student 2's Answer to Question 2

**Q2.** Assign variables to the individual components of your favorite gene! (e.g.
promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3' UTR). Print the entire gene
by using the string concatenation operator, on the standard output! Note: Feel free to create a
fictional gene sequence by randomly filling in the gene components by the characters
corresponding to individual nucleotide bases.

´´´
promoter = "TAAAGCCAAATTT"
5_prime_UTR = "GGGTAACCTTGA"
start_codon = "ATG"
exon1 = "ATCCGGAATCCAATGC"
intron = "ATGGCCAAGGGTTAAA"
exon2 = "AAATGGCCAGTACG"
stop_codon = "TAG"
3_prime_UTR = "AATTTGGGAACCAGTA"

my_fav_gene = promoter + 5_prime_UTR + start_codon + exon1 + \
              intron + exon2 + stop_codon + 3_prime_UTR

print("My favoruite gene sequence is as follows:")
print(my_fav_gene)
´´´
