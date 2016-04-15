# Surface

Surface lets you put a UI on anything in your Clojure runtime. You can quickly compose a UI to interact with your existing data and systems, and push it to a web client. A simple syncronization model based on Om Next maps UI actions back to user code, and state updates back to the client. 

Surface is ideally suited for creating quick-and-dirty interfaces to support interactive development and computation. It trades off serveral factors that are desirable for consumer-facing webapps, such as latency and server resources, in favor of maximal power and flexibility for the developer. 

Existing technologies that try to provide a similar value (notebooks, dashboards) are complicated, and don't solve the core problem that Surface does: how to put a UI around any data, function, or process. This leads to technical limitations and incidental complexity as use cases extend beyond those originally designed. 



