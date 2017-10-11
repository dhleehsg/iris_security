# iris_security
Iris security code for paper 'Cancelable Iris Biometrics Using Noise Embedding' submitted to IEEE TIFS.

# abstract

This paper presents a cancelable biometric (CB) scheme for iris 
recognition system. 
The CB approaches are roughly classified into two categories
depending on whether
the method stresses more on non-invertibility or on discriminability.
The former is to use non-invertibly transformed data for the
recognition instead of the original, so that the impostors cannot
retrieve the original data from the transformed data. The latter 
is to use a salting method that mixes random signals generated 
by user-specific keys so that the imposters cannot retrieve the original 
data without the key.
The proposed cancelable iris biometrics (CIB) can be considered
a combination of these methods, which applies 
a non-invertible transform to the salted data.
We use the reduced random permutation and binary salting (RRP-BS) 
method as the biometric salting, and use the Hadamard product 
for enhancing the non-invertibility of salted data.
Moreover, to overcome the shortcomings of the conventional salting method, we 
generate several templates for an input and define non-coherent and coherent matching
regions among these templates, and show that salting the non-coherent matching regions is less
influential on the overall performance.
Specifically, embedding the noise in this region does not affect 
the performance, while making the data difficult to be inverted to the 
original. For the evaluation, we use three datasets,
namely CASIA V3 iris-interval, IIT Delhi iris, and ND-Iris-0405. 
The extensive evaluations show that the proposed algorithm has low error 
rates and good intra/inter classification performances,
which is better or comparable to the existing methods.
Moreover, the security analysis ensures that the proposed 
algorithm satisfies non-invertibility and unlinkability, and is robust against 
several attacks as well.
