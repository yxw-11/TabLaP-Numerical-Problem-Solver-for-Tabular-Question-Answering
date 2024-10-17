# Numerical-Problem-Solver-for-Tabular-Question-Answering

Question answering on free-form tables (a.k.a. TableQA) is a challenging task because of the flexible structure and the complex schema of tables. Recent studies use Large Lan- guage Models (LLMs) for this task, exploiting their capa- bility in understanding the questions and tabular data which are typically given in natural language and contains many textual fields, respectively. While this approach has shown promising results, it overlooks the challenges brought by numerical values which are common in tabular data, while LLMs are known to struggle with such values. We aim to address this issue and answer numerical questions. We pro- pose a model named TabLaP that uses LLMs as a planner rather than an answer generator, exploiting LLMs’ capabil- ity in multi-step reasoning while leaving the actual numeri- cal calculations to a Python interpreter for accurate calcula- tion. Recognizing the inaccurate nature of LLMs, we further make a first attempt to quantify the trustworthiness of the an- swers produced by TabLaP, such that users can use TabLaP in a regret-aware manner. Experimental results on two bench- mark datasets show that TabLaP is substantially more accu- rate than the state-of-the-art models, improving the answer accuracy by 5.7% and 5.8% on the two datasets, respectively.
