I want you to come up with a list of 3 other validators we can start creating based off the text image and embeddings examples.
Something that we can outsource to miners and will provide value to the validators or clients
like predictions might be a good idea
or scraping data (tweets) 
or internet data
or music
something that we can implement a miner class and a validator and scoring mechanism for


that, but how can we verify on the validator side that it's correct?
How do you envision it? Client uploads data test, miners do some task with the dataset, and how do validators score it?
How could we share the same global state but have each miner train a specific model layer or gradient or something?

##  Tasks

- [ ] Define how system going to work
    - [X] What product we are going to build
    - [X] User story
    - [x] Examples
    - [X] Scoring System
    - [x] Reward System
    - [X] themes



- [ ] Search Web scrapper codes on Python or any other language
    - [x] Parse Libraries
    - [x] Tweeter scrapper libraries
- [ ] Search other bittensor validators
    - [x] [Bittensor validators list](https://bittensor.org/bittensor-validators-list/)
    - [x] [Bittensor Guru](https://bittensor.guru/)
    - [ ] [Bittensor Model Fine-tuning](https://github.com/salahawk/
    bittensor-model-finetune)
    - [x] Taostat [](https://docs.taostats.io/neuron.html)
        - [ ] [Verify Validator from](https://docs.taostats.io/verify_signature.html)
        - [ ] [How to train an LLM?](https://docs.taostats.io/rlhf.html)
        - [ ] [Neurons](https://docs.taostats.io/neuron.html)
        - [ ] [Fine Tuning Examples/Mining](https://docs.taostats.io/Fine_tuning.html)
            - [ ] [Code](https://github.com/opentensor/clm_model_tuning)
- [ ] Explore Text Prompting Validator and Miner
    - [x] Read and analyse [Walkthrough of Text Prompting Subnet ](https://docs.bittensor.com/subnets/code-walkthrough-text-prompting)
        - [x] Prompt for summary
        - [x] Prompt for question
        - [x] Prompt for answer
        - [x] Initialize the metagraph
        - [x] Create axon server
        - [x] Create dendrite client
        - [x] Initialize the reward model
        - [x] Subnet validator run summary
        - [x] Subnet validator run details
        - [x] Common actions in all prompt runs
        - [x] Create synapse object
        - [x] Send the prompt
        - [x] Send updated weights to subtensor
    - [x] Run code on local 
        - [x] Debug Code and see all details step by step
        - [ ] Details analyse forward class
        - [ ] Validator Class
        - [ ] Reward Class
            - [ ] Reward Weights
            - [ ] Reward Models
    - [ ] [Incentivizing Intelligence: The Bittensor Approach](https://ai-secure.github.io/DMLW2022/assets/papers/6.pdf)

- [x] Search other examples of validators on Bittensor

- [ ] Bittensor resources
    - [x] [Bittensor Validators like Neural Internet are Pioneering Decentralized AI](https://medium.com/@chilltensor/bittensor-validators-like-neural-internet-are-pioneering-decentralized-ai-b61c4b00cc18)
    - [ ] Opensource bittensor ChatGPT https://github.com/crazydevlegend/bittensor-chatgpt
- [ ] Bittensor Fine-Tuning
    - [ ] https://docs.taostats.io/Fine_tuning.html
    - [ ] https://github.com/opentensor/clm_model_tuning?tab=readme-ov-file
    - [ ] https://github.com/salahawk/bittensor-model-finetune
    - [ ] https://github.com/nezamtrm/GPU-parllelism-for-finetuning-huggingface-NLP-models-on-bittensor-dataset
- [] [Bittensor: The LLM Model That Cryptocurrency Built](https://www.youtube.com/watch?v=lNACoEOEu_A)
- [x] [Exploring Bittensor's New Subnets: A Deep Dive](https://flagship.fyi/outposts/ai-crypto)
- [x] [Bittensor TAO: Charting the New Horizon of Decentralized Intelligence](https://flagship.fyi/outposts/ai-crypto/bittensor-tao-ai-crypto-token-exchange-wallet)
exploring-bittensors-new-subnets-a-deep-dive
    - [x] Root
    - [x] Subnet 2 - Text Generation
    - [x] Subnet 3 - Machine Translation
    - [x] Subnet 4 - Multi Modality
    - [x] Subnet 5 - Image Generation
    - [x] Subnet 6 - Storage
    - [x] Subnet 7 - Price Prediction
    - [x] Subnet 8 - Pre Training
    - [x] Subnet 9 - Map Reduce
    - [x] Subnet 10 - Text Training
    - [x] Initialize the reward model

- [ ] Explore Wandb




# Goals

#### The goals for this project are as follows:

1. Define Validator Tasks: Clearly define the tasks that each validator will perform. This includes the type of data they will work with and the specific operations they will perform on this data.

2. Implement Miner Classes: Develop the corresponding miner classes for each validator within the BITTENSOR network. The miner classes should be designed to efficiently perform the validator tasks.

3. Develop Scoring Mechanisms: Create scoring mechanisms for each validator within the BITTENSOR network. These mechanisms should accurately assess the quality of the miner's output and provide useful feedback for improvement.

4. Ensure Robust Validation: The validation process should be robust and reliable. It should accurately assess the quality of the miner's output, even as the volume and complexity of the data increases.

5. Provide Value to Clients: The validators should provide valuable services to our clients. This could include providing insights, making predictions, or performing other useful tasks.

6. Leverage BITTENSOR Technology: All implementations should fully leverage the capabilities of the BITTENSOR technology, ensuring that the validators and miners are optimized for this specific network
