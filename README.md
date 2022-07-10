# CutMix

For CutMix:


a pytorch implement of cutmix, which solve some problem on original cutmix



the original cutmix re-calculate the prob if the bbox is out of range. I use some trick to solve this problem.


And, I use KL divergence instead of linear combination of 2 cross entropy loss.


And, thanks for YUQS, who told me that using clone when assigning value to other variable instead of clone at the beginning of the function. This can improve efficiency and save memory.


For MixUp:

implement with my style.(KL div)
