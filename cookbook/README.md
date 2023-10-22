# LangChain cookbook

Example code for building applications with LangChain, with an emphasis on more applied and end-to-end examples than contained in the [main documentation](https://python.langchain.com).

Notebook | Description
:- | :-
[LLaMA2_sql_chat.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/LLaMA2_sql_chat.ipynb) | Build a chat application that interacts with a sql database using an open source llm (llama2), specifically demonstrated on a sqlite database containing nba rosters.
[Semi_Structured_RAG.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/Semi_Structured_RAG.ipynb) | Perform retrieval-augmented generation (rag) on documents with semi-structured data, including text and tables, using unstructured for parsing, multi-vector retriever for storing, and lcel for implementing chains.
[Semi_structured_and_multi_moda...](https://github.com/langchain-ai/langchain/tree/master/cookbook/Semi_structured_and_multi_modal_RAG.ipynb) | Perform retrieval-augmented generation (rag) on documents with semi-structured data and images, using unstructured for parsing, multi-vector retriever for storage and retrieval, and lcel for implementing chains.
[Semi_structured_multi_modal_RA...](https://github.com/langchain-ai/langchain/tree/master/cookbook/Semi_structured_multi_modal_RAG_LLaMA2.ipynb) | Perform retrieval-augmented generation (rag) on documents with semi-structured data and images, using various tools and methods such as unstructured for parsing, multi-vector retriever for storing, lcel for implementing chains, and open source language models like llama2, llava, and gpt4all.
[autogpt/autogpt.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/autogpt/autogpt.ipynb) | Implement autogpt, a language model, with langchain primitives such as llms, prompttemplates, vectorstores, embeddings, and tools.
[autogpt/marathon_times.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/autogpt/marathon_times.ipynb) | Implement autogpt for finding winning marathon times.
[baby_agi.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/baby_agi.ipynb) | Implement babyagi, an ai agent that can generate and execute tasks based on a given objective, with the flexibility to swap out specific vectorstores/model providers.
[baby_agi_with_agent.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/baby_agi_with_agent.ipynb) | Swap out the execution chain in the babyagi notebook with an agent that has access to tools, aiming to obtain more reliable information.
[camel_role_playing.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/camel_role_playing.ipynb) | Implement the camel framework for creating autonomous cooperative agents in large scale language models, using role-playing and inception prompting to guide chat agents towards task completion.
[causal_program_aided_language_...](https://github.com/langchain-ai/langchain/tree/master/cookbook/causal_program_aided_language_model.ipynb) | Implement the causal program-aided language (cpal) chain, which improves upon the program-aided language (pal) by incorporating causal structure to prevent hallucination in language models, particularly when dealing with complex narratives and math problems with nested dependencies.
[code-analysis-deeplake.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/code-analysis-deeplake.ipynb) | Analyze its own code base with the help of gpt and activeloop's deep lake.
[custom_agent_with_plugin_retri...](https://github.com/langchain-ai/langchain/tree/master/cookbook/custom_agent_with_plugin_retrieval.ipynb) | Build a custom agent that can interact with ai plugins by retrieving tools and creating natural language wrappers around openapi endpoints.
[custom_agent_with_plugin_retri...](https://github.com/langchain-ai/langchain/tree/master/cookbook/custom_agent_with_plugin_retrieval_using_plugnplai.ipynb) | Build a custom agent with plugin retrieval functionality, utilizing ai plugins from the `plugnplai` directory.
[databricks_sql_db.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/databricks_sql_db.ipynb) | Connect to databricks runtimes and databricks sql.
[deeplake_semantic_search_over_...](https://github.com/langchain-ai/langchain/tree/master/cookbook/deeplake_semantic_search_over_chat.ipynb) | Perform semantic search and question-answering over a group chat using activeloop's deep lake with gpt4.
[elasticsearch_db_qa.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/elasticsearch_db_qa.ipynb) | Interact with elasticsearch analytics databases in natural language and build search queries via the elasticsearch dsl api.
[forward_looking_retrieval_augm...](https://github.com/langchain-ai/langchain/tree/master/cookbook/forward_looking_retrieval_augmented_generation.ipynb) | Implement the forward-looking active retrieval augmented generation (flare) method, which generates answers to questions, identifies uncertain tokens, generates hypothetical questions based on these tokens, and retrieves relevant documents to continue generating the answer.
[generative_agents_interactive_...](https://github.com/langchain-ai/langchain/tree/master/cookbook/generative_agents_interactive_simulacra_of_human_behavior.ipynb) | Implement a generative agent that simulates human behavior, based on a research paper, using a time-weighted memory object backed by a langchain retriever.
[gymnasium_agent_simulation.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/gymnasium_agent_simulation.ipynb) | Create a simple agent-environment interaction loop in simulated environments like text-based games with gymnasium.
[hugginggpt.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/hugginggpt.ipynb) | Implement hugginggpt, a system that connects language models like chatgpt with the machine learning community via hugging face.
[hypothetical_document_embeddin...](https://github.com/langchain-ai/langchain/tree/master/cookbook/hypothetical_document_embeddings.ipynb) | Improve document indexing with hypothetical document embeddings (hyde), an embedding technique that generates and embeds hypothetical answers to queries.
[learned_prompt_optimization.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/learned_prompt_optimization.ipynb) | Automatically enhance language model prompts by injecting specific terms using reinforcement learning, which can be used to personalize responses based on user preferences.
[llm_bash.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/llm_bash.ipynb) | Perform simple filesystem commands using language learning models (llms) and a bash process.
[llm_checker.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/llm_checker.ipynb) | Create a self-checking chain using the llmcheckerchain function.
[llm_math.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/llm_math.ipynb) | Solve complex word math problems using language models and python repls.
[llm_summarization_checker.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/llm_summarization_checker.ipynb) | Check the accuracy of text summaries, with the option to run the checker multiple times for improved results.
[llm_symbolic_math.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/llm_symbolic_math.ipynb) | Solve algebraic equations with the help of llms (language learning models) and sympy, a python library for symbolic mathematics.
[meta_prompt.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/meta_prompt.ipynb) | Implement the meta-prompt concept, which is a method for building self-improving agents that reflect on their own performance and modify their instructions accordingly.
[multi_modal_output_agent.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/multi_modal_output_agent.ipynb) | Generate multi-modal outputs, specifically images and text.
[multi_player_dnd.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/multi_player_dnd.ipynb) | Simulate multi-player dungeons & dragons games, with a custom function determining the speaking schedule of the agents.
[multiagent_authoritarian.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/multiagent_authoritarian.ipynb) | Implement a multi-agent simulation where a privileged agent controls the conversation, including deciding who speaks and when the conversation ends, in the context of a simulated news network.
[multiagent_bidding.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/multiagent_bidding.ipynb) | Implement a multi-agent simulation where agents bid to speak, with the highest bidder speaking next, demonstrated through a fictitious presidential debate example.
[myscale_vector_sql.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/myscale_vector_sql.ipynb) | Access and interact with the myscale integrated vector database, which can enhance the performance of language model (llm) applications.
[openai_functions_retrieval_qa....](https://github.com/langchain-ai/langchain/tree/master/cookbook/openai_functions_retrieval_qa.ipynb) | Structure response output in a question answering system by incorporating openai functions into a retrieval pipeline.
[petting_zoo.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/petting_zoo.ipynb) | Create multi-agent simulations with simulated environments using the petting zoo library.
[plan_and_execute_agent.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/plan_and_execute_agent.ipynb) | Create plan-and-execute agents that accomplish objectives by planning tasks with a language model (llm) and executing them with a separate agent.
[press_releases.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/press_releases.ipynb) | Retrieve and query company press release data powered by [Kay.ai](https://kay.ai).
[program_aided_language_model.i...](https://github.com/langchain-ai/langchain/tree/master/cookbook/program_aided_language_model.ipynb) | Implement program-aided language models as described in the provided research paper.
[sales_agent_with_context.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/sales_agent_with_context.ipynb) | Implement a context-aware ai sales agent, salesgpt, that can have natural sales conversations, interact with other systems, and use a product knowledge base to discuss a company's offerings.
[self_query_hotel_search.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/self_query_hotel_search.ipynb) | Build a hotel room search feature with self-querying retrieval, using a specific hotel recommendation dataset.
[smart_llm.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/smart_llm.ipynb) | Implement a smartllmchain, a self-critique chain that generates multiple output proposals, critiques them to find the best one, and then improves upon it to produce a final output.
[tree_of_thought.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/tree_of_thought.ipynb) | Query a large language model using the tree of thought technique.
[twitter-the-algorithm-analysis...](https://github.com/langchain-ai/langchain/tree/master/cookbook/twitter-the-algorithm-analysis-deeplake.ipynb) | Analyze the source code of the twitter algorithm with the help of gpt4 and activeloop's deep lake.
[two_agent_debate_tools.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/two_agent_debate_tools.ipynb) | Simulate multi-agent dialogues where the agents can utilize various tools.
[two_player_dnd.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/two_player_dnd.ipynb) | Simulate a two-player dungeons & dragons game, where a dialoguesimulator class is used to coordinate the dialogue between the protagonist and the dungeon master.
[wikibase_agent.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/wikibase_agent.ipynb) | Create a simple wikibase agent that utilizes sparql generation, with testing done on http://wikidata.org.