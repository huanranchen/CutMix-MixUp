# CutMix
a pytorch implement of cutmix, which solve some problem on original cutmix



the original cutmix re-calculate the prob if the bbox is out of range. I use some trick to solve this problem.


And, I use KL divergence instead of linear combination of 2 cross entropy loss.
