## Module Description
Calculate eigenvalues, eigenvectors, or RREF(Reduced Row Echelon Form) from a 2D array (matrix)  
Status: Abandoned  
License: ISC  

## How to use
    npm install @ahmaddynugroho/eig

## Functions
#### 1. eig(matrix)
description: calculate eigenvalues and eigenvector of a 2D array(matrix)  
parameter: 2D array of number  
return: object = { eigval: [], eigvec: [] }  
note: eigenvector corresponding to eigenvalues with the same index  

#### 2. eigval(matrix)
description: calculate eigenvalues from a 2D array(matrix)  
parameter: 2D array of number  
return: array = []  

#### 3. rref(matrix)
description: calculate Reduced Row Echelon Form(RREF) from a 2D array(matrix)  
parameter: 2D array of number  
return: array = []  

## Examples
    const eig = require('@ahmaddynugroho/eig')  
    
    let A = [[7, 3], [3, -1]]  
    let B = [[5, -6], [-3, 2]]  
    const C = [[1, 2, 3],   
               [4, 5, 6],   
               [7, 4, 9]]  
     
    console.log(eig.eig(A))  
    console.log(eig.eig(B))  
    console.log(eig.eig(C))  