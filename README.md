# Detection-Of-ICMP-Attacks
Machine Learning model to identify the type of ICMP attack.

The dataset contains three different ICMP attacks: TCP, UDP and ICMP attacks. Three different models are trained to predict the type of attack. Each model provides a percentage which is the probability of the attack being of a certain kind. The attack can be classified as either TCP, UDP or ICMP attack based on the highest probability amongst the results (the attack will be classified to the into the attack whose outcome percentage is the highest amongst the 3 models).
