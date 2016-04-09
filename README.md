# distributed-system-learning-resources
A collection of good learning resources in distributed system, big data, and cloud computing areas

#### Distributed Systems Tutorials / Courses / Projects

- MIT :
[Distributed systems (with Go), Spring 2016 version](https://pdos.csail.mit.edu/6.824/), including 4 great course projects : MapReduce, Raft, and two key/value store.

- Brown University : 
[Distributed systems (with Go)](http://cs.brown.edu/courses/cs138/s15/syllabus.html)
good projects for building Chord, Tapestry, Raft, PuddleStore

- CMU : 
There are couple of versions of distributed system courses. I'll only recommend the Go versions. Personally my favoriate is [Fall15 version](http://www.cs.cmu.edu/~srini/15-440/assignments.html) and its [github](https://github.com/cmu440-F15),
it extends the [original version taught by David, Anderson](https://www.cs.cmu.edu/~dga/15-440/S14/assignments.html), and replace the last "Design your own distributed system" project with 
a "Paxos" project. Alternatively, you can try the latest [Spring16 version](http://www.cs.cmu.edu/~15-440/)


#### Articles, Papers, Books
- [Log, what every engineer should know ..](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)
this is a very good article written by LinkedIn's principal engineer, the lead of Kalfka and Samza.

- [Big Data: Principles and best practices of scalable realtime data systems](http://www.amazon.com/Big-Data-Principles-practices-scalable/dp/1617290343).
This is a really well-written book, by the creator of Apache Storm.  As this was a little bit old (as far as I know it was created in 2012 and published in 2015), 
some chapters about specific tools can be skipped.

- [Spark paper, nsdi12](https://www.usenix.org/system/files/conference/nsdi12/nsdi12-final138.pdf) : This is a paper everybody can understand. Interestingly, there is a source code of 
[the first version of Spark](https://github.com/apache/spark/commit/df29d0ea4c8b7137fdd1844219c7d489e3b0d9c9), including only thousands of lines of Scala code.

#### Misc

- [500 lines or less](https://github.com/aosabook/500lines), this is a good collections of short projects written by domain experts. It includes couple of DB examples, 
and a [Paxos example with Python](https://github.com/aosabook/500lines/blob/master/cluster/cluster.markdown).
