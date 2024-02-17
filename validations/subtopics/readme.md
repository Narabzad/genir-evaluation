The `extracted subtopics` include all the generated subtopics for queries in Trec dl 2019 and 2020 in xml format.
For instance here are the 5 subtopics extracted for the query "do goldfish grow": 

`<query id="156493" text="do goldfish grow">

<topic number="156493" type="faceted">
  
<subtopic number="1" type="inf"> What is the average size of a fully grown goldfish? </subtopic>

<subtopic number="2" type="inf"> How long does it take for a goldfish to reach its full size? </subtopic>

<subtopic number="3" type="inf"> What factors can affect the growth of a goldfish? </subtopic>

<subtopic number="4" type="inf"> Are there any specific care requirements to promote the growth of goldfish? </subtopic>

<subtopic number="5" type="inf"> Can goldfish continue to grow throughout their lifespan? </subtopic>

</topic></query>`

And for every document in the relevance judgements (qrels) we have judged all the subtopics as if they were satisfied (answered) or not. 
Therefore, the files in `quantified` subtopics have the following format:

`<query id> <passage id> 0 <yes or no> 1 <yes or no> 2 <yes or no> `

We not that subtopic 0 is the query itself and subtopic 1 onwards are the extracted subtopics.
