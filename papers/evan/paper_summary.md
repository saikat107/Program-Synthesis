ICLR 2018, [Neural Guided Deductive Search For Real-Time Program Synthesis From Examples](https://arxiv.org/pdf/1804.01186.pdf)

Key summary: 
Most of the sub-problems in the search space does not contribute to the final best program. (Thus, needs to cut down the search space.) They claim that deductive search is Markivinian so that the scope is always local when evaluating sub-problems (? don't think so). They used a tool called PROSE to do the search work, and put different LSTM layers at different depth to give the prediction score for candicates. Their DSL is string manipulation, they collected 375 real-world tasks and compared their method against RobustFILL and DeepCoder. They had the highest accuracy but RobustFill had the fasted speed.   

NIPS 2018, [Neural Guided Constraint Logic Programming for Program Synthesis](https://arxiv.org/abs/1809.02840)

