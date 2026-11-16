# Learning to Denoise: What Makes a DDPM Generate Good Images?

**Claim (DRAFT):** We claim that a DDPM trained once with T=1000 on Fashion-MNIST can be sampled with only 50 respaced 
steps while keeping FID within 10% of full 1,000-step sampling, and we will test it against the full 1,000-step sampler of the same trained model on Fashion-MNIST.
