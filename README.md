# CSI-find-the-suspect
A program that finds and matches a DNA of a suspect
<hr>
Build a CSI forensics program

The famous CSI just asked you to create a forensics program for them. Exciting, right! :)

But first, they have to teach you a bit about our DNA...
<hr>

<b>DNA crash course</b>

<p>If we look deeply how our body works, it seems like a big computer. Our body cells are like programs - each of them does their own task. Each cell in our body includes DNA where our "code of life" is written. Everything about us is written here: how we look, what eye color we have, how tall are we etc. Of course part of what we are is shaped through our education and life experience, but DNA is responsible for a big chunk of what we are.</p>

<p>The language understood by computers is a binary or machine code (zeros and ones). If we write a computer program in Python, it eventually gets translated into zeros and ones (machine code), so computer knows how to run and execute commands written in the program.</p>

<p>Binary/machine code looks like this:</p>

<p background-color: grey>100011 00011 01000 00000 00001 000100</p>

<p>But language of our DNA code is not in a form of 0s and 1s - it's instead in the form of four letters: A, C, T and G. These letters represent 4 nucleobases: adenine (A), cytosine (C), guanine (G) and thymine (T). So DNA can be written like this:</p>

<p background-color: grey>ACTGCTGCATAGTCTGCAAGACTGAATCACTACGTATCG</p>

<p>This is as much biology as needed to finish this exercise. It's enough to understand that our DNA can be written in a single string made of four letters: A, C, G and T. In this DNA code we can find genes that define our personal characteristics (hair color, eye color, height etc.).</p>

<b>Crime!</b>

<p>There has been a hideous crime! A full container of ice cream was stored in the SmartNinja fridge - and now it's completely empty. But the criminal made a fatal mistake. S/he left a spoon inside the container and with a spoon also his/her DNA. A perfect case for our CSI investigators!</p>


<p>CSI lab successfully extracted the DNA and wrote it in the ACTG code format. The only thing needed now is a program that would match that DNA with the suspects DNA and find the criminal.</p>>

<p>Here's the DNA text:
<br>ACAAGATGCCATTGTCCCCCGGCCTCCTGCTGCTGCTGCTCTCCGGGGCCACGGCCACCGCTGCCCTGCCCCTGGAGGGTGGCCCCACCGGCCGAGACAGCGAGCATATGCAGGAAGCGGCAGGAATAAGGAAAAGCAGCCTCCTGACTTTCCTCGCTTGGTGGTTTGAGTGGACCTCCCAGGCCAGTGCCGGGCCCCTCATAGGAGAGGAAGCTCGGGAGGTGGCCAGGCGGCAGGAAGGCGCACCCCCCCAGCAATCCGCGCGCCGGGACAGAATGCCCTGCAGGAACTTCTTCTGGAAGACCTTCTCCTCCTGCAAATAAAACCTCACCCATGAATGCTCACGCAAGTTTAATTACAGACCTGAA 
<br>
</p>
<p>Like we said there are genes hidden in our DNA that define our personal characteristics. The CSI lab got us the following gene sequences for some of the human characteristics:</p>

<em>Hair color:</em>

Black: CCAGCAATCGC
Brown: GCCAGTGCCG
Blonde: TTAGCTATCGC

<em>Facial shape:</em>

Square: GCCACGG
Round: ACCACAA
Oval: AGGCCTCA

<em>Eye color:</em>

Blue: TTGTGGTGGC
Green: GGGAGGTGGC
Brown: AAGTAGTGAC

<em>Gender:</em>

Female: TGAAGGACCTTC
Male: TGCAGGAACTTC

<em>Race:</em>

White: AAAACCTCA
Black: CGACTACAG
Asian: CGCGGGCCG

<p>Please note that these are not real gene sequences and the "DNA" in the file is not a real DNA. It's way too short ;)</p>


<b>Suspects characteristics:</b>

<em>Eva:</em>

Gender: Female
Race: White
Hair color: Blonde
Eye color: Blue
Face shape: Oval

<em>Larisa:</em>

Gender: Female
Race: White
Hair color: Brown
Eye color: Brown
Face shape: Oval

<em>Matej:</em>

Gender: Male
Race: White
Hair color: Black
Eye color: Blue
Face shape: Oval

<em>Miha:</em>

Gender: Male
Race: White
Hair color: Brown
Eye color: Green
Face shape: Square
