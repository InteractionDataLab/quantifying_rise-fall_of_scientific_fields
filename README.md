# quantifying_rise-fall_of_scientific_fields
Processed dataset extracted for the paper "Quantifying the rise and fall of scientific fields" (https://arxiv.org/abs/2107.03749)

Files information - 

fullArxivWithOrcidAndCitations.csv - contains for every article it's :

  "id" - arXiv id 
  "categories" - arXiv field tags used in the article
  "doi" - journal doi of the article if published
  "created" - date of submission to arXiv
  "authors" - last name of authors 
  "authors_orcid" - ORCID id's of authors wherever possible 
  "NumCitationsArxiv" - number of arXiv articles that cite the given article 
  "NumReferencesArxiv" - number of arXiv articles that the given article cites

internal-citations.json - citation network of arXiv articles citing other arXiv articles. 
