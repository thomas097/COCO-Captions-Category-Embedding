# COCO Captions Category Embedding

An attempt to model a semantic space as described in ```Derrac, J., & Schockaert, S. (2014, August). Characterising Semantic Relatedness using Interpretable Directions in Conceptual Spaces. In ECAI (pp. 243-248).```

As opposed to Schockaert's approach to modelling semantic spaces using reviews and Flickr descriptions, the current method uses sentence-wide context windows of contexts/captions from the COCO data set to model the similarity of common object categories (that is, modelling common objects in a distributional model / vector space model). The final aim is to model real-world environments (living room, outdoor, etc.) as convex regions in the semantic space such that environments can be identified by means of the objects that occur in them (e.g. a "living room" being the region that encompass the vectors "tv", "couch", "table", "rug", etc.). 
