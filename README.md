model        : θ → (χ → ψ)   
loss         : ψ → ψ → ℓ  
optimization : (θ → (χ → ψ)) → (ψ → ψ → ℓ) → [(χ, ψ)] → θ  
inference    : (θ → (χ → ψ)) → θ → χ → ψ  