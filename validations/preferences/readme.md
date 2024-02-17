The format of the results of preference-based judgements are as follows:

`<query id> <version> <greater relevance level> <passage id from greater level> <lesser relevance level> <passage id from lesser level> <preference>`

where `<version>` could be either `reg` as regular or `rev` as `reversed` version of the prompt to avois the position bias. Meaning the two passages in the competetion were flipped.

Since we have selected pairs of qrels from diffferent levels of relevance `<greater relevance level>`  shows the more relevant document and `<lesser relevance level>` indicates the level of the passage which has been annotated as less relevant to the query.
