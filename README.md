
### WORK DONE SO FAR: 

- Studied the Jaeger cpp client, deployed HOTROD application present in Go language and see how tracing is done, in
  jaeger UI.
- Made a simple hello world instrumentation code using Jaeger-cpp-client (https://github.com/dexter816/jaeger-hello-world)  
- Studied the project related resources present

      -  talk-https://www.youtube.com/watch?v=NHoI9F9bZeM   
      -  proposal-https://github.com/BU-NU-CLOUD-SP18/Ceph-Tracing 
      -  blog-https://superuser.openstack.org/articles/end-to-end-tracing-with-ceph-and-jaeger/  
      -  research paper and other projects with similar problem statement such as _opencensus-jaeger
         instrumentation_. 
         
- Studied, modified and worked on how modular configuration jaeger provides with the examples
  present in opentracing and jaeger client( will do the web socket instrumentation to deepen this
  understanding.) 
  
- Took inspiration and worked out the distributed tracing example
  https://github.com/dexter816/distributed-tracing-example/tree/master/src/dist_tracing 
  
- Currently working on instrumenting a branch of Ceph, along with studying how tracing endpoints
  are employed using bilkn with lttng tracing in ceph.

### WILL DO BEFORE THE PROJECT BEGINS: 

- How when Openstack is deployed in ceph the tracing is done using blkin, lttng and debugging.

- Study( started ) Mania and Ali’s work and trace endpoints replaced so far, discuss the bottlenecks such as how tracing
  can interfere with core functions of Ceph and try look for some solutions with the team.
  https://github.com/alimaredia/ceph/commit/43a86d6ce6d58342ad9ccd3a8a36a6544cb8bb

### RELEVANT PROJECTS
- Ceph Proposal https://github.com/dexter816/Ceph_Proposal

- Local Developments currently working on: https://github.com/dexter816/ceph (will add code for review in ceph proposal)

- Example code demonstrating tracing in ceph https://github.com/dexter816/distributed-tracing-example

- Jaeger Android Client (underprogress) https://github.com/dexter816/jaeger-opentracing-android
