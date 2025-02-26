![GenI-Banner](https://github.com/genilab-fau/genial-fau.github.io/blob/8f1a2d3523f879e1082918c7bba19553cb6e7212/images/geni-lab-banner.png?raw=true)

# Prompt Engineering in Requirement Analysis for a Basecamp Bot

We explored prompt engineering techniques for generating requirement analysis for a Basecamp knowledge retrieval bot.

<!-- WHEN APPLICABLE, REMOVE THE COMMENT MARK AND COMPLETE
This is a response to the Assignment part of the COURSE.
-->

* Authors: Ali Talasaz <atalasaz2019@fau.edu>, Daniel Brennet <dbenne11@fau.edu>, Rodolfo Matta <rrivasmatta2021@fau.edu>
* Academic Supervisor: [Dr. Fernando Koch](http://www.fernandokoch.me)

# Research Question

We explore prompt engineering techniques to generate requirement analysis for a Basecamp knowledge retrieval bot.

## Arguments

#### What is already known about this topic

- Large Language Models (LLMs) can be used to generate text, translate languages, write different kinds of creative content, and answer your questions in an informative way.
- LLMs are trained on a massive amount of text data.
- Some of the challenges of working with LLMs include biases, limited understanding of the real world, and difficulty in controlling the output.
- You can do different types of prompting such as zero-shot prompting, few-shot prompting, chain-of-thought prompting, and meta prompting to augment, in a way, the quality of the responses.
- Prompt engineering is the process of designing prompts to get the desired output from an LLM.

#### What this research is exploring

<!-- Free-format; use the topics that are applicable to your exploration -->

- We are exploring prompt engineering techniques for generating requirement analysis for a Basecamp knowledge retrieval bot.
- We built multiple examples of prompt engineering techniques.
- We employ zero-shot, few-shot, chain-of-thought, meta prompting, role-based, self consistency, Generate Knowledge, Automatic Reasoning, and prompt chaining techniques (an attempt for 1-level and 2-level automation).

#### Implications for practice

<!-- Free-format; use the topics that are applicable to your exploration -->

- It will be easier to generate requirement analysis for a Basecamp knowledge retrieval bot.
- We will better understand how to use prompt engineering to generate requirement analysis.
- It will optimize the process of requirement analysis.

# Research Method

We explored prompt engineering techniques for generating requirement analysis for a Basecamp knowledge retrieval bot. We first started with the zero-shot technique as the baseline with a simple prompt and then we noticed that adding additional guidelines to this prompt can produce a better outcome.

We then used the updated zero-shot technique as the template to explore how other techniques can further improve the outcome. The prompt engineering techniques that we explored are:
1. [Few-shot](./prompt-eng/few_shots.ipynb)
2. [Chain-of-thought](./prompt-eng/chain_of_thought.ipynb)
3. [Meta prompting](./prompt-eng/meta_prompt.ipynb)
4. Role-based
5. [Self consistency](./prompt-eng/self_consistency.ipynb)
6. Generate Knowledge
7. Automatic Reasoning
8. Prompt Chaining
  - 1-Level Automation
  - 2-Level Automatin

For the chain-of-thought experiment, we not only added guidance to the prompt, but used a different model, `deepkseep-r1:7b`.

For the `prompt_template.ipynb`, we took some time to explore other parameters like temperature and context size.

<!-- WHEN APPLICABLE AND AVAILABLE -->

# Results

We found that adding additional guidelines to the prompt can produce a better outcome. We also found that using a few-shot technique can further improve the outcome. Chain-of-thought prompting helped to generate more detailed and structured requirement analysis while meta prompting helped to generate more thoughtful and structured requirement analysis.

Role-based prompting helped to generate requirement analysis from different perspectives, and self consistency prompting helped to select the most reliable or coherent requirement analysis. Generate Knowledge Prompting helped to generate more comprehensive requirement analysis and Automatic Reasoning prompting helped to generate more nuanced, step-by-step reasoning for the requirements. Prompt chaining helped to generate requirement analysis in a more structured way.

# Further research

We could explore other prompt engineering techniques, such as prompt engineering with RAG or different ways to achieve 1-leve/2-level automation.

Additionally, the exploration of parameters was brief. An idea for further research is to analyze the quality of the reponses using the prompting engineering techniques here and quantitative measures, like performance in sets like HellaSwag.
