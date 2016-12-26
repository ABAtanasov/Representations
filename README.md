# Representations of the Physical Universe

####An upcoming book



## Prerequisites

### 1) Old Notions Revisited

First draft completed, need to draw up figures. dwabi
OK there's a problem with a^i vs v^i vs \mathbf v_i_ (vs possible e_i_) usage in this chapter. I SHOULD BE USING X^i instead of v^i for vector fields :'( Let's fix that though.

#### The Cartesian Coordinate System
	Begin with an example of a falling ball, the vector for velocity
#### Linear Algebra and Coordinates
	Critical to highlight difference between geometric and algebraic vectors
#### Euclidean vs. Affine Space
	The inner product is not an invariant 
#### Nonlinear Coordinates
	
#### Einstein's Summation Convention
	Make clean and short

#### (MOVED) Views of Multilinear Algebra
#### Exercises

### 2) New Horizons

Close to being done. 

We want a section for defining 
	Direct sums, Dual Spaces <-> functionals, 
	and tensor product both INTUITIVELY and FORMALLY

#### The Manifold
#### Examples of Manifolds
#### Elementary Topology
	Gaps in this section
	Add stereographic projection of sphere as example of coordinate charges
#### Embedded v.s Intrinsic
#### Vectors Reimagined
#### What Follows
#### Exercises


## Part 1: A Better Language

### 3) Differential Geometry

THINGS WE SHOULD HAVE DEFINED EARLIER ON:

	C^\infty(M), That 1/k! on the k-form coefficient tensor

#### The Derivative and the Boundary
#### The 1-Form
#### The Exterior Algebra from the Wedge
#### Stokes' Theorem
#### Distance, a Metric
#### The Hodge Star and the Laplacian
#### Movement: Lie's Ideas
#### Exercises

	Finish Stokes' theorem proof.. idk find a good reference, all the groundwork is there
    Finish some Lie derivative summaries



### 4) Harmonics: Fourier Analysis


#### Discrete, Bounded: Eigenvalues
	Functions are very cleraly n-component tuples forming a vector space
#### Continuous, Bounded: Fourier Series
	Differentiation as a linear operator, finding its eigenvalues gives the fourier transform
#### Continuous, Unbounded: Fourier Transform
#### Harmonic Analysis on Higher Euclidean Space
	Here we derive the Laplacian, study diffusion, image processing, convolution
	Functions on 2D space as a limit of a 2D grid
	Laplacian is never obviously derived in any good text so derive it. 
#### Harmonic Analysis on Graphs
	Functions on graphs, graph laplacian. 
	Motivate expanders
	Conclude with spectral graph theory a la Spielman
#### Exercises		
	What about real-valued exponents: c.f. the positive reals


### 5) Beyond Harmonics: Representation Theory
 
  We begin assuming knowledge of group theory/ intro-level abstract algebra. 
  	Look at finite groups...
		Build analogous results to fourier analysis
	Return to graphs 
		graphs -> quivers?
		Representation theory of k[x] = Jordan Normal Form
	
	Some statements about compact groups/topological groups?


  Begin with spectral graph theory motivating representations as generalizations of eigenvalues

## Part 2: Physics

### 6) SL(2,C), SU(2), SL(2,R)... all of finite dimensional QM basically

  Review how this ties together: rep theory of SO(3) leading to SO(3,1), and spinors (projective representations)
  
  QI section


### 7) Classical Mechanics and Symplectic Geometry

	What is the difference between velocity and momentum 
	Legendre transform
    Feynman Argument for conservation in the Lagrangian viewpoint

    Intuition behind how the symplectic form bundles everything together and lets us go from a hamiltonian to \partial / \partial t -> the arrow of time -> 


### 8) Einstein's Gravity
  
  	Covariant Derivatives. Motivate Riemann Curvature
	
	READ WEYLS BOOK it literally derives GR from symmetry 
	
	And then:
	
	Black holes, let them spin let them be charged. Let there be parallel universe, everything. 
	Penrose diagrams
	
	Expanding universes, redshift, Hubble's thing.. ADM might be too much its ugly af imo (but the preceeding chapter HAS developed the hamiltonian formalism enough)
	
	The cosmological constant: stroke of genius or just a stupid freaking Lambda that Einstein put in.  

## Part 3: More Advanced Topics

### 8) Cohomology and Homology

	Goal is a simple motivation of poincare duality and relating the space of harmonic p-forms to the (co)homology

### 9) An Introduction to Geometric Quantization

  
	The idea should be that even though, physically, we can barely grasp quantization at first glance, the mathematics guides us and we shuold try to interpret THAT physically. 

### 10) Classification of Simple Lie Algebras over C

	You Qi's notes, together with Humphreys will be the guide
	The goal is to introduce, with reasonable proof, the ABCDEFG classification of Lie Algebras
