 # description   
    
    In a new DEEPLEARNING.AI short course “Efficiently Serving Large Language Models”, 
    you’ll pop the hood on large language model inference servers. 

    

    What You Will Learn:

    - how to increase the performance and efficiency of your LLM-powered applications
    - how to generate text, chunk documents, and extract relevant info based on input prompts
    - how to cache computations inside the transformer network inference, in order to make this process efficient
    - what is the time to first token, how to lower inference time (time it takes user to receive the response on a user prompt) 
    - what’s throughput (rate at which server processes user requests) of your application, 
    - how to select the vendor to serve your custom built and tuned LLM model
    - how to serve multiple LLMs with multiple user requests, coordinate and extract relevant answers
    - what is at the core of efficient LLMs serving
    - how vectorization enables serving multiple requests in a single operation, or multiple requests at the same time
    - what is KV Caching technique- how is common attention data for every token kept in memory, and not recalculated over and over again for each token 
    - how KV Caching leads to big reduction in latency for every subsequent token after the first one
    - how to batch prompts in a single tensor, so LLM can process multiple inputs at the same time
    - how continuous batching dynamically updates the batch as the new request comes in, and old request completes 
    => continuous batching is at the foundation for Predibase to serve multiple tenants at the same time or multiple request at once by reducing latency and increasing throughput
    - how to implement quantization of a model to lower its memory footprint, by lowering precision to INT4
    - how LORA fine-tuning technique enables specialized adapters to be dynamically loaded at runtime to lower latency and boost throughput of a LLM
    - how to combine continuous batching and LORA  to achieve serving multiple customers (LoRAX,  and Multi-LoRA inference)
    - how to improve performance of user’s LLM application by using above internal details of inference implementations

    https://predibase.com/lora-land
    https://predibase.com/blog
    https://github.com/predibase/lorax

    Enroll today  https://learn.deeplearning.ai/courses/efficiently-serving-llms

