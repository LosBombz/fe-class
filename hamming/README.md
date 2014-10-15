Hey guys, I’d like to try something a little different as part of front-end class. Usually, we talk about some high level programming, and where it might apply in your code, but we don’t really get into real implementations with tangible results. I’d like to change that with a little challenge to be put out on Monday, and then we’ll go over some possible solutions and approaches on Wednesday. Obviously, you should not do any work on this challenge problem while you have client work but if you have a bit of spare time these challenges may take from 15 minutes to an hour. Participation is completely optional, but may be a good opportunity to get your hands dirty writing some JS. Now for this week’s challenge:

#Hamming Distance
Difficulty: 2/5

In the field of genetics, a mutation is an mistake that gets made when creating or copying DNA. The most common type of mutation is called a ‘point mutation’ where the wrong nucleotide gets put in place in a single spot. By comparing two strands of DNA and counting how many places are different, we can get an idea of the minimum number of mutations to get from one species to another. This is known as the ‘Hamming distance’ between two strands of DNA. 

Example:
GAGCCTACTAACGGGAT
CATCGTAATGACGGCCT
^ ^ ^  ^ ^    ^^
The Hamming distance between the two above sequences is 7.

Your task is to write a function that will calculate the difference between two passed DNA sequences.

##What to do

Your goal is to make all the tests in a test suite pass. The suite is contained for this project in hamming_test.spec.js. You’ll see a bunch of it() and xit() functions. When you run the test spec, it will run all the it() functions and skip over all the xit() functions. As you get your tests to pass, just remove the ‘x’ to start running the next test. For more information on the tests, see http://jasmine.github.io/1.3/introduction.html.
To get started, you’ll need to install the test runner by typing npm install –g jasmine-node into your terminal. Next you’ll need to download the attached zip file, unzip it, and navigate to the new folder in your terminal. Finally, you can run jasmine-node . To run the test suite. 

If you feel comfortable, and would like critique of your solution, feel free to send me your solution to this problem, and we can take a look at your solution. If not, that’s totally fine, it’s just a fun little exercise to help learn and apply some JS skill.

Problem taken from http://rosalind.info/problems/hamm/