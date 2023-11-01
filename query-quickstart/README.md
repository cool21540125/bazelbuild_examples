Query Quickstart
----------------

This project runs you through a set of basic queries you can use to learn more about your project's file dependencies. It is intended for new Bazel developers with a basic knowledge of how Bazel and `BUILD` files work.

Read the [Bazel quickstart](https://bazel.build/query/quickstart) tutorial to follow along.

# [Query quickstart](https://bazel.build/query/quickstart)

```bash

bazel query --noimplicit_deps "deps(:runner)"


### gen graph
bazel query --noimplicit_deps 'deps(:runner)' --output graph > graph.in
dot -Tpng < graph.in > graph.png
# 不過我倒覺得貼 Web 比較方便
bazel query --noimplicit_deps 'deps(:runner)' --output graph
# http://www.webgraphviz.com/


### 
```
