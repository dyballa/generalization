
Here you will find code for fine-tuning various models for image classication and evaluating their capacity for generalizing to unseen classes from the same visual domain, in terms of separability. We apply this to various transformers and CNNs architectures pre-trained on ImageNet, and fine-tuned on two datasets: Chinese calligraphy and CIFAR-100.

We found that the networks vary in their power to extrapolate to unseen classes, both across layers and across architectures. Accuracy is not a good predictor of generalizability, and generalization varies non-monotonically with layer depth. For more information, please refer to the paper:

> Gerrtiz, E., Dyballa, L., Zucker, S. W. (2024), "Zero-shot generalization across architectures for visual classification", _The Twelfth International Conference on Learning Representations (ICLR '24), TinyPapers Track_.

