# sketch-rnn
Repository to save the content and updates of my studies about Google Neural Network Sketch-RNN

On models folder you can find two models:
- multiclass: trained on 3 classes (flamingo, palmtree and yoga) - 54K steps
- pretrained_sheep: initialized with multiclass model and trained on sheep class - 13K steps

Both models parameters:

num_steps=60000
save_every=500
dec_rnn_size=2048
dec_model=hyper
enc_rnn_size=512
enc_model=lstm
z_size=128
kl_weight=1.0
kl_weight_start=0.01
kl_tolerance=0.2
batch_size=100
grad_clip=1.0
num_mixture=20
learning_rate=0.001
decay_rate=0.9999
min_learning_rate=0.00001
kl_decay_rate=0.99995
use_recurrent_dropout=True
recurrent_dropout_prob=0.90
use_input_dropout=False
input_dropout_prob=0.90
use_output_dropout=False
output_dropout_prob=0.90
random_scale_factor=0.15
augment_stroke_prob=0.10
conditional=True
