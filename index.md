# NIPS 2017 Workshop: Deep Learning At Supercomputer Scale

Five years ago, it took more than a month to train a state-of-the-art image recognition model on the ImageNet dataset. Earlier this year, Facebook demonstrated that such a model could be trained in an hour. However, if we could parallelize this training problem across the world’s fastest supercomputers (~100 PFlops), it would be possible to train the same model in under a minute. This workshop is about closing that gap: how can we turn months into minutes and increase the productivity of machine learning researchers everywhere?

This one-day workshop will facilitate active debate and interaction across many different disciplines. The conversation will range from algorithms to infrastructure to silicon, with invited speakers from Cerebras, DeepMind, Facebook, Google, OpenAI, and other organizations. When should synchronous training be preferred over asynchronous training? Are large batch sizes the key to reach supercomputer scale, or is it possible to fully utilize a supercomputer at batch size one? How important is sparsity in enabling us to scale? Should sparsity patterns be structured or unstructured? To what extent do we expect to customize model architectures for particular problem domains, and to what extent can a “single model architecture” deliver state-of-the-art results across many different domains? How can new hardware architectures unlock even higher real-world training performance?

Our goal is bring people who are trying to answer any of these questions together in hopes that cross pollination will accelerate progress towards deep learning at true supercomputer scale.

# Confirmed Speakers

1. Priya Goyal - "ImageNet in 1 Hour" - Facebook Research
2. Timothy Lillicrap - "Scalable RL & AlphaGo" - DeepMind
3. Nitish Keskar - "Generalization Gap" - Salesforce Research
4. Scott Gray - "Small World Network Architectures" - OpenAI
5. Matthew Johnson & Daniel Duckworth - "KFAC and Natural Gradients" - Google Brain
6. Tim Salimans - "Evolutionary Strategies" - OpenAI
7. Elad Hoffer - "Closing the Generalization Gap" - Technion
8. Michael James - "Scaling with Small Batches" - Cerebras
9. Azalia Mirhoseini - "Learning Device Placement" - Google Brain
10. Gregory Diamos - "Scaling and Sparsity" - Baidu
11. Simon Knowles - "Scalable Silicon Compute" - GraphCore
12. Sam Smith - "Don't Decay the Learning Rate, Increase the Batchsize" - Google Brain
13. Shankar Krishnan - "Neumann Optimizer" - Google Brain
14. Ujval Kapasi - "Practical Scaling Techniques" - NVIDIA
15. Thorsten Kurth - "Scaling Deep Learning to 15 PetaFlops" - Lawrence Berkeley National Labs
16. Chris Ying - "ImageNet is the New MNIST" - Google Brain

# Important Dates

* 3 November 2017: Submissions due, 4:59pm PST
* 10 November 2017: Decisions announced
* 9 December 2017: Workshop

# Accepted Posters

* Extremely Large Minibatch SGD: Training ResNet-50 on ImageNet in 15 Minutes - Takuya Akiba, Shuji Suzuki, Keisuke Fukuda
* MPIML: A High-Performance Sparse Communication Layer for Machine Learning - Cedric Renggli, Dan Alistarh, Torsten Hoefler
* Deep Gradient Compression: Reducing Communication Bandwidth for Distributed Training - Yujun Lin
* Stabilizing Gradients for Deep Neural Networks via Efficient SVD Parameterization - Jiong Zhang, Qi Lei, Inderjit S. Dhillon 
* Scalable Language Modeling: WikiText-103 on a Single GPU in 12 hours - Stephen Merity, Nitish Shirish Keskar, James Bradbury, Richard Socher
* Supercomputing for Deep Learning: Lessons Learned and Future Directions - Sreenivas R. Sukumar, Peter J. Mendygral, Jacob Balma, Jeffrey Dawson, Alessandro Rigazzi, Aaron Vose, Michael F. Ringenberg, Kristyn J. Maschhoff and Steve L. Scott
* Scaling GRPC Tensorflow on up to 512 nodes of Cori Supercomputer - Amrita Mathuriya, Thorsten Kurth, Vivek Rane, Mustafa Mustafa, Lei Shao, Debbie Bard, Prabhat, Victor W Lee
* Communication Analysis of Hybrid Model and Data Parallelism in Training Neural Networks - Amir Gholami1, Ariful Azad, Kurt Keutzer, Aydın Buluc
* Block-Sparse Recurrent Neural Networks - Sharan Narang, Eric Undersander, Greg Diamos
* Implementing a Sparse Prediction Machine on the Trinity Supercomputer - Boram Yoon, Pete Schultz, Garrett Kenyon
* Sparse Persistent RNNs - Feiwen Zhu, Jeff Pool, Michael Andersch, Jeremy Appleyard, Fung Xie
* Adaptive Memory Networks - Daniel Li, Asim Kadav
* ImageNet Training in Minutes - Yang You, Zhao Zhang, Cho-Jui Hsieh, James Demmel, Kurt Keutzer

# Registration Awards

We will offering NIPS workshop registrations to the four best papers submitted by students at academic instituions.  Please indicate in your submission if you would like to apply for this award.

# Contact Us

Feel free to reach us at `supercomputersfordl2017@gmail.com` with any questions you might have.

# Schedule

* 8:00 - 8:10 - Welcome
* 8:10 - 8:30 - Nitish Keskar - "Generalization Gap"
* 8:30 - 8:50 - Elad Hoffer - "Closing the Generalization Gap"
* 8:50 - 9:10 - Sam Smith - "Don't Decay the Learning Rate, Increase the Batchsize"
* 9:10 - 9:30 - Priya Goyal - "ImageNet in 1 Hour"
* 9:30 - 9:50 - Chris Ying - "ImageNet is the New MNIST"

* Coffee Break

* 10:10 - 10:30 - Matthew Johnson & Daniel Duckworth - "KFAC and Natural Gradients"
* 10:30 - 10:50 - Shankar Krishnan - "Neumann Optimizer"
* 10:50 - 11:10 - Tim Salimans - "Evolutionary Strategies"

* 11:15 - 12:00 - Panel on Future Hardware Directions
  - Greg Diamos, Baidu Research, Moderator
  - Jeff Dean, Google Senior Fellow, Panelist
  - Michael James, Cerebras Chief Software Architect and Co-founder, Panelist
  - Simon Knowles, Graphcore CTO and Co-founder, Panelist
  - Scott Gray, OpenAI, Panelist

* Lunch Break (and posters)

* 1:30 - 1:50 - Azalia Mirhoseini - "Learning Device Placement"
* 1:50 - 2:10 - Gregory Diamos - "Scaling and Sparsity"
* 2:10 - 2:30 - Scott Gray - "Small World Network Architectures"
* 2:30 - 2:50 - Timothy Lillicrap - "Scalable RL & AlphaGo"

* Break

* 3:20 - 3:40 - Thorsten Kurth - "Scaling Deep Learning to 15 PetaFlops"
* 3:40 - 4:00 - Simon Knowles - "Scalable Silicon Compute"
* 4:00 - 4:20 - Ujval Kapasi - "Practical Scaling Techniques"
* 4:20 - 4:40 - Michael James - "Designing for Supercompute-Scale Deep Learning"

* 4:45 - 5:30 - Posters and Mingling

# Organizers
* Erich Elsen, Google Brain
* Danijar Hafner, University College London
* Zak Stone, Google Brain
* Brennan Saeta, Google Brain
* Nicolas Le Roux, Google Brain
