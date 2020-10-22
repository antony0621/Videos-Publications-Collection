Visual signals in a video can be divided into content and
motion. While content specifies which objects are in the
video, motion describes their dynamics. Based on this prior,
we propose the Motion and Content decomposed Generative
Adversarial Network (MoCoGAN) framework for video
generation. The proposed framework generates a video by
mapping a sequence of random vectors to a sequence of
video frames. Each random vector consists of a content
part and a motion part. While the content part is kept
fixed, the motion part is realized as a stochastic process. To
learn motion and content decomposition in an unsupervised
manner, we introduce a novel adversarial learning scheme
utilizing both image and video discriminators. Extensive
experimental results on several challenging datasets with
qualitative and quantitative comparison to the state-of-theart
approaches, verify effectiveness of the proposed framework.
In addition, we show that MoCoGAN allows one to
generate videos with same content but different motion as
well as videos with different content and same motion.