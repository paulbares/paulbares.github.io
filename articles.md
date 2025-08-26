---
layout: post
title: List of articles
---

### Algorithm
* [https://sortingsearching.com](https://sortingsearching.com) tags{sort,search}
* [https://github.com/labuladong/fucking-algorithm/tree/english](https://github.com/labuladong/fucking-algorithm/tree/english) tags{interview,algorithm}
* [https://jolynch.github.io/posts/use_fast_data_algorithms/](https://jolynch.github.io/posts/use_fast_data_algorithms/) tags{compression,hashing,encryption}
* [Use Fast Data Algorithms](https://jolynch.github.io/posts/use_fast_data_algorithms/) tags{compression,hashing}

### Database
* [https://research.google/pubs/pub48030/](https://research.google/pubs/pub48030/) tags{google,key-value,distributed}
* [http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.674.248&rep=rep1&type=pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.674.248&rep=rep1&type=pdf) tags{index,hashtable,radix,tree}

### Data
* [https://ananasanalytics.com/](https://ananasanalytics.com/) tags{analytics}

### Framework
* [https://www.stemlaur.com/blog/2021/03/30/tech-hibern-hate/](https://www.stemlaur.com/blog/2021/03/30/tech-hibern-hate/) tags{hibernate,jpa,java}

### GitHub
* [https://github.com/wrandelshofer/FastDoubleParser](https://github.com/wrandelshofer/FastDoubleParser) tags{parser,java}

### Interview 
* [https://yangshun.github.io/tech-interview-handbook/](https://yangshun.github.io/tech-interview-handbook/) tags{interview,algorithm,exercise}
* [https://www.amazon.jobs/en/principles](https://www.amazon.jobs/en/principles) tags{interview,aws,amazon}
* [Reverse interview](https://github.com/viraptor/reverse-interview) tags{interview}

### Job
* [https://haseebq.com/my-ten-rules-for-negotiating-a-job-offer/](https://haseebq.com/my-ten-rules-for-negotiating-a-job-offer/) tags{negotiation,job}

### Linux
* [https://lwn.net/Articles/lsfmm2019/](https://lwn.net/Articles/lsfmm2019/) tags{filesystem,memory}

### Misc.
* Task queue:
  * [https://slack.engineering/scaling-slacks-job-queue-687222e9d100](https://slack.engineering/scaling-slacks-job-queue-687222e9d100) tags{redis,kafka}
  * [https://redis.io/commands/rpoplpush](https://redis.io/commands/rpoplpush) tags{redis}
    > ...queue is not reliable as messages can be lost, for example in the case there is a network problem or if the consumer crashes just after the message is received but it is still to process.
RPOPLPUSH (or BRPOPLPUSH for the blocking variant) offers a way to avoid this problem: the consumer fetches the message and at the same time pushes it into a processing list. 
* [https://bits.houmus.org/2020-02-02/this-goes-to-eleven-pt5](https://bits.houmus.org/2020-02-02/this-goes-to-eleven-pt5) tags{simd}
* [http://web.eecs.utk.edu/~azh/blog/challengingprojects.html](http://web.eecs.utk.edu/~azh/blog/challengingprojects.html) tags{programming,project,training}
* [https://mechanical-sympathy.blogspot.com/2011/07/memory-barriersfences.html](https://mechanical-sympathy.blogspot.com/2011/07/memory-barriersfences.html) tags{memory,cpu,cache}

### Optimization
* [https://www.infoq.com/articles/making-code-faster-taming-branches/](https://www.infoq.com/articles/making-code-faster-taming-branches/) tags{cpu,branch}
* [Why is processing a sorted array faster than processing an unsorted array?](https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array) tags{cpu,branch,predication}

### Profiling

* [https://mostlynerdless.de/blog/2023/03/27/writing-a-profiler-in-240-lines-of-pure-java/](https://mostlynerdless.de/blog/2023/03/27/writing-a-profiler-in-240-lines-of-pure-java/) tags{profiler,java,safepoint}

### Rust
* [https://rust-unofficial.github.io/too-many-lists/](https://rust-unofficial.github.io/too-many-lists/) tags{rust,exercise,training}
* The Rustonomicon, advanced rust concepts: [https://doc.rust-lang.org/nomicon/index.html](https://doc.rust-lang.org/nomicon/index.html) tags{rust}
* [Rust cookbook](https://rust-lang-nursery.github.io/rust-cookbook/) tags{rust}

### Security
* [https://youtu.be/996OiexHze0](https://youtu.be/996OiexHze0) tags{ouath2,authentication code flow,okta}
* [https://www.paepper.com/blog/posts/how-to-properly-manage-ssh-keys-for-server-access/](https://www.paepper.com/blog/posts/how-to-properly-manage-ssh-keys-for-server-access/) tags{ssh}
* [https://www.root-me.org/?lang=en](https://www.root-me.org/?lang=en) tags{challenge,ctf}
* [https://twitter.com/N26Careers/status/1085098091273994240?s=20](https://twitter.com/N26Careers/status/1085098091273994240?s=20) tags{n26,ctf,career}]
* [https://tldp.org/HOWTO/SSL-Certificates-HOWTO/x64.html](https://tldp.org/HOWTO/SSL-Certificates-HOWTO/x64.html) tags{ssl,tls}

### Software development
* [https://www.csc.gov.sg/articles/how-to-build-good-software](https://www.csc.gov.sg/articles/how-to-build-good-software) tags{best practice,productivity,knowledge,support}
* [https://roadmap.sh/guides/levels-of-seniority](https://roadmap.sh/guides/levels-of-seniority) tags{seniority}
* [https://embeddedartistry.com/blog/2018/04/26/embedded-rules-of-thumb/](https://embeddedartistry.com/blog/2018/04/26/embedded-rules-of-thumb/) tags{rules}
* [https://www.mrlacey.com/2020/07/youve-only-added-two-lines-why-did-that.html](https://www.mrlacey.com/2020/07/youve-only-added-two-lines-why-did-that.html) tags{bug,fix}

### System design
* [https://github.com/ByteByteGoHq/system-design-101](https://github.com/ByteByteGoHq/system-design-101) tags{system}

### Testing
```
This really is a concept that you need to keep in mind when you write your code "testability". And i find that when you get this you also get a Buch of other properties for "free". Orthogonality and reusability for example. And really it's a force multiplier and kicks productivity into high gear when you know that your lower level components work as expected and you don't have to go ok a wilf goose hunt when something would be constantly broken. To summarize I find that writing tests early on reduce product velocity but the compound effect of good quality and regression prevention give you higher velocity later on.
```
* [https://software.rajivprab.com/2019/04/28/rethinking-software-testing-perspectives-from-the-world-of-hardware/](https://software.rajivprab.com/2019/04/28/rethinking-software-testing-perspectives-from-the-world-of-hardware/) tags{test}
