# Agentic or experiencer? The Nonhuman Action in Ecofiction

This is a description of the files used in the work "Agentic or experiencer? The Nonhuman Action in Ecofiction", submitted to the DH2026.

1. `code.zip` includes:
   - `concatenate_all.py`: concatenates BookNLP output files with the extensions `.supersense` and `.tokens`
   - `ecofiction.py`: runs the BookNLP pipeline on the corpus
   - `embedding.py`: calculates cosine similarity between corpus tokens and input agentic and experiencer verbs using Gensim Word2Vec embeddings
   - `expand.py`: outputs agentic and experiencer words from the corpus based on the output of `embedding.py`
   - `human_verbs.py`: outputs sentences where human entities (tokens tagged with `noun.person`) collocate with agentic and experiencer verbs
   - `nonhuman_counts.py`: counts the number of nonhuman living entities (tokens tagged with `noun.animal` and `noun.plant`) per volume (book) in the corpus
   - `nonhuman_verbs.py`: outputs sentences where nonhuman living entities (tokens tagged with `noun.animal` and `noun.plant`) collocate with agentic and experiencer verbs
3. `ecofiction_metadata.csv` includes metadata of the ecofiction corpus (title, author, and publication year)
4. `human_verbs.csv` includes the output of `code.zip/human_verbs.py`.
5. `nonhuman_verbs.csv` includes the output of `code.zip/nonhuman_verbs.py`.
6. `verb-count.pdf` shows Figure 1 in the abstract.
7. `verb-proportion.pdf` shows Figure 2 in the abstract.
