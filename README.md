How to set MODEL.FEATURE_EVAL_SETTINGS parameter for different evaluations
In order to evaluate the model, you need to set MODEL.FEATURE_EVAL_SETTINGS in yaml config file. Various options determine how the model is evaluated and also what part of the model is initialized from weights or what part of the model is frozen.

Below we provide instructions for setting the MODEL.FEATURE_EVAL_SETTINGS for evaluating a pre-trained model on several benchmark tasks. Below are only some example scenarios but hopefully provide an idea for any different use case one might have in mind.