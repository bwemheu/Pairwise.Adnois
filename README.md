# Pairwise.Adonis (under construction)
R package to calculate pairwise comparisions using the adonis function in vegan (under development)


Command
pairwise.adonis(d, v, p.adjust.m = "BH")
  d = distance matrix/matrix with dissimilarities (e.g. Bray-Curtis/Unifrac)
  v = factorial parameter (with at least three factors; will run with two)
  p.adjust.m = How should the P value be adjusted for multiple testing (default: BH; see p.adjust in R for details)
