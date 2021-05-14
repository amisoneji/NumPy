# NumPy:

- It is a package for python programming language and simplify operations on multi-dimensional arrays.
	
	  like mean,mode,std,var,cov,dotproduct,comparision etc.

- It was introduced (by Travis Oliphant) in  2005 and distributed as open source library.

	
**Difference  between list and numpy array**
 

	             list		                                                     numpy array
___________________________________________________________________________________________________________________________
	     
       Any type of values(heterogeneous)		                       Similer type of values (homogeneous)  
	                                                                                                                                  
       Resizable	                                                       Immutable in size

       Less function	                                               huge library
	
       Does not supports broadcasting                                      Support broadcasting
                                                             
       Does not store actual elements	                               It stortes actual elements
		
  

**Numpy Array Creation:**

   1.a=np.array(seq)

   2.a=np.arange(start,stop,step)

   3.a=np.zeros(size)

   4.a=np.ones(size)

   5.a=np.empty(size)	#generate random float or based on type

   6.a=np.linspace(low,high,num)

   7.a=np.full(size,initial_value)

   8.a=np.random.random(size) 	#generate random float 

   9.a=np.random.randint(low,high,size)

   10.a=np.random.uniform(low,high,size)

   Note:each numpy array is represented by an object of ndarray class.


**ndarray.ndim:**

   The number of dimensions of the array.

**ndarray.shape:**

   This is a tuple of integers indicating the size of the array in each dimension. For a matrix with n rows and m columns, shape will be (n,m).

**ndarray.size:**

   The total number of elements of the array.

**ndarray.dtype:**

   An object describing the type of the elements in the array. 
	 we may specify standard Python types or NumPy types


**Commonly used numpy functions/array methods:**
_______________________________________________________________________________________________________________________________________

   1.  np.min(a)

   2.  np.max(a)

   3.  np.argmax(a)

   4.  np.argmin(a)
   
   5.  np.sort(a) #copy
   
   6.  np.sqrt(a)	& np.square(a)
   
   7.  np.log(a) #natural log(base e)
   
   8.  np.log10(a)
   
   9.  np.exp(a)
   
   10. np.unique(a)
   
   11. np.bincount(a)
   
   12. Arithmetic:
	    a3=a1+a2
	    
      a3=a1-a2
	    
      a3=a1*a2
	    
      a3=a1/a2
   
   13. np.std(a)
   
   14. np.var(a)
   
   15. np.cov(a)
   
   16. a.reshape()
   
   17. a.resize()
   
   18. a.dot(b) #matrix multiplication
   
   19. a @ b #matrix multiplication(from 3.5)
   
   20. a.T	#transpose
   
   21. np.sum(a)
   
   22. np.loadtxt(path)
   
   23. np.savetxt(path)
   
   24. np.hstack(a1,a2,...)
   
   25. np.vstack(a1,a2,...)
   
   26. a.flatten()


