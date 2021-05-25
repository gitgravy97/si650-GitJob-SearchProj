# si650-GitJob-SearchProj
Final Project for Info Retrieval // Search Eng., attempt at building job search system

## Repo Map

- Most importantly, our end-product script is in the included `jobs-engine.zip` file, with its own ReadMe regarding script usage. This zip also contains the necessary data for using the ipynb files described below.
- `docs` contains final paper and a results spreadsheet breaking down performance by mean-average precision per parameter combination fed into ranking algorithm
- `NERS_Gen.ipynb` Generates and outputs custom entity-recognition model
- `GroundTruth_Eval.ipynb` facillitates performance evaluation for relevance / ranking algorithm relative to subset human-annotated for different queries
- `BM25_FullData.ipynb` is the notebook form of our end-product providing search functionality

## Rebuild Considerations

- Due to inexperience with IR systems, errors were made regarding underspecific queries used for manual annotation. Redo annotation process with greater emphasis on intended filter affordances.
- Design a proper front-end for testing/deployability
- Retain the BM25 approach at first and focus on prefiltering affordances
- Expand NERS training data, possibly build a UI so less technnical individuals could assist (potential side project)