## Research

### Neural Speech Synthesis For Resource-Scarce Languages (2019)

Recent work in sequence-to-sequence neural networks with attention mechanisms,
such as the Tacotron 2 and DCTTS architectures, have brought on substantial
naturalness improvements in synthesised speech. These architectures require
at least an order of magnitude more data than is generally available in
resource-scarce language environments. In this paper we propose an efficient
feed-forward deep neural network (DNN)-based acoustic model, using stacked
bottleneck features, that together with the recently introduced LPCNet vocoder
can be used in resource-scarce language environments, with corpora less than 1
hour in size, to build text-to-speech systems of high perceived naturalness.
We compare traditional hidden Markov model (HMM)-based acoustic modelling for
speech synthesis with the proposed architecture using the World and LPCNet
vocoders, giving both objective and MUSHRA based subjective results, showing
that the DNN LPCNet combination leads to more natural synthesised speech that
can be confused with natural speech. The proposed acoustic model provides for
an efficient implementation, with faster than real time synthesis.

Link to [samples and paper](https://abylouw.github.io/fair2019_samples.html)
