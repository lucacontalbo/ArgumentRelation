# ArgumentRelation
Notebook for the detection of attack/support relation via Adversarial Training

# TODO

1) Do the finetuning with the whole dataset for Debate
2) Create the model that injects discourse markers into the input text and then finetunes [DONE]
3) Find other candidate datasets to check
4) Run the tests on the additional candidate datasets
5) Try more comprehensive tests: apply a gridsearch for the loss weights; [DONE on student_essay]
6) try to add more data for discovery with proper class weighting
7) Try more sophisticated architectures. Specifically:
   - Try adding an additional GRL layer on the predictions;
   - Try testing other adversarial methodologies
   - Research on other architectures
8) Apply various analysis methodologies
