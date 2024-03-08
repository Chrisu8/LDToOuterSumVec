# From LD Matrix To Outer Sum Vector
Our project is using MPC to find the LD boundaries, this part is used for each local party to convert their LD matrix to the OuterSum vector, which is the first step in our project.
## Introduction
The LD matrix is a fundamental component in genetic studies, representing the linkage disequilibrium between pairs of genetic variants. Converting this matrix to an Outer Sum Vector is the first step that each party get its own locally, and their Outer Sum vector is the imput for our MPC.
## Getting Started
you start to look at the Anti_dig_sum.py first, it is the orginal way that how we find the LD matrix boundaries. refer to the paper https://academic.oup.com/bioinformatics/article/32/2/283/1743626 
our method is using the outer sum of the ld Matirx, please refer to the algorithm.
here we are using the 1000 Genomes phase 1, and we use Chromosome 2 with specfic region as an example.

### Prerequisites

Before you begin, ensure you have the following requirements installed:
- Python 3.6 or newer

### Installation

Clone the repository to your local machine to get started



