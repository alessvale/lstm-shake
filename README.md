# Character based language modelling via Deep LSTM Neural Networks

Language modelling with a neural network with 2 LSTM layers, based on <a href = "http://karpathy.github.io/2015/05/21/rnn-effectiveness/" target = _blank>this</a>.</br>
The corpus is given by a collection of sonnets by Shakespeare.</br>
The network has been trained for 100 epochs using GPUs (approximately 1 hour of training time). Weights for the Keras model are provided.</br>
A parameter called <b>temperature</b> controls how conservative the network is in choosing the next character.</br>
Some example, where only minimal editing has been applied.

Temperature: 0.4

 Of</br>
 This his</br> 
 Respects</br> 
 Shape</br> 
 Where thou dost stay no matter then although my </br>
 Foot did </br>
 Stand </br>
 Upon the virtuous</br> 
 Hate that labouring</br>

 Temperature: 0.8

 Day and no let me busy despraved a gon become </br>
 Thy </br>
 Beauty commit them and have ability </br>
 Eyes have I break </br>
 The hersect where breath motion and mine my bright the first </br>
 Ay birth in </br>
 The rear! </br>
 Common and an </br>
 Oft </br>
 Were bras nawht trust halbnyed in grown doth </br>
 Natur'st of shame and thris </br>
 Fiery marrof I't howef </br>
 Their </br>
 Past I be my use that cheries I </br>
 Am blind </br>
