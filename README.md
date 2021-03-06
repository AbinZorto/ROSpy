# Scenario
Consider a social humanoid robot sitting at a table in front of a human child. 

At each interaction, a different colored toy is placed on the table, and the robot should express one
emotion, which depends on both the perceived object properties and the perceived child
behavior. This can be modeled with a Bayesian Network.

The robot can perceive the size of the object (O), and
classify it as either: small(0) or big(1) (they are all equally likely to
happen). 

The robot can perceive human facial expressions
(HE), and classify them as either: happy(0), sad(1), neutral(2) (they
are all equally likely to happen). 

The robot can perceive
human head and eyes movements (actions, HA), and
classify them as either: looking at the robot face, looking at
the colored toy, looking away (they are all equally likely to
happen). 

The robot face can express three possible
happy, sad, neutral.

Note that, during an interaction, the robot might not have
access to all the variables (object size, human expression, human action), due to e.g.
absence of one of the stimuli or failure of a sensor, but still the robot has to decide what
emotion expression is the most likely to be appropriate.
