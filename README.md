# llm-auto-memory-manager

- llms have limited context but we can give them infinite? memory
- idea is we keep track of all the memory in an index of sorts of all the tasks progress, structures and other subtree of similar indexes, the llm has can choose which tree it wants to access by usign tools and then going in depth for that task to gain relevant context without pollution main context
- can be also use to orchestrate multiple agent swarm by having a "memory-manager" agent whose sole task is to update the memory tree
- analogous to many real world systems