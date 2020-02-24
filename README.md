# Variational Inference for the IBP posterior

The VI implementation is based from [Doshi-Velez et al](http://ai.stanford.edu/~tadayuki/papers/doshivelez-miller-vangael-teh-tech-report09.pdf) 2009. 

The notebooks contains an implementation of matrix factorisation using the IBP prior over latent features in the dictionary. The implementation contains finite approximations based on a Beta-Bernoulli model from [Griffiths and Ghahramani](http://www.jmlr.org/papers/v12/griffiths11a.html) in `ibp_vi.ipynb` and a finite stick-breaking contruction from [Teh et al](http://proceedings.mlr.press/v2/teh07a.html) in the notebook `ibp_vi_sb.ipynb`.
